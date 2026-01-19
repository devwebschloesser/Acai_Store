# 🍧 Projeto Açaí Online

```Aplicação web desenvolvida em **React.js** para um sistema de pedidos de açaí online, permitindo que clientes naveguem pelos produtos, adicionem itens ao carrinho e finalizem pedidos de forma prática e intuitiva.

O projeto utiliza **Vite** para build rápido, **Context API** para gerenciamento de estado global (carrinho) e uma arquitetura organizada por componentes e páginas.


## 🚀 Tecnologias Utilizadas

- **React.js**
- **Vite**
- **JavaScript (ES6+)**
- **JSX**
- **Context API**
- **CSS**
- **ESLint**

---

## 📁 Estrutura do Projeto

PROJETO-ACAI-ONLINE
├── public
├── src
│ ├── assets
│ ├── Components
│ │ ├── BotaoWhatsapp.jsx
│ │ ├── Depoimentos.jsx
│ │ ├── Localizacao.jsx
│ │ └── logo.jsx
│ ├── Context
│ │ └── CarrinhoContext.jsx
│ ├── Global
│ │ └── globalStyled.js
│ ├── Pages
│ │ ├── carrinho.jsx
│ │ ├── DepoimentosPage.jsx
│ │ └── home.jsx
│ ├── Styles
│ ├── App.jsx
│ └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md

yaml
Copiar código

---

## 🧠 Funcionalidades

- Página inicial com apresentação do negócio
- Exibição de depoimentos de clientes
- Página de localização
- Carrinho de compras funcional
- Gerenciamento de estado global com Context API
- Botão de contato via WhatsApp
- Layout responsivo e organizado

---

## 🛒 Carrinho de Compras

O carrinho é gerenciado globalmente através do **CarrinhoContext**, permitindo:

- Adicionar produtos
- Remover produtos
- Controlar quantidade
- Compartilhar dados entre páginas

---

## 🖥️ Como Rodar o Projeto Localmente

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn

### Passo a passo

bash
# Clone o repositório
git clone https://github.com/devwebschloesser/PROJETO-ACAI-ONLINE.git

# Acesse a pasta do projeto
cd PROJETO-ACAI-ONLINE

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
Após isso, acesse no navegador:

arduino
Copiar código
http://localhost:5173
🎨 Estilização
Estilos globais centralizados em globalStyled.js

Organização modular para facilitar manutenção e escalabilidade

```
