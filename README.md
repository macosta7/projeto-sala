# 🏫 Checkin Room

Sistema web para automação do processo de **reserva de salas em ambientes acadêmicos**. A plataforma possibilita que estudantes, professores e coordenadores verifiquem a disponibilidade de salas em tempo real, realizem reservas com antecedência e recebam notificações automáticas quando a solicitação for aprovada ou recusada. Administradores têm acesso a um painel de controle com gestão de solicitações.

---

## ✅ Funcionalidades

- Login para diferentes perfis de usuário (aluno, professor, coordenador, recepção)
- Cadastro e edição de dados pessoais
- Consulta de horários disponíveis por sala
- Realização de reservas com data e horário
- Painel administrativo com aprovações de solicitações
- Notificações automáticas para usuários
- Testes unitários com Jest

---

## 📁 Estrutura de Pastas

mvc-boilerplate/      
│      
├── config/ # Configurações, como conexão com o banco de dados     
│ └── db.js     
├── controllers/ # Lógica das requisições HTTP     
│ └── aboutController.js      
│ └── contactController.js      
│ └── homeController.js      
│ └── userController.js      
├── models/ # Definições das entidades do banco (ORM ou SQL)       
│ └── userModel.js       
├── routes/ # Arquivos de rotas do sistema       
│ └── index.js      
│ └── frontRoutes.js       
│ └── userRoutes.js       
├── services/ # Funções reutilizáveis e lógicas de negócio        
│ └── userService.js        
├── assets/ # Imagens, fontes e arquivos públicos       
├── scripts/ # Scripts JS públicos (front-end)       
├── public/      
│ └── css/       
│ └─────style.css # Estilos CSS      
├── tests/ # Testes unitários com Jest      
│ └── userController.test.js      
│ └── userModel.test.js     
│ └── userRoutes.test.js       
│ └── userService.test.js       
├── views/ # Vizualização da aplicação       
├── .gitignore # Arquivos/ pastas ignorados pelo Git       
├── .env # Variáveis de ambiente       
├── jest.config.js # Configuração do Jest para testes      
├── package-lock.json # Lockfile do npm     
├── package.json # Dependências e scripts do Node.js      
├── PI-WAD.md # Arquivo da documentação do projeto     
├── readme.md # Documentação do projeto      
├── server.js # Inicialização do servidor Express      
└── rest.http # Arquivo opcional para testes de API via VSCode      

## ▶️ Como Executar o Projeto Localmente

### 🔧 Pré-requisitos

- [Node.js](https://nodejs.org/)
- Banco de dados PostgreSQL ou Supabase
- Um terminal compatível com comandos `npm`

---

### ⚙️ Instalação

1. **Clone o repositório**

```bash
git clone https://github.com/macosta7/mvc-boilerplate.git
cd mvc-boilerplate 
```  

2. **Instale as dependências**
```bash
npm install
npm init -y
npm install express ejs
```  

### 🗃️ Inicializar o Banco de Dados

Antes de rodar a aplicação, inicialize o banco com o comando:

```bash
npm run init-db
```

### 🚀 Executar o Servidor

1. Inicie a aplicação com:

```bash
node app.js
```

2. O servidor estará rodando em:

```arduino
http://localhost:3000
```

