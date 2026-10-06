# Teste de mesa — Grupo 06 · Base Tabuleiro

> **MODELO DE REFERÊNCIA.** Os valores de **entrada** já estão preenchidos com o cartão do grupo.
> Tudo o que está como `____` é para **vocês calcularem na mão**, sem olhar a saída do programa. Só depois comparem (seção final).
> Copie para `docs/`. Se precisarem de mais linhas, acrescentem.

**Código de autenticidade:** `SA03S-G06-964D` · **Responsável pelo teste de mesa:** _maria carolina santos da silva_____________________

## Constantes do cartão (usadas em todas as contas)

| Constante | Valor |
|---|---|
| Pagamento por entrega | R$ 5,00 |
| Meta semanal | 35 entregas |
| Meta mínima | 23 entregas |
| Bônus de meta | R$ 80,00 |
| Desconto por cancelamento | R$ 8,00 |

Entregadores do teste, segundo o cartão: **702** e **704**.

---

## Teste 1 — entregador de código 702 (Jaqueline)

**Dados de entrada (do cartão):**

| Código | Nome | Cancelamentos | Posição `i` no vetor/matriz |
|---|---|---|---|
| 702 | Jaqueline | 2 | __2__ |

### Parte A — acumulando as entregas da semana (laço dos dias)

| Passo | `dia` (índice) | Dia | `entregas[i][dia]` | `totalEntregas` antes | `totalEntregas` depois |
|:-:|:-:|---|:-:|:-:|:-:|
| início | — | — | — | — | ____ |
| 1 | __0__ | Segunda | 5 | __0__ | __5__ |
| 2 | __1__ | Terça | 9 | __5__ | __14__ |
| 3 | __2__ | Quarta | 9 | __14__ | __23__ |
| 4 | __3__ | Quinta | 12 | __23__ | __35__ |
| 5 | __4__ | Sexta | 6 | __35__ | __41__ |
| fim do laço | — | — | — | — | `totalEntregas` final = __41__ |

### Parte B — cálculos do repasse

Escreva a conta **com os números do cartão** e o resultado.

| Variável | Conta (com os valores) | Resultado |
|---|---|:-:|
| `ganho` | ______________________ | ____ |
| `bonus` | ______________________ | ____ |
| `desconto` | ______________________ | ____ |
| `repasse` | ______________________ | ____ |

### Parte C — decisão da situação (na ordem em que o programa testa)

| Ordem | Condição testada (com os valores) | Verdadeira ou falsa? | Parou aqui? |
|:-:|---|:-:|:-:|
| 1ª | __41<=31__ | __verdadeira__ | __sim__ |
| 2ª | _______2 == 0_______ | __falsa__ | __sim__ |
| 3ª | (se chegou aqui) ______________________ | ____ | ____ |

**`situacao` final:** ____________

### Resumo do teste 1

| Total de entregas | Ganho | Bônus | Desconto | Repasse | Situação |
|:-:|:-:|:-:|:-:|:-:|:-:|
| __41__ | __328__ | ____ | ____ | ____ | ____ |

---

## Teste 2 — entregador de código 704 (Bruna)

**Dados de entrada (do cartão):**

| Código | Nome | Cancelamentos | Posição `i` no vetor/matriz |
|---|---|---|---|
| 704 | Bruna | 0 | ____ |

### Parte A — acumulando as entregas da semana (laço dos dias)

| Passo | `dia` (índice) | Dia | `entregas[i][dia]` | `totalEntregas` antes | `totalEntregas` depois |
|:-:|:-:|---|:-:|:-:|:-:|
| início | — | — | — | — | ____ |
| 1 | __0__ | Segunda | 3 | __0__ | __4__ |
| 2 | __1__ | Terça | 1 | __4__ | __5__ |
| 3 | __2__ | Quarta | 1 | __5__ | __9__ |
| 4 | __3__ | Quinta | 4 | __9__ | __17__ |
| 5 | __4__ | Sexta | 8 | __17__ | __36__ |
| fim do laço | — | — | — | — | `totalEntregas` final = ____ |

### Parte B — cálculos do repasse

Escreva a conta **com os números do cartão** e o resultado.

| Variável | Conta (com os valores) | Resultado |
|---|---|:-:|
| `ganho` | ______________________ | ____ |
| `bonus` | ______________________ | ____ |
| `desconto` | ______________________ | ____ |
| `repasse` | ______________________ | ____ |

### Parte C — decisão da situação (na ordem em que o programa testa)

| Ordem | Condição testada (com os valores) | Verdadeira ou falsa? | Parou aqui? |
|:-:|---|:-:|:-:|
| 1ª | ______________________ | ____ | ____ |
| 2ª | ______________________ | ____ | ____ |
| 3ª | (se chegou aqui) ______________________ | ____ | ____ |

**`situacao` final:** ____________

### Resumo do teste 2

| Total de entregas | Ganho | Bônus | Desconto | Repasse | Situação |
|:-:|:-:|:-:|:-:|:-:|:-:|
| ____ | ____ | ____ | ____ | ____ | ____ |

---

## Comparação com a execução do programa

Rodem o programa no Portugol Web Studio, copiem a linha de cada um dos dois entregadores e comparem com o resumo acima.

| Entregador | Campo | Na mão | No programa | Bateu? |
|---|---|:-:|:-:|:-:|
| 702 | Total de entregas | ____ | ____ | ____ |
| 702 | Ganho | ____ | ____ | ____ |
| 702 | Bônus | ____ | ____ | ____ |
| 702 | Desconto | ____ | ____ | ____ |
| 702 | Repasse | ____ | ____ | ____ |
| 702 | Situação | ____ | ____ | ____ |
| 704 | Total de entregas | ____ | ____ | ____ |
| 704 | Ganho | ____ | ____ | ____ |
| 704 | Bônus | ____ | ____ | ____ |
| 704 | Desconto | ____ | ____ | ____ |
| 704 | Repasse | ____ | ____ | ____ |
| 704 | Situação | ____ | ____ | ____ |

**Se algo não bateu:** o que o grupo investigou e corrigiu? ______________________________

