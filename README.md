
CRUD-JS

CRUD-JS é um aplicativo web que permite cadastrar, listar, editar e excluir pensamentos e frases, usando HTML, CSS e JavaScript, com Axios para comunicação com um backend fake (JSON Server).

É um projeto simples, mas perfeito para praticar CRUD (Create, Read, Update, Delete), manipulação de DOM e requisições HTTP.

🔹 Funcionalidades

Adicionar pensamentos: Cadastrar novos pensamentos com conteúdo e autoria.

Listar pensamentos: Visualizar todos os pensamentos cadastrados.

Editar pensamentos: Alterar informações de pensamentos existentes.

Excluir pensamentos: Remover pensamentos da lista.

🔹 Tecnologias utilizadas

HTML / CSS → Estrutura e estilo da interface.

JavaScript → Lógica do frontend e manipulação do DOM.

Axios → Requisições HTTP para o backend.

JSON Server → Backend fake para testes de CRUD localmente.

🔹 Como rodar o projeto

Clonar o repositório:

git clone https://github.com/Pedro1325/Crud-Js.git


Instalar JSON Server (se ainda não tiver):

npm install -g json-server


Rodar o backend:

cd backend
npm start


Isso vai iniciar a API fake em: http://localhost:3000

Rodar o frontend:

Abra o arquivo index.html com Live Server (VS Code)

Acesse o frontend em: http://localhost:5500

🔹 Estrutura do projeto
CRUD-JS/
│
├─ backend/        # Backend fake (JSON Server)
│   ├─ db.json
│   └─ package.json
│
├─ css/            # Estilos
├─ js/             # Scripts JS
├─ index.html      # Página principal
└─ README.md       # Documentação

🔹 Objetivo do projeto

Praticar operações CRUD, manipulação de dados no frontend e integração de JavaScript com Axios, aprendendo também a organizar e versionar um projeto no GitHub.

Se você quiser, posso te fazer uma versão ainda mais curta e chamativa, pronta para aparecer direto na página do GitHub, que atrai atenção e mostra rapidamente do que se trata o projeto.
