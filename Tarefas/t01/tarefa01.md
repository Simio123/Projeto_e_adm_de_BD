# Tarefa 01 – Consultas Aninhadas

## Lista de Exercícios

[Link para o documento de exercícios](https://docs.google.com/document/d/1S8QITJFW59ss9CIAiw8UznCbxKVvDAlu4ir75fNoBF0/edit?tab=t.0)

## 📜 Scripts

- [Criação do esquema relacional](tarefa01-create.sql)
- [Inserção de dados no esquema](tarefa01-inserts.sql)

## 📊 Consultas

- [Q01 – Funcionários com salário acima dos salários do departamento 2](tarefa01-q01.sql)
- [Q04 – Funcionários que não são o mais velho](tarefa01-q04.sql)
- [Q07 – Total de funcionários por departamento (incluindo sem gerente)](tarefa01-q07.sql)
- [Q13 – Detalhes de atividades dos projetos](tarefa01-q13.sql)
- [Q16 – Responsáveis de projeto que são gerentes ou ganham mais que o gerente do departamento](tarefa01-q16.sql)
- [Q19 – Funcionários com maior salário por departamento (mesmo sem estar associado a um)](tarefa01-q19.sql)

## 📘 Conceitos

### 🔗 NATURAL JOIN
`NATURAL JOIN` une automaticamente tabelas com base em colunas de **mesmo nome e tipo**. É simples de usar, mas deve ser aplicado com cuidado para evitar joins inesperados.

**Exemplo:**
```sql
SELECT * FROM funcionario NATURAL JOIN departamento;
