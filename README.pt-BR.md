*[Read in English](README.md)*


# competitive-programming

Minhas soluções de problemas de juízes online.

| Juiz | Problema | Linguagem | Tópico |
|---|---|---|---|
| beecrowd | [1001–1011](beecrowd/beginner/) | Rust | Iniciante: E/S, aritmética |
| beecrowd | [2602](beecrowd/sql/2602_postgresql/solution.sql) | PostgreSQL | SELECT com filtro |
| LeetCode | [1. Two Sum](leetcode/0001_two-sum.py) | Python | Hash map |
| LeetCode | [938. Range Sum of BST](leetcode/0938_range-sum-bst.cpp) | C++ | Árvore binária de busca |
| LeetCode | [1768. Merge Strings Alternately](leetcode/1768_merge-strings-alternately.py) | Python | Dois ponteiros |

Cada solução Rust do beecrowd é um crate com `input.txt` e `expected.txt`:

```bash
cd beecrowd/beginner/1001_rust && cargo run < input.txt | diff - expected.txt
```

Nomes: `<id-do-problema>_<linguagem ou título>`, com o ID preenchido com zeros para ordenar numericamente.
