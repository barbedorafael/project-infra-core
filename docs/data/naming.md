# Nomenclatura

Convenções de nome ajudam a localizar, interpretar e automatizar o uso de dados e artefatos do projeto.

## Objetivo

Manter nomes previsíveis, legíveis e consistentes ao longo do tempo.

## Diretrizes gerais

- usar letras minúsculas;
- preferir caracteres simples e estáveis;
- evitar espaços e acentuação em nomes de arquivos e diretórios;
- usar separadores consistentes, preferencialmente `_` ou `-`;
- manter siglas e abreviações sob controle;
- evitar nomes genéricos como `final`, `novo`, `teste2`.

## Componentes úteis em nomes

Conforme o caso, um nome pode incluir:

- dataset ou tema;
- área ou recorte espacial;
- período ou data de referência;
- resolução;
- fonte;
- estágio;
- versão.

Nem todo arquivo precisa conter todos os componentes. O importante é que o padrão adotado seja suficiente para reduzir ambiguidade.

## Datas e tempo

Sempre que possível, usar formatos ordenáveis, como:

- `YYYY-MM-DD`
- `YYYY-MM`
- `YYYY`

Para timestamps mais detalhados, manter um padrão único no projeto.

## Versões

Se houver versionamento explícito no nome, usar convenções simples e crescentes, como:

- `v1`
- `v2`
- `v2026-04`

O critério deve ser consistente com o ciclo de atualização do dado ou produto.

## Variáveis e identificadores

Em tabelas, scripts e metadados:

- nomes devem ser claros e estáveis;
- abreviações devem ser poucas e conhecidas;
- o mesmo conceito não deve aparecer com múltiplos nomes sem necessidade.

## Regra prática

Antes de criar um novo padrão de nome, vale verificar se ele já pode ser representado por convenção existente. Consistência costuma ser mais valiosa do que precisão excessiva no nome.
