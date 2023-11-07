# Sistema de Vendas - Testes Unitários

Este projeto contém testes unitários para as classes `FreteNegocio` e `VendasNegocio` do sistema de vendas.

## FreteNegocioTest

Esta classe contém testes para o cálculo do frete com base na distância em quilômetros.

### Testes Incluídos

- `DeveCalcularFretePara5KmComSucesso`: Verifica se o frete é calculado corretamente para distâncias até 5 km.
- `DeveCalcularFreteEntre5kmE15kmComSucesso`: Verifica se o frete é calculado corretamente para distâncias entre 5 km e 15 km.
- `DeveCalcularFreteSuperior15kmComSucesso`: Verifica se o frete é calculado corretamente para distâncias superiores a 15 km.

## VendasNegocioTest

Esta classe contém testes para o cálculo da média mensal de vendas.

### Testes Incluídos

- `DeveCalcularMediaMensalComSucesso`: Verifica se a média mensal de vendas é calculada corretamente.

## Pré-requisitos

- Ambiente de desenvolvimento compatível com C# e Xunit.

## Como Executar os Testes

1. Abra o projeto em seu ambiente de desenvolvimento.
2. Abra o explorador de testes ou terminal e execute os testes.

## Contribuindo

Se você gostaria de contribuir para o desenvolvimento deste projeto, fique à vontade para abrir um pull request.

## Licença

Este projeto está sob a [licença MIT](LICENSE).
