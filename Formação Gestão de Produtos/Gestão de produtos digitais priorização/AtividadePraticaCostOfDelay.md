# Atividade Prática: Risco vs Valor

## Objetivo  

Aplicar a técnica de Cost of Delay combinada com o modelo CD3 (Cost of Delay Divided by Duration) para definir prioridades de funcionalidades. Esta abordagem visa equilibrar valor entregue e tempo de desenvolvimento, permitindo decisões baseadas em impacto e eficiência.

---

## Projeto escolhido: Vespucci – App de Exploração Histórica e Geográfica

 Inventei "Vespucci", inspirado no navegador Américo Vespúcio, que oferece uma maneira interativa e divertida de explorar o mundo. A ideia é integrar tecnologia, história, geografia e conhecimento cultural. O aplicativo permite que os usuários naveguem por mapas interativos com camadas históricas, acessem linhas do tempo geográficas, visualizem conteúdo multimídia de áreas específicas e recebam notificações diárias de fatos interessantes com base na localização. Além disso, contém questionários para testar conhecimentos gerais e permite compartilhar descobertas com amigos.

---

## Funcionalidades selecionadas

Considerei que o aplicativo possui somente o MVP (Minimal viable product) assim ele possui 
* Mapa Interativo com Pontos Históricos
* Linha do Tempo Geográfica Básica
* Curiosidade do Dia
* Quiz Básico

---
Assim devemos definir qual(is) épico(s) será(ão) priorizado(s) na próxima sprint.

|Funcionalidade|Descrição|
-|-|
| Modo Offline	                                                | Permite acessar o mapa e conteúdos principais sem conexão com a internet.|
| Exploração Guiada com Narrador Histórico                      |Uma voz narra os eventos históricos enquanto o usuário explora o mapa.	|
|Filtro de Conteúdo por Temática (ex: guerras, cultura, ciência)|Usuário escolhe que tipo de eventos históricos quer visualizar.|
| Chat com Outros Exploradores Próximos	        |Usuários podem conversar com pessoas próximas que estão usando o app.	|
| Relatório Mensal de Locais Visitados		        |Gera um resumo das regiões exploradas e temas vistos no mês.|


---
## Simulação da dinâmica  

A simulação foi feita atribuindo valores estimados de CoD (custo do atraso por semana) e Duração (tempo de entrega em semanas). A prioridade foi definida com base no índice CD3 (CoD / Duração).

| Funcionalidades                                            | CoD | Duração  | CD3     |
|---|---|---|---|
|Modo Offline|400	|1|400
|Exploração Guiada com Narrador Histórico|700|2|350
|Filtro por Temática (guerras, cultura, ciência) |300|1|300
| Chat com Outros Exploradores Próximos  |900|4|225
| Relatório Mensal de Locais Visitados  |500|3|167


## Reflexões e aprendizados  
A dinâmica baseada em Cost of Delay (CoD) e CD3 mostrou-se extremamente eficaz na priorização de entregas com base objetiva no impacto do atraso, combinada com a eficiência no tempo de desenvolvimento.

Vantagens:

Ajuda a quantificar o impacto do tempo
Mostra quanto custa adiar a entrega de uma funcionalidade, tornando mais claro o valor do tempo no processo de desenvolvimento.

Facilita a priorização com foco em valor
Permite comparar tarefas com base em custo x valor, priorizando aquilo que traz maior retorno mais rápido.

Combina valor, urgência e risco
Ao considerar urgência, valor e tempo, o CoD é mais completo do que priorizações puramente qualitativas.

Promove discussões com base em dados
Reduz decisões baseadas em “achismos” e estimula discussões baseadas em impacto real no negócio.

Alinha produto com objetivos estratégicos
Ajuda a tomar decisões mais alinhadas com resultados desejados, como aumento de receita, retenção, satisfação do cliente etc.

Desvantagens

Dificuldade em estimar o valor do atraso
Nem sempre é fácil ou preciso calcular o real impacto financeiro de uma entrega atrasada.

Pode exigir maturidade analítica
Equipes menos experientes podem ter dificuldade em aplicar o CoD de forma consistente e confiável.

Demanda alinhamento entre áreas
Estimar corretamente o CoD pode exigir inputs de produto, negócios, marketing, vendas, etc.

Risco de manipulação de dados
Se os números forem inflados ou subestimados para “forçar” uma priorização, a prática perde seu valor.

Pode ser mal interpretado
Quando mal compreendido, o CoD pode levar à priorização apenas de tarefas urgentes e de curto prazo, negligenciando inovações ou melhorias técnicas.

Reflexão geral:
---

A técnica de CoD + CD3 é poderosa para maximizar valor por unidade de tempo, sendo especialmente útil em contextos ágeis onde o tempo é restrito e os recursos limitados. Aprendi que priorizar funcionalidades com base apenas em valor pode ser arriscado.

---

*Esta atividade visa consolidar o entendimento sobre priorização com foco em impacto financeiro e agilidade na entrega, contribuindo para decisões mais estratégicas na gestão de produtos digitais.*
