# Sprint 01

## 🎯 Objetivo 
> Orientar a criação de um painel interativo de apoio à tomada de decisões em políticas públicas de segurança e mobilidade no trânsito. A proposta é integrar dados da frota nacional, população, sinistros e mortalidade para possibilitar análises comparativas entre estados, faixas etárias, gêneros e períodos. Com isso, busca-se identificar tendências, avaliar riscos regionais, medir a efetividade de políticas públicas e direcionar ações preventivas voltadas à redução de acidentes e mortes no trânsito.  

- Qual problema resolve?
problema que será resolvido é a falta de integração e visualização acessível dos dados sobre frota, população, sinistros e mortalidade no trânsito, que hoje estão dispersos em diferentes bases e dificultam análises estratégicas.

- Qual hipótese será validada?
A hipótese a ser validada é que a integração e análise conjunta dos dados de frota, população, sinistros e mortalidade permite identificar relações diretas entre o crescimento da frota, o perfil demográfico e o aumento (ou redução) dos acidentes e mortes no trânsito.

- Qual valor será entregue ao usuário final?  
Com o painel interativo proposto, será possível concentrar essas informações em uma única plataforma, permitindo que gestores públicos identifiquem padrões, regiões críticas e tendências de crescimento da frota e dos acidentes, além de avaliar o impacto das políticas de segurança viária de forma mais ágil e baseada em evidências.

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 📝 Solução
> Nesta etapa será desenvolvido e entregue um painel interativo de visualização de dados, que reunirá informações sobre frota de veículos, população, sinistros e mortalidade no trânsito. O painel permitirá filtrar e comparar dados por estado, ano, tipo de veículo, faixa etária e gênero, apresentando gráficos e mapas dinâmicos para análise de tendências e indicadores, como mortalidade por 100 mil habitantes e sinistros por 10 mil veículos.
O resultado desta entrega será uma ferramenta consolidada de apoio à decisão, capaz de auxiliar gestores públicos na identificação de padrões, regiões críticas e avaliação do impacto de políticas de segurança viária.  

- Funcionalidades principais incluídas:
1.Visualização interativa da frota nacional — gráficos e séries temporais que mostram a quantidade de veículos por tipo, ano e estado, com filtros dinâmicos.
2.Análise demográfica da população — segmentação por estado, faixa etária e gênero, permitindo cruzamento com dados de frota e acidentes.
3.Painel de mortalidade (DATASUS) — acompanhamento da evolução temporal de óbitos no trânsito, com comparativos por gênero, idade e localização.
4.Indicadores de mortalidade por 100 mil habitantes — gráficos e mapas comparativos entre estados e séries históricas para identificação de regiões críticas.
5.Indicadores de sinistros por 10 mil veículos — visualização em mapa interativo e gráficos de evolução anual e regional.
6.Filtros e comparativos integrados — possibilidade de selecionar estados, anos e variáveis para análises personalizadas e cruzamentos de dados.
7.Exportação e compartilhamento — geração de relatórios e gráficos para uso em apresentações e planejamento de políticas públicas.

- Limitações conhecidas:
 Não foi possivel criar filtro de genêro e faixa etária, pois os arquivos csv não se interligam.

