# Lab MySQL MediCore — Matrícula 09022004

Site estático de evidências da atividade de Banco de Dados (MySQL).

## Conteúdo
- `index.html` — página única com identificação, schema, procedure (Grupo A),
  índice + EXPLAIN (Grupo B) e reflexão.
- `assets/` — screenshots do MySQL Workbench:
  - `schema-workbench.png` — schema `lab_09022004` e as 4 tabelas
  - `call-procedure.png` — teste do `CALL` da procedure + erro do SIGNAL
  - `explain-antes.png` — EXPLAIN sem índice
  - `explain-depois.png` — EXPLAIN com índice composto (coluna `key` preenchida)

## SQL
Os scripts testados estão em `C:\Users\victo\mysql-local\prova\`:
- `lab_setup.sql` — schema, tabelas, dados e procedure
- `missao4_explain.sql` — índice composto + EXPLAIN antes/depois

## Deploy
Publicado na Vercel como site estático (Framework Preset: **Other**).
