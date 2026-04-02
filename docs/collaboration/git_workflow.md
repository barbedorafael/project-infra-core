# Workflow com Git

Estas diretrizes definem um fluxo colaborativo simples, suficiente para o início do projeto.

## Objetivo

Usar Git como base de colaboração, histórico e revisão, sem introduzir um processo pesado demais.

## Diretrizes gerais

- A branch principal deve refletir o estado de referência do repositório.
- Mudanças devem ser feitas em branches curtas e com escopo claro.
- Commits devem ser pequenos o suficiente para facilitar revisão e entendimento.
- Pull requests devem ser o ponto preferencial de discussão e validação de mudanças.

## Branches

Recomendações iniciais:

- usar nomes curtos e descritivos;
- indicar o tipo de trabalho quando fizer sentido;
- evitar branches longas com múltiplos objetivos.

Exemplos de padrão:

- `feat/nome-curto`
- `fix/nome-curto`
- `docs/nome-curto`
- `data/nome-curto`

## Commits

Recomendações:

- descrever a mudança de forma objetiva;
- manter um único propósito por commit quando possível;
- evitar mensagens vagas como `ajustes` ou `update`.

## Pull requests

Um pull request deve deixar claro:

- o que mudou;
- por que mudou;
- impactos esperados;
- pontos que ainda dependem de validação.

Quando aplicável, incluir referência a decisão, issue ou contexto operacional relacionado.

## Revisão

A revisão deve priorizar:

- clareza da mudança;
- consistência com os padrões do projeto;
- risco de regressão ou ambiguidade;
- impacto sobre dados, nomenclatura e documentação.

Nem toda mudança exige um ritual formal, mas mudanças estruturais devem passar por revisão.

## Versionamento

No início do projeto, o mais importante é manter histórico legível e rastreável. Estratégias mais formais de versionamento podem ser adotadas depois, se houver necessidade real.
