**Quando Usar Machine Learning**
Referência:
RUSSELL, Stuart; NORVIG, Peter. Inteligência Artificial: uma abordagem moderna. 4. ed. Rio de Janeiro: GEN LTC, 2022.

"...Ambiente dinâmico, parcialmente observável ou complexo demais para que um programador humano consiga prever e ditar todas as regras de transição de estado por meio de algoritmos tradicionais."

Referência:
BISHOP, Christopher M. Pattern Recognition and Machine Learning. New York: Springer, 2006.
"em problemas onde as variáveis de entrada possuem relações altamente não lineares e ruidosas, exigindo uma abordagem baseada em densidades de probabilidade e teoria da decisão."

**Etapas iniciais a partir das referências**

**1º Passo**
Qual é o problema a ser resolvido?
- Massifcar o entendimento do problema, quais dores enfrentadas nessa situação pelo cliente

Machine learning é a a solução ideal? Por que?
- Algum meio foi tentado antes do Machine Learnig? Se sim, o que deu errado, por que não deu certo?

Qual é a expectativa sobre resultado? O que queremos prever?
- Precisamos de certeza absoluta?

Quais decisões serão tomadas com a previsão feita pelo modelo?

**2º Tipificação do Problema**

Precisamos classificar alguma categoria?
- (Bom pagador, mal pagador)
- (Email SPAM - Não SPAM)
- (Sim ou Não - manutenção da frota)
- (Leads - Quente ou Frio) - Cliente que fecha negócio cliente que não vai fechar negócio

Precisamos prever um número?
- Preço de imóvel > 350mil
- Valorização de um ativo acima 10%
- Canditado "A" vencer eleição (>= 100mil) votos

Precisamos agrupar informações desconhecidas?
- Recomendar produtos ou filmes com base nos perfis (A,B,C...)
- Aplicar mais ou menos linha de crédito a clientes com perfis (A,B,C...)
- Definir rotas(A,B,C) dos veiculos com base nos dias/horario

**3º Definir a variável Alvo (Target)**
- A chamada variável dependente é uma das partes mais imortantes  do machine learning
É número? É texto?
Embora nos algoritimos tudo vire número, pois é necessário essa formatação para as operações matemáticas\
podemos ao final entregar os *rótulos* [Spam, Não Spam],etc.


**4º Coleta**
Onde estão os dados?
- Bancos de Dados (SGBDs, Nuvem, API, Sistemas Legado, sensores, logs, Internet)
Quis tipos? (JSON, CSV, EXCEL,XML,YAML, etc)
Como extrair/recepcionar?(Raspagem de dados, Dump,Envio direto, Sharepoint, Clone/fork de Repositório)

**5º Análise Exploratória dos Dados - EDA (Exploratory Data Analysis)**
- Contagem de registros
- Tipos de dados
- Contagem de nulos
- Dados duplicados
- RESUMO ESTATÍSTICO (Média, Mediana, Mín,Máx, Quartis, Outliers,Zeros, Valores faltantes, distribuição(nomal/assimetrica))
    - Porque essa fase é importante?
        - Auxiliar entre a escolha ou não de uma regressão linear...
        - Atestar a qualidade dos dados
        - Se há transformações a fazer nos dados
- Visualização
    - Histograma
    - Scatterplot (grafico de bolhas)
    - Graficos de analise de categorias (barras, treemap)

