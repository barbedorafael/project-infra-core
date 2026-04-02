# Compartilhamento de Dados

O compartilhamento de dados deve equilibrar acesso, custo, manutenção e controle operacional.

## Objetivo

Orientar a avaliação de opções de compartilhamento sem fechar uma arquitetura definitiva cedo demais.

## Opções comuns

### Servidor local ou rede interna

Pode ser adequado quando:

- a equipe trabalha em ambiente controlado;
- o volume de dados é relevante;
- a operação depende de acesso interno recorrente.

Pontos de atenção:

- dependência de infraestrutura local;
- acesso remoto mais limitado;
- necessidade de operação e backup bem definidos.

### Object storage

Pode ser adequado quando:

- há necessidade de acesso distribuído;
- o volume tende a crescer;
- o projeto pode se beneficiar de escalabilidade e padronização de acesso.

Pontos de atenção:

- custos de armazenamento e transferência;
- necessidade de controle de permissões;
- desenho consistente de prefixos e políticas de acesso.

### Solução híbrida

Pode ser adequada quando:

- parte dos dados precisa ficar próxima da operação local;
- parte dos dados precisa de compartilhamento mais amplo;
- o projeto quer reduzir migração abrupta no início.

Pontos de atenção:

- risco de duplicidade e divergência;
- necessidade de regras claras sobre fonte de verdade;
- maior cuidado com sincronização e governança.

## Critérios de avaliação

Na comparação entre opções, considerar:

- custo total;
- facilidade de acesso;
- simplicidade de operação;
- esforço de manutenção;
- segurança e controle de acesso;
- escalabilidade;
- aderência ao uso real do projeto.

## Diretriz inicial

No começo do projeto, a melhor opção costuma ser a que reduz atrito sem comprometer rastreabilidade. A decisão deve ser revista quando o volume, a equipe ou o padrão de consumo mudarem de forma relevante.
