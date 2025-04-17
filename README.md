# MCP Products Info Server

Este é um servidor MCP (Model Context Protocol) que fornece informações sobre produtos da Caffeine Army, especialmente o SuperCoffee.

## Descrição

O servidor utiliza a API do Shopify para buscar informações detalhadas sobre produtos, incluindo:
- Nome do produto
- Descrição
- Preço
- Fornecedor
- Outras informações relevantes

## Requisitos

- Node.js
- NPM ou Yarn
- Variáveis de ambiente configuradas

## Configuração

1. Clone o repositório
2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente criando um arquivo `.env` na raiz do projeto:
```env
SHOPIFY_SHOP=seu-shop.myshopify.com
SHOPIFY_STOREFRONT_TOKEN=seu_token
```

## Uso

Para iniciar o servidor:

```bash
npm start
```

## Ferramentas Disponíveis

### get-products

Retorna informações detalhadas sobre o SuperCoffee, incluindo:
- Título do produto
- Descrição completa
- Preço atual
- Informações do fornecedor

## Estrutura do Projeto

```
├── src/
│   ├── index.ts          # Ponto de entrada do servidor
│   └── @types/          # Definições de tipos TypeScript
├── .env                 # Variáveis de ambiente (não versionado)
├── package.json        # Dependências e scripts
└── README.md          # Este arquivo
```

## Tecnologias Utilizadas

- TypeScript
- Node.js
- MCP SDK
- Shopify API
- Axios

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes. 
