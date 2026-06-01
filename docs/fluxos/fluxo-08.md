# Fluxo Operacional 08

# Consistência das Parcelas

## Objetivo

Demonstrar a validação operacional das parcelas antes da conciliação.

```mermaid
flowchart TD

A[Parcela Gerada]

--> B[Cobrança]

B --> C[Arrecadação]

C --> D[Faturamento]

D --> E{Consistente?}

E -->|Sim| F[Base Confiável]

E -->|Não| G[Parcela Irregular]

G --> H[Análise]

H --> I[Correção]

I --> D

F --> J[Conciliação]
```

---

# Pontos de Controle

## Cobrança

* Parcela gerada corretamente.

## Arrecadação

* Valor recebido.

## Faturamento

* Registro financeiro correto.

## Consistência

* Validação cruzada das informações.

---

# Indicadores Recomendados

* Parcelas irregulares.
* Valor irregular.
* Tempo de regularização.
* Percentual consistente.
* Tendência de inconsistências.
