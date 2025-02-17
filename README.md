# Controle-de-Gastos-Residenciais

Este projeto é um sistema para controle de gastos residenciais, permitindo o cadastro de pessoas e transações financeiras, além da consulta de totais de receitas e despesas.

Tecnologias Utilizadas

Backend:

Python (Flask)

SQLite (Banco de dados relacional)

Flask-CORS (Para permitir comunicação entre frontend e backend)

Frontend:

React.js (Interface de usuário)

Axios (Requisições HTTP para comunicação com o backend)

Tailwind CSS (Estilização da aplicação)

Como Rodar o Sistema

🔧 1. Configuração do Backend

Instalar dependências:

pip install flask flask-cors

Salvar o código backend como app.py e rodar:

python app.py

O backend será iniciado em:

http://localhost:5000

🖥️ 2. Configuração do Frontend

Criar e acessar a pasta do projeto React:

npx create-react-app frontend
cd frontend

Instalar dependências:

npm install axios

Substituir o conteúdo de src/App.js pelo código do frontend.

Iniciar o frontend:

npm start

Acesse no navegador:

http://localhost:3000

📌 Funcionalidades

Cadastro de Pessoas: Nome e idade

Cadastro de Transações: Descrição, valor e tipo (receita/despesa)

Consulta de Totais: Exibe receitas, despesas e saldo de cada pessoa

📌 Próximos Passos

Implementar edição e remoção de transações

Melhorar a interface gráfica

Adicionar autenticação de usuários

🚀 Desenvolvido para fins de aprendizado e prática de desenvolvimento Full Stack.
