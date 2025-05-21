# Sistema de Gestão de Fornecedores e Compras (Flask)

Este projeto é um sistema web básico, feito com **Python + Flask**, para gerenciar **fornecedores** e **compras** de uma empresa. Ele permite o cadastro, edição, exclusão, visualização e exportação de dados de forma simples, acessível via navegador.

---

## Funcionalidades principais

- Autenticação de usuário com senha criptografada
- Cadastro e listagem de **fornecedores**
- Registro de **compras** por fornecedor
- Filtro de busca por nome de fornecedor
- Paginação dos dados
- Edição e exclusão com proteção de dados relacionados
- Exportação de fornecedores e compras em formato CSV
- Feedback visual com mensagens flash
- Interface web renderizada com HTML via `render_template_string`

---

## Acesso ao sistema

- Acesse via: `http://localhost:5000/login`
- Usuário padrão: `admin`
- Senha padrão: `admin`

---

## Como rodar

1. Certifique-se de ter o Python 3 instalado.
2. Instale as dependências:

```bash
pip install flask flask_sqlalchemy flask_login werkzeug
