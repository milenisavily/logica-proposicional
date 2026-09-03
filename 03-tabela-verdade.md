# Tabela-Verdade

## Definição

A tabela-verdade lista todos os possíveis valores lógicos de uma proposição composta, combinando todos os valores possíveis das proposições simples que a compõem.

---

## Número de linhas

Para **n** proposições simples, a tabela terá **2ⁿ** linhas.

| Proposições | Linhas |
|---|---|
| 1 (p) | 2¹ = 2 |
| 2 (p, q) | 2² = 4 |
| 3 (p, q, r) | 2³ = 8 |

---

## Exemplo com 2 proposições

Tabela-verdade de **p ∧ q** e **p ∨ q**:

| p | q | p ∧ q | p ∨ q |
|---|---|---|---|
| V | V | V | V |
| V | F | F | V |
| F | V | F | V |
| F | F | F | F |

---

## Exemplo com negação

Tabela-verdade de **¬p ∨ q**:

| p | q | ¬p | ¬p ∨ q |
|---|---|---|---|
| V | V | F | V |
| V | F | F | F |
| F | V | V | V |
| F | F | V | V |

---

## Ordem de precedência dos conectivos

Assim como na matemática, os conectivos têm prioridade:

| Prioridade | Conectivo |
|---|---|
| 1ª (maior) | ¬ (negação) |
| 2ª | ∧ (conjunção) |
| 3ª | ∨ (disjunção) |
| 4ª | → (implicação) |
| 5ª (menor) | ↔ (bicondicional) |

> Use parênteses para alterar a ordem de avaliação.
