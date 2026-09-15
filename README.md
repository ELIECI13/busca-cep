# BuscaCEP

Aplicação front-end para consultar endereços brasileiros a partir de um CEP.

**Demo online:** https://elieci13.github.io/busca-cep/

Criei este projeto para praticar consumo de API REST com JavaScript sem utilizar framework. A consulta é feita no ViaCEP e a interface trata CEP inválido, endereço não encontrado e falhas de conexão.

## Recursos

- consulta de CEP usando `fetch` e `async/await`;
- formatação automática do CEP;
- validação antes da requisição;
- tratamento de erros da API;
- exibição de logradouro, bairro, cidade, estado, DDD e código IBGE;
- histórico das últimas consultas usando LocalStorage;
- botão para copiar o endereço;
- tema claro/escuro salvo no navegador;
- layout responsivo.

## Tecnologias

HTML5, CSS3 e JavaScript. Os dados de endereço são fornecidos pelo webservice ViaCEP.

## Como executar

A forma mais rápida é acessar a demo online. Também é possível baixar os arquivos e abrir `index.html` no navegador. Não há dependências para instalar.

## O que pratiquei

Neste projeto trabalhei com requisições assíncronas, `fetch`, JSON, `try/catch`, manipulação do DOM, eventos, validação de formulário e armazenamento local.

## Observação

O histórico fica apenas no navegador do usuário. Nenhum endereço pesquisado é enviado para um banco de dados deste projeto.
