# Equivalência Lógica (≡)

## Definição

Duas proposições são **logicamente equivalentes** quando possuem a **mesma tabela-verdade** — ou seja, têm o mesmo valor lógico para todas as combinações possíveis.

Notação: **p ≡ q**

---

## Como verificar equivalência

Basta construir a tabela-verdade das duas proposições e comparar as colunas finais. Se forem idênticas, as proposições são equivalentes.

---

## Equivalências fundamentais

### Lei da Dupla Negação
> **¬(¬p) ≡ p**

| p | ¬p | ¬(¬p) |
|---|---|---|
| V | F | V |
| F | V | F |

---

### Leis de De Morgan

> **¬(p ∧ q) ≡ ¬p ∨ ¬q**

| p | q | ¬(p ∧ q) | ¬p ∨ ¬q |
|---|---|---|---|
| V | V | F | F |
| V | F | V | V |
| F | V | V | V |
| F | F | V | V |

> **¬(p ∨ q) ≡ ¬p ∧ ¬q**

| p | q | ¬(p ∨ q) | ¬p ∧ ¬q |
|---|---|---|---|
| V | V | F | F |
| V | F | F | F |
| F | V | F | F |
| F | F | V | V |

---

### Implicação como Disjunção
> **p → q ≡ ¬p ∨ q**

| p | q | p → q | ¬p ∨ q |
|---|---|---|---|
| V | V | V | V |
| V | F | F | F |
| F | V | V | V |
| F | F | V | V |

---

### Contrapositiva
> **p → q ≡ ¬q → ¬p**

---

## Resumo das principais equivalências

| Nome | Equivalência |
|---|---|
| Dupla negação | ¬(¬p) ≡ p |
| De Morgan 1 | ¬(p ∧ q) ≡ ¬p ∨ ¬q |
| De Morgan 2 | ¬(p ∨ q) ≡ ¬p ∧ ¬q |
| Implicação | p → q ≡ ¬p ∨ q |
| Contrapositiva | p → q ≡ ¬q → ¬p |
| Bicondicional | p ↔ q ≡ (p → q) ∧ (q → p) |
