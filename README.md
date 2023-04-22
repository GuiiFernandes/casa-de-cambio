# Casa de Câmbio

O projeto da casa de câmbio é uma aplicação que busca a conversão da taxa de uma moeda para diversas outras.
O protótipo da aplicação está [nesse link](https://www.figma.com/file/H3gBEiF0F94VESCGx9DD17/Casa-de-C%C3%A2mbio?node-id=0%3A1).

## Requisitos

### 1. Ambiente do Projeto
1. Criar um repositório do zero ou fazer um fork desse repositório (fique à vontade para fazer PRs quando terminar o desenvolvimento).
2. Iniciar projeto com NPM.
3. Estruturar o projeto para usar ESModules (usar `type` como `module` no `package.json` e nas tags `script`).
4. Instalar Vite como Dev Tool e `npm run dev`.

### 2. Estrutura da Aplicação
1. Estruturar o HTML de acordo com [protótipo](https://www.figma.com/file/H3gBEiF0F94VESCGx9DD17/Casa-de-C%C3%A2mbio?node-id=0%3A1).
2. Criar tags semânticas no HTML.

### 3. Interação com API
1. O endpoint da API que deverá ser usada é `https://api.exchangerate.host/latest?base=${moeda}`. 
2. A moeda a ser pesquisada deverá ser passada como o parâmetro `moeda` do _endpoint_.
3. Todas as moedas deverão ser listadas na tela.
> [Link da documentação da API](https://exchangerate.host/#/docs) caso necessário

### 4. Tratamento de Erro
1. Você deve usar o [Sweet Alert 2](https://sweetalert2.github.io/) para as mensagens de Erro.
2. Um erro deverá aparecer quando nenhuma moeda é passada.
3. Um erro deverá aparecer quando uma moeda inexistente é passada.

### 5. Estilização (Bônus)
1. Implementação do [protótipo de alta fidelidade](https://www.figma.com/file/H3gBEiF0F94VESCGx9DD17/Casa-de-C%C3%A2mbio?node-id=0%3A1)
