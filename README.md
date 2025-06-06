# 💻 Projeto Node.js com MySQL — E-commerce de Peças de Computador

Este projeto é um sistema com fins pedagógicos de um e-commerce desenvolvido com **Node.js** e **MySQL**, implementando na Unidade Curricular 13 - "Executar os processos de codificação,
manutenção e documentação de aplicativos computacionais para internet", do Senac unidade Salto, onde o foco é fazer com que o aluno tenha seus primeiros contatos com o desenvolvimento back-end.

---

## 📥 Clonar o repositório

Abra o terminal e digite:

```bash
git clone https://github.com/leorocco/UC13_NodeJS.git
cd UC13_NodeJS
```

---

## ⚙️ Instalar as dependências

Após acessar o diretório do projeto, rode:

```bash
npm install
```

Esse comando instalará todas as dependências listadas no `package.json`.

---

## 🛠️ Executar o instalador do banco de dados

Certifique-se de que o **MySQL está rodando** e que o usuário/senha estão configurados corretamente no arquivo `db/setup.js`.

Para criar o banco de dados, tabelas e inserir os dados iniciais, execute:

```bash
npm run setup
```

Esse comando irá rodar o script `setup.js` que está localizado em `db/setup.js` e executará automaticamente o conteúdo do `setup.sql`.

---

## 📂 Estrutura esperada

```
projeto/
├── db/
│   ├── setup.js
│   └── setup.sql
├── node_modules/
├── package.json
├── package-lock.json
└── README.md
```

---

## ✅ Requisitos

- [Node.js instalado no Windows ou Linux](https://nodejs.org/pt/download)
- [MySQL instalado e rodando no Windows ou Linux](https://www.alura.com.br/artigos/mysql-instalacao-configuracao?srsltid=AfmBOoo65gaX8aOV31G8q3nuUgHZHwNx7RdH6k4YPSQpp0Fj-_Wt89Nw)
- Um usuário com permissões de criação de banco

---

## 🧪 Teste

Após a execução do `npm run setup`, verifique no seu MySQL se o banco `ecommerce_pc` foi criado com as tabelas e dados inseridos corretamente.

---

## 🗃️ Licença

Este projeto é livre para fins educacionais.

## 📚 Referências Bibliográficas e Direitos 