# RPUtilidades Store (Gourmet Mix)

<p align="center">
  <img src="https://img.shields.io/badge/React-19.x-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite-8.x-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 8" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-v4.3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS v4" />
  <img src="https://img.shields.io/badge/Oxlint-1.x-FF69B4?style=for-the-badge" alt="Oxlint" />
  <img src="https://img.shields.io/badge/Deploy-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/License-MIT-green.style=for-the-badge" alt="License" />
</p>

## 📌 Sobre o Projeto

O **RPUtilidades Store** é uma loja virtual moderna, rápida e de alto padrão estético desenvolvida para a marca RPUtilidades Gourmet Mix. O projeto conta com design responsivo, animações fluidas e uma arquitetura construída com a stack mais recente do ecossistema React.

## 🚀 Tecnologias Utilizadas

- **React**: 19.2
- **Bundler & Dev Server**: Vite 8
- **Estilização**: Tailwind CSS v4 (`@tailwindcss/vite`)
- **Animações**: Framer Motion 12
- **Ícones**: Lucide React
- **Roteamento**: React Router DOM v7
- **Linter Ultra-rápido**: Oxlint

## 📋 Pré-requisitos

- **Node.js**: >= 18.0.0
- **npm**: Versão mais recente

## 🔧 Instalação e Execução Local

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/usuario/rp-utilidades-store.git
   cd rp-utilidades-store
   ```

2. **Instalar dependências**
   ```bash
   npm install
   ```

3. **Iniciar o Servidor de Desenvolvimento**
   ```bash
   npm run dev
   ```
   Acesse a aplicação em `http://localhost:5173`.

4. **Gerar Build de Produção**
   ```bash
   npm run build
   ```

5. **Visualizar o Build Localmente**
   ```bash
   npm run preview
   ```

## 🧪 Execução de Linters

- **Verificar erros de código com Oxlint**:
  ```bash
  npm run lint
  ```

## 📁 Estrutura do Projeto

```
rp-utilidades-store/
├── public/                 # Favicon, SVG de ícones e mídias estáticas
├── src/                    # Código fonte da loja
│   ├── assets/             # Imagens e recursos gráficos
│   ├── components/         # Componentes reutilizáveis de UI
│   ├── pages/              # Páginas da aplicação
│   ├── App.jsx             # Estrutura principal com rotas
│   └── main.jsx            # Ponto de entrada React
├── .oxlintrc.json          # Regras de validação do Oxlint
├── index.html              # HTML base da aplicação SPA
├── vercel.json             # Configurações de deploy na Vercel
├── vite.config.js          # Configuração do bundler Vite
└── package.json            # manifesto de dependências e scripts npm
```

## 📄 Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).
