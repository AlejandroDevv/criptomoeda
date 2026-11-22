# 🪙 Criptomoedas

Aplicação web para acompanhar o mercado de criptomoedas, com lista de moedas, busca e página de detalhes. Desenvolvida com React, TypeScript e Vite, consumindo dados da API da CoinCap.

## 📸 Preview

![PReview da aplicação](./public/print-%20preview.png)

## 🌐 Demonstração

🔗 [Acessar aplicação](https://criptomoeda-inky.vercel.app/)

## ✨ Funcionalidades

- 📊 Listagem de criptomoedas com preço, volume, valor de mercado e variação em 24h
- 🔎 Busca de moedas pelo nome
- 📄 Página de detalhes de cada criptomoeda
- ♾️ Carregamento de mais moedas ao rolar a página
- 🔄 Consumo de dados via API REST
- 📱 Interface responsiva

## 🛠️ Tecnologias utilizadas

- React 19
- TypeScript
- Vite
- React Router
- React Icons
- React Compiler
- ESLint
- CSS
- [CoinCap API](https://docs.coincap.io/)

## ⚙️ Como executar o projeto

### Pré-requisitos

- Node.js (versão recente, 20.19 ou superior)
- Git
- Uma chave de API da [CoinCap](https://docs.coincap.io/)

### Instalação

```bash
git clone https://github.com/AlejandroDevv/criptomoeda.git
cd criptomoeda
npm install
```

### Configurando a chave da API

Crie um arquivo `.env` na raiz do projeto, seguindo o modelo do `.env.example`:

```
VITE_COINCAP_API_KEY=sua_chave_aqui
```

### Executando

```bash
npm run dev
```

O projeto abrirá em `http://localhost:5173`.

Para gerar a versão de produção:

```bash
npm run build
npm run preview
```

## 👨‍💻 Autor

**Alejandro Oliveira**

- 💼 [LinkedIn](https://www.linkedin.com/in/alejandro-oliveira/)
- 🐙 [GitHub](https://github.com/AlejandroDevv)