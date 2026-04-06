# 🎨 Interfaces com React e Tailwind CSS

Projeto focado no desenvolvimento de interfaces modernas com React e Tailwind CSS. Construímos uma aplicação completa com autenticação, dashboard, formulários, upload de arquivos, paginação e controle de permissões por perfil de usuário.

<div align="center">

| Login | Criar Conta |
|:---:|:---:|
| <img width="100%" alt="Página de Login" src="https://github.com/user-attachments/assets/afe916f5-c58a-4798-8031-f23a5f953918" /> | <img width="100%" alt="Página de Criar Conta" src="https://github.com/user-attachments/assets/9e9bd7ce-0946-4d44-9e17-0f0195d8a6f1" /> |
| *Tela de autenticação para acesso à plataforma* | *Cadastro de novo usuário na aplicação* |

| Solicitação Enviada | Dashboard |
|:---:|:---:|
| <img width="100%" alt="Solicitação Enviada" src="https://github.com/user-attachments/assets/a3e0e82c-f1cf-4f46-8b87-8abd01e1ca4f" /> | <img width="100%" alt="Dashboard" src="https://github.com/user-attachments/assets/719f4bf8-7ecd-459c-b33e-7f618b2f46dd" /> |
| *Confirmação de solicitação de reembolso enviada com sucesso* | *Painel de gerenciamento com listagem, pesquisa e paginação* |

| Formulário de Reembolso | Página Not Found |
|:---:|:---:|
| <img width="100%" alt="Solicitação de Reembolso" src="https://github.com/user-attachments/assets/cece722a-ca13-4b9f-9b3b-13cbaa13e54b" /> | <img width="100%" alt="Not Found" src="https://github.com/user-attachments/assets/616c2ee2-2b09-4b21-9c88-e411b664da01" /> |
| *Formulário para cadastro de nova solicitação de reembolso* | *Página 404 para rotas inválidas com código no VS Code* |

</div>

> 🔌 API utilizada neste projeto: [-API-desenvolvida-Para-o-Projeto-Interfaces-com-React-e-Tailwind-CSS-](https://github.com/FernandoCyber3/-API-desenvolvida-Para-o-Projeto-Interfaces-com-React-e-Tailwind-CSS-/tree/main)
---

## 🛠️ Tecnologias Utilizadas

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## ✨ Funcionalidades

- 🔐 **Autenticação** — rotas protegidas, AuthLayout e página de SignUp com link de navegação
- 📋 **Formulário de Reembolso** — campos, select com categorias, inputs lado a lado e componente de upload
- 📊 **Dashboard** — listagem de reembolsos, pesquisa, paginação e visualização de arquivos
- 💅 **Tailwind CSS** — estilização com classes utilitárias e tema personalizado
- 👤 **Role do Usuário** — controle de permissões e exibição de conteúdo por perfil
- 🔄 **Componentes Reutilizáveis** — Header, AppLayout, Loading, RefundItem, Pagination e mais
- ❌ **Página Not Found** — tratamento de rotas inválidas

---

## 📦 Instalação e Execução

### Pré-requisitos
- Node.js v18+

### Passo a Passo

**1. Clone o repositório:**
```bash
git clone https://github.com/FernandoCyber3/Interfaces-com-React-e-Tailwind-CSS.git
cd seu-repositorio
```

**2. Instale as dependências:**
```bash
npm install
```

**3. Inicie o servidor de desenvolvimento:**
```bash
npm run dev
```

> A aplicação estará disponível em: http://localhost:5173

---

## 📚 Principais Módulos

### 🔐 Autenticação
Criação de auth-routes, AuthLayout, componentes de Input e Button, submit com eventos de formulário e navegação entre páginas.

### 📋 Formulário de Reembolso
Rota de refund, AppLayout, Header, formulário completo com Select populado por categorias, inputs lado a lado, componente de upload e botão de envio com confirmação.

### 📊 Dashboard
Página de dashboard com input de pesquisa, variantes de botão, componente RefundItem, scroll customizado, formatação de moeda (`formatCurrency`), paginação com `handlePagination`, visualização de arquivos e componente de Loading.
