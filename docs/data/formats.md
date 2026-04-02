# Formatos de Dados

A escolha de formatos deve priorizar uso prático, interoperabilidade e custo operacional de manutenção.

## Critérios gerais

Na fase inicial, a seleção de formatos deve considerar:

- compatibilidade com ferramentas de uso provável;
- facilidade de leitura e escrita;
- suporte a metadados;
- eficiência para volume e frequência de acesso;
- clareza para troca entre pessoas e ambientes.

## Vetores

Para dados vetoriais, a recomendação é preferir formatos amplamente suportados e que reduzam ambiguidade de esquema, projeção e atributos.

Quando houver múltiplas opções viáveis, vale priorizar a que simplifique circulação entre análise, validação e processamento.

## Rasters

Para rasters, o formato escolhido deve considerar:

- portabilidade;
- suporte a compressão;
- preservação de referência espacial;
- viabilidade de leitura parcial ou distribuição.

Em cenários de compartilhamento ou armazenamento em nuvem, formatos compatíveis com acesso eficiente tendem a ser preferíveis.

## Tabelas e séries temporais

Para tabelas e séries temporais, a decisão deve equilibrar:

- legibilidade humana quando necessário;
- eficiência de armazenamento;
- preservação de tipos;
- facilidade de integração com pipelines.

Arquivos tabulares simples podem conviver com formatos mais eficientes, desde que o papel de cada um esteja claro.

## Recomendação prática

Não é necessário fechar um catálogo rígido de formatos neste momento. A recomendação é adotar poucas opções por tipo de dado e evitar variação desnecessária dentro do mesmo projeto.

Se um novo formato for introduzido, vale registrar o motivo e o contexto de uso.
