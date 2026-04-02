# Infra Core

Repositório de apoio à estruturação inicial do projeto, com foco em organização, dados e referências operacionais.

Esta documentação deve funcionar como referência viva: curta, versionada em Git e atualizada junto com a evolução do trabalho.

## Visão geral

Esta base documental reúne diretrizes iniciais para organização do projeto, colaboração em Git, estruturação de dados e registro de decisões.

O objetivo desta fase é criar uma base simples e estável o suficiente para orientar o trabalho sem antecipar detalhes que ainda dependem de implementação e uso real.

## Como usar esta documentação

- Use este repositório como referência prática para dúvidas recorrentes de organização.
- Prefira atualizar a documentação junto com mudanças relevantes no repositório, nos dados ou na forma de operação.
- Registre decisões quando elas alterarem padrões, responsabilidades ou fluxos de trabalho.
- Mantenha os textos curtos, objetivos e fáceis de revisar.

## Estrutura

- [Princípios orientadores](#principios-orientadores)
- Colaboração
  - [Workflow com Git](docs/collaboration/git_workflow.md)
  - [Organização do repositório](docs/collaboration/repository_organization.md)
- Dados
  - [Visão geral](docs/data/overview.md)
  - [Formatos](docs/data/formats.md)
  - [Nomenclatura](docs/data/naming.md)
  - [Organização de armazenamento](docs/data/storage_organization.md)
- Infraestrutura
  - [Compartilhamento de dados](docs/infrastructure/data_sharing.md)
  - [Governança da documentação](docs/infrastructure/governance.md)
- [Registro de decisões](#registro-de-decisoes)

## Principios orientadores

Este projeto adota princípios simples para manter o trabalho organizado desde o início, sem excesso de formalismo.

### Reprodutibilidade

Sempre que possível, resultados devem poder ser refeitos a partir de código, parâmetros e dados identificáveis.

### Rastreabilidade

Arquivos, datasets, versões e decisões devem permitir entender de onde vieram, como foram gerados e qual o seu papel no fluxo.

### Simplicidade operacional

O padrão adotado deve ser fácil de explicar, aplicar e revisar. Se uma convenção gerar mais atrito do que clareza, ela deve ser revisitada.

### Padronização suficiente

O projeto precisa de consistência, mas não de rigidez desnecessária. O objetivo é reduzir ambiguidade, não bloquear evolução.

### Evolução incremental

As definições iniciais são guias de trabalho. Elas podem ser refinadas conforme surgirem necessidades reais, desde que as mudanças sejam registradas.

### Separação entre tipos e estágios de dados

Dados brutos, intermediários, processados e produtos finais não devem ser misturados sem critério. A distinção ajuda em validação, auditoria e manutenção.

### Metadados como parte do ativo

Dados sem contexto operacional perdem utilidade. Sempre que necessário, origem, cobertura temporal, resolução, versão e observações devem acompanhar o dataset.

### Documentação útil

A documentação deve refletir o funcionamento do projeto. Texto desatualizado ou genérico demais reduz confiança e deve ser evitado.

## Registro de decisoes

Esta documentação também funciona como referência para registrar decisões arquiteturais e operacionais de forma leve e rastreável.

### Objetivo

Evitar que escolhas relevantes fiquem apenas em conversas, mensagens soltas ou memória da equipe.

### Quando registrar

Registrar uma decisão quando ela:

- definir um padrão de organização;
- escolher entre alternativas com impacto real;
- alterar fluxo operacional;
- influenciar armazenamento, acesso, nomenclatura ou governança.

### Forma do registro

O registro deve ser curto e suficiente para responder:

- qual foi a decisão;
- por que ela foi tomada;
- quais alternativas foram consideradas;
- quais impactos ou desdobramentos são esperados.

### Modelo simples

Cada decisão pode virar um arquivo próprio, por exemplo:

`YYYY-MM-DD_titulo_curto.md`

Estrutura sugerida:

```md
# Título da decisão

## Status
Proposta | Em avaliação | Aprovada | Revisada | Substituída

## Contexto
Resumo objetivo do problema ou necessidade.

## Decisão
Descrição direta da escolha realizada.

## Consequências
Impactos, ganhos, limitações e próximos ajustes esperados.
```

### Diretriz

O registro de decisões não deve virar burocracia. Ele existe para preservar contexto quando a escolha realmente influencia o projeto.

## Critério de atualização

Esta documentação deve ser ajustada quando houver:

- mudança de fluxo de trabalho;
- criação de novo padrão recorrente;
- escolha entre alternativas com impacto operacional;
- necessidade de corrigir ambiguidade ou inconsistência.

Se uma regra ainda estiver em discussão, o texto deve deixar isso explícito em vez de tratar a definição como fechada.
