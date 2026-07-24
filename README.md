# NEXUS E-commerce - Frontend

Bem-vindo ao repositório do **NEXUS E-commerce**, uma aplicação frontend moderna, responsiva e focada na melhor experiência de usuário, construída com React e Vite.

## 🚀 Tecnologias Utilizadas

- **React 18** (UI Library)
- **Vite** (Build Tool & Dev Server)
- **CSS Vanilla** (Estilização com CSS Variables e animações customizadas)
- **Glassmorphism Design** (Estética premium, clean e futurista)

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas no seu sistema:

- [Node.js](https://nodejs.org/) (Versão 18 ou superior recomendada)
- [NPM](https://www.npmjs.com/) (Vem junto com o Node.js) ou [Yarn](https://yarnpkg.com/) / [pnpm](https://pnpm.io/)

## ⚙️ Configuração Inicial

1. **Navegue até a pasta do projeto**:
   ```bash
   cd Front
   ```

2. **Instale as dependências**:
   ```bash
   npm install
   ```

3. **Configure as Variáveis de Ambiente**:
   O arquivo `.env` já foi criado na raiz do projeto com as variáveis base da aplicação (como URL da API backend e Nome do App). Se você precisar de configurações exclusivas da sua máquina que não devem ir para o repositório, crie um arquivo chamado `.env.local`.

## 💻 Como Rodar a Aplicação

Para iniciar o servidor de desenvolvimento ultrarrápido do Vite, execute o comando abaixo na raiz do projeto:

```bash
npm run dev
```

Após rodar o comando, o terminal exibirá a URL local (geralmente `http://localhost:5173/`). Segure o `Ctrl` (ou `Cmd`) e clique no link para abrir no navegador.

## 🛠️ Outros Scripts Úteis

- `npm run build`: Compila o aplicativo otimizado e minificado para produção (gera os arquivos na pasta `dist`).
- `npm run preview`: Inicia um servidor web local para visualizar exatamente como a versão de produção (`dist`) irá se comportar antes do deploy.
- `npm run lint`: Roda a verificação de regras de código para garantir que tudo está no padrão.

## 🎨 Funcionalidades do Projeto

- **Telas de Autenticação Interativas**: Efeitos visuais (orbs e objetos 3D) que seguem a posição do mouse. Alternância suave entre Login e Cadastro.
- **Navegação em Abas (Tabs)**:
  - **Descobrir**: Vitrine inicial com lançamentos e destaques.
  - **Categorias**: Grade elegante para navegar entre departamentos.
  - **Ofertas**: Área de *Flash Sale* com banner interativo, relógio de contagem regressiva e visualização de descontos e preços riscados.
- **Sistema de Carrinho Lateral**: Drawer (gaveta lateral) super responsiva, adicionando/removendo produtos com atualização do total e emblema contador animado na barra de navegação.
- **Checkout Exclusivo**: Tela de pagamento dividida entre resumo do pedido e formas de pagamento (Cartão interativo e Área de PIX com animação de "laser scanner").
- **Modais Customizados**: Experiência imersiva e sem interrupções bruscas (sem `alert` nativo do navegador), com ícones SVG animados para confirmação de ações de sucesso.

---
Desenvolvido focado em entregar uma UI inovadora e uma UX sem atritos. Mãos à obra! 🚀
