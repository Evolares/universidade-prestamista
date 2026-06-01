# Fluxo Operacional 05

# Contratação e Limite Centralizado

## Objetivo

Demonstrar o fluxo de contratação e a validação da exposição do segurado.

```mermaid
flowchart TD

A[Operação de Crédito]

--> B[Oferta do Seguro]

B --> C[Validação de Elegibilidade]

C --> D[Consulta de Operações Existentes]

D --> E[Cálculo de Acúmulo]

E --> F{Limite Centralizado}

F -->|Dentro do Limite| G[Contratação]

F -->|Acima do Limite| H[Análise Complementar]

G --> I[Formalização]

H --> I

I --> J[Emissão]

J --> K[Cobrança]
```

---

# Pontos de Controle

## Elegibilidade

* Produto elegível.
* Perfil do cooperado.

## Exposição

* Operações existentes.
* Capital acumulado.

## Limite

* Verificação do limite centralizado.

## Formalização

* Documentação correta.

---

# Indicadores Recomendados

* Operações contratadas.
* Exposição média por cooperado.
* Limites excedidos.
* Operações pendentes de análise.
* Percentual de contratação.
