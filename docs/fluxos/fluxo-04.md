# Fluxo Operacional 04

# Parametrizações da Cooperativa

## Objetivo

Demonstrar como as parametrizações influenciam a contratação e a cobrança do seguro.

```mermaid
flowchart TD

A[Operação de Crédito]

--> B{Seguro Obrigatório?}

B -->|Sim| C[Contratação Automática]

B -->|Não| D[Oferta ao Cooperado]

D --> E{Aceitou?}

E -->|Sim| F[Contratação]

E -->|Não| G[Operação sem Seguro]

C --> H[Definição de Cobrança]

F --> H

H --> I{Pagamento}

I -->|À Vista| J[Prêmio Integral]

I -->|Parcelado| K[Parcelas Mensais]

J --> L[Faturamento]

K --> L[Faturamento]

L --> M[Conciliação]
```

---

# Pontos de Controle

## Contratação

* Seguro obrigatório ou opcional.
* Registro da adesão.

## Cobrança

* À vista.
* Parcelado.

## Faturamento

* Conferência das parcelas.

## Conciliação

* Validação dos valores arrecadados.

---

# Indicadores Recomendados

* Percentual protegido.
* Taxa de adesão.
* Percentual bonificado.
* Cobranças inconsistentes.
* Índice de conciliação.
