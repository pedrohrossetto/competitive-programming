*[Leia em português](README.pt-BR.md)*


# competitive-programming

My solutions to online judge problems.

| Judge | Problem | Language | Topic |
|---|---|---|---|
| beecrowd | [1001–1011](beecrowd/beginner/) | Rust | Beginner: I/O, arithmetic |
| beecrowd | [2602](beecrowd/sql/2602_postgresql/solution.sql) | PostgreSQL | SELECT with filter |
| LeetCode | [1. Two Sum](leetcode/0001_two-sum.py) | Python | Hash map |
| LeetCode | [938. Range Sum of BST](leetcode/0938_range-sum-bst.cpp) | C++ | Binary search tree |
| LeetCode | [1768. Merge Strings Alternately](leetcode/1768_merge-strings-alternately.py) | Python | Two pointers |

Each beecrowd Rust solution is its own crate with `input.txt` and `expected.txt`:

```bash
cd beecrowd/beginner/1001_rust && cargo run < input.txt | diff - expected.txt
```

Naming: `<problem-id>_<language or title>`, with the ID zero-padded so folders sort numerically.
