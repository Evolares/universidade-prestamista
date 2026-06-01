# Fluxo Operacional 06

# Formalização, DPS e Resseguro

## Objetivo

Demonstrar o fluxo completo de formalização e análise da DPS.

```mermaid
flowchart TD

A[Contratação]

--> B[Formalização]

B --> C{Necessita DPS?}

C -->|Não| D[Aceitação Automática]

C -->|Sim| E[Preenchimento da DPS]

E --> F[Envio para Análise]

F --> G{Resultado}

G -->|Aceita| H[Cobertura Liberada]

G -->|Pendente| I[Solicitação Complementar]

G -->|Recusada| J[Cobertura Negada]

H --> K[Emissão]

I --> F

K --> L[Operação Ativa]

L --> M{Capital Elevado?}

M -->|Não| N[Risco Retido]

M -->|Sim| O[Resseguro]

O --> P[Compartilhamento do Risco]
```

---

# Pontos de Controle

## Formalização

* Assinatura válida.
* Documentação completa.

## DPS

* Prazo de análise.
* Pendências.

## Resseguro

* Capitais elevados.
* Exposição concentrada.

---

# Indicadores Recomendados

* DPS pendentes.
* Tempo médio de análise.
* Propostas aceitas.
* Propostas recusadas.
* Operações com resseguro.
