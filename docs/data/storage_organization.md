# Organização de Armazenamento

Os dados devem ser organizados de forma navegável, estável e compatível com uso local ou em object storage.

## Objetivo

Definir uma lógica de organização que funcione bem tanto em diretórios quanto em prefixos de armazenamento.

## Princípios

- a estrutura deve favorecer localização rápida;
- o caminho deve refletir contexto suficiente do dado;
- a lógica deve ser estável ao longo do tempo;
- a profundidade da árvore deve ser controlada.

## Eixos de organização

Dependendo do caso, os principais eixos tendem a ser:

- dataset ou domínio;
- estágio do dado;
- versão;
- recorte temporal;
- recorte espacial;
- tipo de produto.

Não é necessário usar todos os eixos em todos os casos. O importante é que a estrutura seja previsível.

## Exemplo conceitual

Uma organização possível pode seguir lógica semelhante a:

`<dataset>/<estagio>/<versao>/<periodo>/<area>/<artefato>`

Esse modelo deve ser ajustado conforme o tipo de dado e a frequência de atualização.

## Object storage

Em object storage, a organização é feita por prefixos, não por pastas reais. Por isso:

- o caminho precisa funcionar bem como chave de navegação;
- prefixos devem evitar ambiguidade;
- mudanças estruturais frequentes tendem a gerar custo operacional.

## Recomendações iniciais

- separar bruto, intermediário, processado e produto;
- evitar misturar dados temporários com dados de referência;
- manter convenção compatível com automação futura;
- documentar exceções quando a estrutura padrão não for suficiente.
