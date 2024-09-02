
---

# 🗃️ **SQL - Criando Sistemas de Banco de Dados**

---

## 📚 **Introdução ao SQL Server 2016**

### 🏛️ **Banco de Dados Relacional**

Um banco de dados relacional é uma arquitetura na qual os dados são armazenados em tabelas retangulares, semelhantes a uma planilha. Essas tabelas frequentemente possuem uma informação chave que as relaciona, facilitando a inserção, alteração, exclusão e recuperação de dados.

### 🛠️ **Design do Banco de Dados**

A construção de um banco de dados passa por quatro etapas:

- **Modelo Descritivo:** Documento indicando a necessidade de construção de um banco de dados.
- **Modelo Conceitual:** Extração de informações do modelo descritivo (substantivos e propriedades).
- **Modelo Lógico:** Diagrama das entidades e atributos encontrados nos modelos anteriores.
- **Modelo Físico:** Associado ao software de gerenciamento de banco de dados, neste caso, o SQL Server 2016.

**Componentes:**

- **Tabelas (entidades):** Local de armazenamento das informações.
- **Campos (atributos):** Características da tabela.
- **Chave Primária:** Campo único que define a exclusividade da linha.
- **Relacionamento:** Relação entre tabelas (1 para 1, 1 para N, M para N).
- **Dicionário de Dados:** Descreve as características da tabela.

### 🗂️ **Normalização de Dados**

O processo de organizar dados e eliminar informações redundantes de um banco de dados é chamado normalização.

---

## 🛠️ **Arquitetura Cliente-Servidor**

---

## 🧑‍💻 **As Linguagens SQL e T-SQL**

### 🖥️ **SQL Server**

- **Ferramentas de Gerenciamento:** SQL Server Management Studio (SSMS)

---

## 🛠️ **Criando um Banco de Dados**

### 🗃️ **CREATE DATABASE**

```sql
CREATE DATABASE nome_do_banco;
USE nome_do_banco;
```

### 📋 **CREATE TABLE**

```sql
CREATE TABLE TB_ALUNO (
    COD_ALUNO INT IDENTITY,
    NOME VARCHAR(50)
);
```

### 🏷️ **Tipos de Dados**

- **Inteiros, Bit, Numéricos exatos**
- **Valores monetários, Números aproximados**
- **Data e Hora, Strings de caracteres ANSI e Unicode**
- **Strings Binárias, Outros tipos de Dados**

### 🔢 **Campo de Autonumeração**

```sql
CREATE TABLE TB_ALUNO (
    COD_ALUNO INT IDENTITY,
    NOME VARCHAR(50)
);
```

### ⚙️ **Constraints**

- **PRIMARY KEY, FOREIGN KEY, CHECK, UNIQUE, DEFAULT**

### ❓ **Nulabilidade**

```sql
CREATE TABLE TB_ALUNO (
    COD_ALUNO INT IDENTITY NOT NULL,
    NOME VARCHAR(50) NOT NULL
);
```

---

## 🔄 **Manipulando Dados**

### 🆗 **Constantes**

### ➕ **Inserção de Dados**

- Utilização de **TOP** em uma instrução **INSERT**
- **OUTPUT**

### 🔄 **Atualização e Exclusão de Dados**

- **UPDATE**
- **DELETE**
- **OUTPUT** para **DELETE** e **UPDATE**

### 🔄 **Transações**

---

## 🔍 **Consultando Dados**

### 🗂️ **SELECT**

- **Ordenação de Dados**
- **Operadores Relacionais**
- **Operadores Lógicos**
- **Consulta de Intervalos com BETWEEN**
- **Consulta com Base em Caracteres**
- **Consulta de Valores Pertencentes ou não a uma Lista de Elementos**
- **Lidando com Valores Nulos**
- **Substituição de Valores Nulos**
- **UNION**
- **EXCEPT e INTERSECT**

---

## ℹ️ **About**

Introdução ao SQL Server 2016, criando um banco de dados, manipulando dados, e consultando dados.

---

## 📚 **Resources**

- **Readme**
- **Activity**

---

## ⭐ **Stars**

0 stars

### 👁️ **Watchers**

1 watching

### 🍴 **Forks**

0 forks

### 📦 **Releases**

No releases published

### 📦 **Packages**

No packages published

