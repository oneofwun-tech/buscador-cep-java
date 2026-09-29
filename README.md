# Buscador de CEP

Projeto desenvolvido durante meus estudos de Java na Alura.

A aplicação recebe um CEP informado pelo usuário, faz uma consulta em uma API de CEP e mostra os dados do endereço encontrado. Depois, os dados são salvos em um arquivo JSON.

## O que pratiquei

- Consumo de API
- Requisições HTTP
- Conversão de JSON
- Uso da biblioteca Gson
- Criação e organização de classes
- Tratamento de exceções
- Leitura de dados pelo console

## Estrutura

O projeto está dividido em algumas classes:

- `Principal` – inicia a aplicação e recebe o CEP informado.
- `ConsultaCep` – realiza a consulta na API.
- `Endereco` – representa os dados do endereço.
- `GeradorDeArquivo` – salva o resultado em JSON.

## Exemplo

Ao executar o programa, o CEP é informado pelo terminal:

```text
Digite o CEP para consulta:
22753-790
