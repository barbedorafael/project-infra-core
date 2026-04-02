# Organização do Repositório

O repositório deve separar com clareza código, documentação, configurações e referências a dados.

## Objetivo

Facilitar navegação, manutenção e colaboração sem depender de conhecimento implícito.

## Estrutura esperada

Como diretriz inicial, o repositório tende a incluir áreas como:

- código de processamento ou apoio operacional;
- documentação em `docs/`;
- scripts utilitários;
- arquivos de configuração;
- referências a dados e instruções de acesso;
- artefatos leves necessários ao desenvolvimento.

## Diretrizes

- Dados grandes não devem ser versionados no Git por padrão.
- O repositório pode conter amostras pequenas, metadados, esquemas ou manifestos quando isso facilitar entendimento e testes.
- Scripts de uso recorrente devem ficar em local previsível e com nome claro.
- Configurações devem ser separadas de código executável sempre que fizer sentido.
- A documentação deve apontar para dados externos quando eles não estiverem no repositório.

## O que evitar

- misturar código com artefatos gerados sem distinção;
- armazenar múltiplas cópias do mesmo dado por conveniência;
- depender apenas de conhecimento oral para localizar insumos e saídas;
- criar profundidade excessiva de diretórios sem necessidade.

## Ajustes futuros

Esta organização pode evoluir conforme a stack e os fluxos se consolidem. Mudanças estruturais relevantes devem ser refletidas na documentação.
