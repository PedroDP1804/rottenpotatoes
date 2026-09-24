# RottenPotatoes 🍿

Aplicação web simples para gerenciamento e ordenação de filmes, desenvolvida como projeto prático para o curso de Engenharia de Software utilizando **Ruby on Rails** e **HAML**.

---

## 📌 Sobre o Projeto

O **RottenPotatoes** permite visualizar, cadastrar, editar e remover informações sobre filmes (CRUD completo). Além das funcionalidades básicas de gerenciamento, a aplicação possui recursos para ordenação dinâmica da lista por **título**, **classificação** (*rating*) e **data de lançamento**.

### Tecnologias Utilizadas
* **Linguagem:** Ruby (3.x)
* **Framework Web:** Ruby on Rails (>= 7.0)
* **Template Engine:** HAML
* **Banco de Dados:** SQLite3

---

## 🚀 Como Instalar e Executar a Aplicação

Siga as instruções abaixo para rodar o projeto em seu ambiente local.

### 1. Pré-requisitos

Certifique-se de ter os seguintes programas instalados no seu computador:
* **Git**
* **Ruby** (versão 3.0 ou superior)
* **Bundler** (`gem install bundler`)

### 2. Clonar o Repositório

```bash
git clone [https://github.com/PedroDP1804/rottenpotatoes](https://github.com/PedroDP1804/rottenpotatoes)
cd rottenpotatoes
```

### 3. Instalar Dependências

Instale as gems necessárias listadas no `Gemfile`:

```bash
bundle install
```

### 4. Configurar o Banco de Dados

Crie o banco de dados e rode as migrações e seeds:

```bash
bin/rails db:prepare
bin/rails db:migrate
bin/rails db:seed
```

### 5. Iniciar o Servidor Local

Rode a aplicação localmente:

```bash
bin/rails server
```

### 6. Acessar no Navegador

Abra o seu navegador e acesse o endereço:
👉 **http://localhost:3000/movies**

---

## 🛠 Funcionalidades

- [x] **Listagem de Filmes:** Exibição da tabela com todos os filmes cadastrados.
- [x] **Ordenação Dinâmica:** Clique nos cabeçalhos para ordenar por Título, Classificação ou Data de Lançamento.
- [x] **CRUD Completo:** Telas de criação, edição, visualização e remoção de filmes.