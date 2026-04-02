# Visão Geral de Dados

O projeto deve tratar dados como ativos organizados por tipo, estágio e contexto de uso.

## Tipos de dados

Neste contexto, é esperado lidar com combinações de:

- tabelas;
- séries temporais;
- dados vetoriais;
- rasters;
- metadados e arquivos auxiliares.

Cada tipo pode exigir formatos e práticas específicas, mas a lógica de organização deve permanecer coerente.

## Estágios de dados

Como referência inicial, os dados podem ser classificados em:

- `bruto`: dado recebido ou coletado sem transformação relevante;
- `intermediario`: dado em preparo, limpeza, harmonização ou enriquecimento;
- `processado`: dado estruturado para uso recorrente;
- `produto`: saída orientada a consumo analítico, operacional ou publicação.

Essa separação ajuda a evitar confusão entre origem e derivação.

## Relação entre dados e metadados

Sempre que possível, datasets devem ser acompanhados por informações mínimas como:

- origem;
- período de referência;
- recorte espacial;
- versão;
- observações relevantes de uso.

Nem todo metadado precisa estar em um padrão formal desde o início, mas ele deve existir de forma recuperável.

## Versionamento de dados

Nem todo dado precisa de versionamento explícito no primeiro momento. Ainda assim, o projeto deve buscar algum mecanismo de distinção entre:

- dados substituíveis;
- dados consolidados;
- produtos publicados ou compartilhados.

Quando houver sobrescrita, deve ser possível identificar ao menos quando e por que ela ocorreu.
