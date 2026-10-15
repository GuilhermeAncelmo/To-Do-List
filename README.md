# To-Do List — quadro Kanban

Aplicação de tarefas com interface React e API Flask. Permite criar, mover e excluir tarefas; o backend salva os dados em um arquivo JSON local.

![Prévia do quadro de tarefas](https://github.com/user-attachments/assets/a909b499-9a21-4fe0-8785-819119062c9d)

## Stack atual

- Frontend: React, JavaScript e Vite
- Backend: Python, Flask e Flask-CORS
- Persistência: arquivo JSON local

## Funcionalidades

- Criação de tarefas
- Organização por status em um quadro Kanban
- Atualização e exclusão de tarefas
- Comunicação entre frontend e API HTTP

## Executar localmente

1. Clone: `git clone https://github.com/GuilhermeAncelmo/To-Do-List.git`.
2. Em `backend`, instale `flask` e `flask-cors`; depois execute `python app.py`. A API inicia em `http://localhost:5000`.
3. Em `front-end`, execute `npm install` e `npm run dev`.
4. Abra a URL informada pelo Vite. O frontend usa `http://localhost:5000/tasks`.

## Estado do projeto

Projeto de estudo. O arquivo JSON oferece persistência simples para desenvolvimento local. Próximos passos: registrar as dependências Python em arquivo próprio, adicionar testes e configurar a URL da API por ambiente.
