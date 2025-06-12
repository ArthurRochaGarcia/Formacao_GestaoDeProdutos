# Atividade Prática: Priorização por Atributos

## Objetivo  
refletir sobre os critérios utilizados para priorizar funcionalidades em um produto digital, partindo dos três atributos estudados no curso:

- Lucro

- Complexidade de desenvolvimento

- Agrado ao usuário

A ideia central é analisar se esses atributos refletem a sua realidade profissional ao priorizar funcionalidades, e se há outros atributos que você considera importantes, podendo, inclusive, propor novos critérios que julgar mais relevantes para sua realidade de trabalho ou de projeto.

---

## Atributos estudados

|Atributo|Comentário|
|---|---|
|Lucro| Qual será o lucro? (PO)|
|Complexidade de desenvolvimento | O quão complexo é fazer essa funcionalidade? (DEV)|
|Agrado ao usuário | Quão agradável será para o usuário? (User)|

Faz bastante sentido na prática e são pilares fundamentais na priorização de funcionalidades em produtos digitais. No entanto, nem sempre são suficientes sozinhos para capturar toda a realidade de um projeto.
---

## Atributos propostos

|Atributo|Comentário|
|---|---|
|Alinhamento estratégico| O quanto esta funcionalidade contribui com os objetivos estratégicos do produto ou da empresa? (PO)|
|Urgência | Qual o nível de urgência |

Esses atributos ajudam a trazer uma visão mais realista do impacto e da sustentabilidade de cada decisão tomada.

---


## Projeto escolhido: Vespucci – App de Exploração Histórica e Geográfica

 Inventei "Vespucci", inspirado no navegador Américo Vespúcio, que oferece uma maneira interativa e divertida de explorar o mundo. A ideia é integrar tecnologia, história, geografia e conhecimento cultural. O aplicativo permite que os usuários naveguem por mapas interativos com camadas históricas, acessem linhas do tempo geográficas, visualizem conteúdo multimídia de áreas específicas e recebam notificações diárias de fatos interessantes com base na localização. Além disso, contém questionários para testar conhecimentos gerais e permite compartilhar descobertas com amigos.

---

## Funcionalidades selecionadas  
Considerei que o aplicativo possui somente o MVP (Minimum viable product) assim ele possui 
* Mapa Interativo com Pontos Históricos
* Linha do Tempo Geográfica Básica
* Curiosidade do Dia
* Quiz Básico
---
Assim devemos definir qual(is) épico(s) será(ão) priorizado(s) na próxima sprint.

|Funcionalidade|Descrição|
-|-|
| Curiosidades baseadas na posição real   | Oferecer curiosidades históricas, culturais e geográficas com base na localização do usuário|
| Realidade aumentada                     |Tornar a exploração de locais históricos mais envolvente no mundo real.|
| Sistema de gamificação ou conquistas    |Aumentar o engajamento com metas e recompensas.|
| Mapa do Conhecimento Comunitário        |Engajar os usuários na construção do conteúdo.|

---

## Priorização com atributos originais

| Funcionalidade          | Lucro (1-5) | Complexidade (1-5) | Agrado (1-5) | Média ponderada |
-|-|-|-|-|
| Curiosidades baseadas na posição real   | 3 | 2 | 5 | 2.0 |
| Realidade aumentada                     | 4 | 5 | 5 | 1.3 |
| Sistema de gamificação ou conquistas    | 5 | 4 | 4 | 1.6 |
| Mapa do Conhecimento Comunitário        | 3 | 4 | 4 | 1.0 |

Hipótese: pesos iguais para cada atributo.

Pontuação: ((Lucro + Agrado - Complexidade) / Total de pesos)

Resultado: priorizar Curiosidade e Gamificação ou conquista.

---

## Priorização com novos atributos.

| Funcionalidade          | Lucro (1-5) | Complexidade (1-5) | Agrado (1-5) | Urgência (1-5) | Alinhamento (1-5) | Média ponderada |
-|-|-|-|-|-|-|
| Curiosidades baseadas na posição real   | 3 | 2 | 5 | 4 | 5 | 3.8 |
| Realidade aumentada                     | 4 | 5 | 5 | 2 | 3 | 2.2 |
| Sistema de gamificação ou conquistas    | 5 | 4 | 4 | 3 | 4 | 3.0   |
| Mapa do Conhecimento Comunitário        | 3 | 4 | 4 | 4 | 5 | 3.2 |

Hipótese: pesos maior por Urgência.

Pontuação: ((Lucro + Agrado - Complexidade + Alinhamento + (Urgência * 2)) / Total de pesos)

Resultado: priorizar Curiosidade e Mapa do Conhecimento Comunitário.

#### Ao expandir os critérios de avaliação, percebi que:

* O atributo urgência trouxe mais clareza sobre quando uma funcionalidade deve ser executada, mesmo que não seja a mais atrativa financeiramente.

* O alinhamento estratégico reforça decisões coerentes com os objetivos de médio e longo prazo do produto.

---

## Reflexões  
Após simular a atividade, percebi alguns pontos importantes sobre a dinâmica Priorização por Atributos.

### Vantagens:

* #### Engajamento analítico: A dinâmica exige que os participantes analisem múltiplos critérios, o que enriquece a discussão e ajuda a considerar diferentes perspectivas (como valor, esforço, risco e impacto).

* #### Visão comparativa: Ao atribuir pesos ou notas aos atributos, é possível visualizar de forma mais clara quais iniciativas oferecem maior retorno sob diferentes dimensões.

* #### Decisões mais equilibradas: Como a decisão não depende de um único critério (como valor de negócio, por exemplo), evita-se o viés de priorizar sempre o que parece mais urgente ou chamativo.

* #### Transparência: A estrutura baseada em atributos torna os critérios de decisão mais objetivos e visíveis para todos os envolvidos.

### Desvantagens
* #### Complexidade inicial: A definição dos atributos e seus pesos pode ser confusa ou subjetiva para equipes com menos maturidade em priorização.

* #### Tempo de preparação: Demanda uma etapa inicial de alinhamento sobre os critérios e a forma de avaliação, o que pode alongar o processo.

* #### Risco de enviesamento: Mesmo com múltiplos critérios, decisões podem ser enviesadas se os atributos não forem bem escolhidos ou calibrados.

* #### Dificuldade em consenso: Pode haver divergência entre os participantes na hora de pontuar os atributos, especialmente quando os objetivos do negócio não estão totalmente alinhados.

Reflexão geral:
---
A dinâmica de Priorização por Atributos oferece uma abordagem estruturada e colaborativa para tomada de decisão, ideal para ambientes onde múltiplos fatores devem ser considerados. Apesar de exigir mais preparação e alinhamento prévio, ela promove uma priorização mais racional e transparente. É uma ferramenta poderosa quando bem conduzida e adaptada à realidade da equipe.

---

*Esta atividade visa fortalecer a prática da priorização baseada em múltiplos critérios e estimular o pensamento crítico sobre o valor de cada entrega.*