- Escopo reduzido:
1.Visualização básica da frota nacional — gráfico de evolução anual da quantidade total de veículos por tipo e por estado.
2.Integração com dados populacionais — exibição da população por estado e cálculo da relação veículos por habitante.
3.Indicador de mortalidade no trânsito (DATASUS) — total de mortes por estado e ano, com cálculo da taxa por 100 mil habitantes.
4.Mapa comparativo simples — visualização das taxas de mortalidade por estado em um único ano selecionável.
5.Filtros principais — seleção por estado e ano para atualização dos gráficos e indicadores. 

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 🔑 User Stories (Backlog do MVP)
| Rank  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| 1 | Como tomador de decisões de politicas públicas, quero uma visualização interativa da frota nacional, apresentando quantidade de veículos por tipo e ano, com filtros por estado e comparativos de evolução histórica para identificar tendências no crescimento da frota.        | Alta       | 4   |
| 2 | Como tomador de decisões de politicas públicas, quero visualizar dados da população nacional segmentados por estado, ano, faixa etária e gênero com possibilidade de cruzar informações com frota e acidentes, para avaliar riscos e impactos regionais.         | Alta      | 3   |
| 3 | Como tomador de decisões de politicas públicas, quero uma visualização consolidada da mortalidade do DATASUS, apresentando evolução temporal com comparativos por gênero, idade e localização para compreender os fatores associados às mortes no trânsito.         | Alta      | 1   |
| 4 | Como tomador de decisões de politicas públicas, quero indicadoresde de mortalidade por 100mil habitantes, com gráficos comparativos entre estados e séries temporais, para identificar regiões mais críticas e acompanhar se políticas públicas têm reduzido as taxas.         | Alta      | 2   |
| 5 | Como tomador de decisões de politicas públicas, quero indicadoresde de sinistros por 10 mil veículos, com comparativos anuais e regionais, apresentados em mapa interativo e gráficos de evolução, para medir a gravidade e frequência relativa de acidentes no país.         | Alta      | 2   |

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | visualização interativa da frota nacional, apresentando quantidade de veículos por tipo e ano, com filtros por estado e comparativos de evolução  | Concluído|
| 01     | dados da população nacional segmentados por estado, ano, faixa etária e gênero                           | Concluído |
| 01     | visualização consolidada da mortalidade do DATASUS, apresentando evolução temporal com comparativos por gênero, idade e localização                           | Concluído |
| 01     | indicadoresde de mortalidade por 100mil habitantes, com gráficos comparativos entre estados e séries temporais                           | Concluído |
| 01     | indicadoresde de sinistros por 10 mil veículos, com comparativos anuais e regionais, apresentados em mapa interativo e gráficos de evolução                           | Concluído |

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 📊 Critérios de Aceitação
- A principal ação consiste em criar um painel interativo integrado, reunindo informações sobre frota de veículos, população e mortalidade no trânsito em uma única plataforma visual.  
- O evento importante é a disponibilização do painel interativo funcional, que permite aos gestores públicos visualizar e analisar de forma consolidada os dados de frota, população e mortalidade no trânsito. 
- As métricas coletadas para esta etapa podem incluir:
1.Tempo de resposta do painel — duração para carregar gráficos e mapas após a aplicação de filtros.
2.Taxa de uso — número de acessos ou interações por usuário no painel.
3.Cobertura de dados — percentual de estados e anos disponíveis para análise em cada indicador (frota, população, mortalidade).
4.Taxa de atualização — frequência com que os dados do painel refletem as informações mais recentes das bases oficiais.
5.Precisão dos indicadores — consistência dos cálculos de mortalidade por 100 mil habitantes e sinistros por 10 mil veículos.
6.Engajamento dos filtros — quais filtros (estado, ano, tipo de veículo, faixa etária) são mais utilizados pelos usuários.  

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 📈 Métricas de Validação
- Número de usuários que testaram o painel: 5
- Feedback qualitativo (positivo/negativo): Obtivemos um feedback positivo sobre o painel interativo, estava completo e continha todos os requisitos do cliente. 

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 🚀 Próximos Passos
- Melhorias planejadas após feedback: Utilização de outros sites para a coleta de informações.
- Ajustes de usabilidade: melhorias nos botões e interatividade. 

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

## 📂 Anexos / Evidências
- Tela 1:
  <img width="1280" height="720" alt="Design sem nome" src="https://github.com/user-attachments/assets/2506b513-9c4f-4a81-91f9-f8cce4772e26" />

- Tela 2:
  <img width="1280" height="720" alt="Design sem nome (1)" src="https://github.com/user-attachments/assets/d1407c3a-06b5-4285-aee5-432f5aee64cb" />

- Vídeo (MVP)

(Assista)https://www.canva.com/design/DAG3UNOUz2o/qlFJZi0deNN8fF5D9AOnSA/edit?utm_content=DAG3UNOUz2o&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

![Linha RGB](https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif)

* [Volte ao topo](#MVP-Sprint-01)
