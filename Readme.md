![logo](imagens/logo.png)

**_Exercicio Semana 7 Módulo 1 FMT_**

## [M1S7] Ex 1 - Modelagem

### Descrição

Modelar tabelas "curso" e "professor"

1. Tabela curso deve conter ao menos:
- Colunas:
  - ID
  - Nome
  - Descrição
  - Professores
  - Carga Horária

2. Tabela professor deve conter ao menos:
- Colunas:
    - ID
    - Nome
    - Especialidade

### Resultado

<div align="center">
    <img src="imagens/modelagem.png" alt="modelagem lógoca">
</div>


## [M1S7] Ex 2 - DDL (Professor)

### Descrição

Com a modelagem pronta, vamos para o banco de dados.
Crie *DDl* para a tabela "_professor_" conforme sua modelagem

## Resultado 

Aplicativo usado DBeaver.

- Criar Banco de Dados "cursos"
<div align="center">
  <img src="imagens/create_db.png" alt="Create Data Base Código">
</div>

- DDL tabela professor

<div align="center">
  <img src="imagens/ddl_professor.png" alt="DDL">
</div>

## [M1S7] Ex 3 - DML (Professor)

### Descrição

Tabela criada! Estão faltando seus dados. 
Crie ao menos 5 comandos 'insert' para a tabela _professor_ com dados diferentes.

## Resultado

<div align="center">
  <img src="imagens/dml_professor.png" alt="DML">
</div>

## [M1S7] Ex 4 - DDL (Curso)

### Descrição 

Após criar sua primeira tabela a segunda é sempre mais fácil
Crie *DDL* para a tabela _curso_ conforme sua modelagem

## Resultado

<div align="center">
  <img src="imagens/ddl_professor.png" alt="DDL">
</div>

## [M1S7] Ex 5 - DML (Curso)

### Descrição

O próximopasso são os dados!
Crie ao menos 3 comandos _insert_ para a tabela _curso_ cm dados diferentes

## Resultado

<div align="center">
<img src="imagens/dml_curso.png" alt="DML">
</div>

## [M1S7] Ex 6 - Modelagem (Relacionamento)

### Descrição

Volte na modelagem para implementarmos o relacionamento entre as tabelas
Relacione as tabelas onde um curso pode ter vários _professores_ (N:1)

## Resultado

<div align="center">
<img src="imagens/modelagem_fk.png" alt="Modelagem Relacionamento">
</div>

## [M1S7] Ex 7 - Dl (Relacionamento)

### Descrição

Alterando a modelagem é possível ter uma visão da alteração necessária no banco de dados.
Cria *DDL* para o relacionamento entre as tabelas _curso_ e _professor_ conforme sua modelagem.

## Resultado

<div align="center">
<img src="imagens/foreign_key.png" alt="Foreign Key">
</div>

- Relacionamento (1:N) - (Curso -> Professores)

<div align="center">
<img src="imagens/fk.png" alt="Modelagem FK">
</div>
