# ANÁLISE DOS DADOS DE VENDAS DAS LOJAS FAVORITAS: APLICANDO TESTE T e RESPONDENDO PERGUNTAS, USANDO PYSPARK

![img_beyond_theory](https://github.com/user-attachments/assets/52176bf7-e67c-45f2-afb1-121691f18f7f)

# Objetivos de Negócio

Neste projeto tenho um conjunto de dados do periodo 2013 a 2017 com informações sobre as vendas das lojas Corporation Favorita, uma importante varejista de alimentos sediada no Equador. Os principais objetivos são: 
a. Entender o impacto das promoções nas vendas das lojas Favorita que ela possa adaptar suas estratégias de marketing e impulsionar as vendas durante períodos específicos. 
b. Responder a perguntas analíticas importantes. 
Ao alavancar dados históricos de vendas e informações suplementares relevantes, e fazer uma análise mais verticalizada dos dados pode-se fornecer informações confiáveis que permitam à gestão das lojas Favorita melhorar as tomadas de decisão, otimizando o gerenciamento de estoque, alocando recursos e estratégias de marketing. Para tanto utilizei o frameworks pyspark, bem como bibliotecas de visualizações. O projeto é composto de duas etapas, incluindo comprensão do negócio e compreensão e análise dos dados.Essa composição é parte inicial da estrutura de INTELIGENCIA ANALITICA DO BIG DATA PARA OS NEGÓCIOS.

![inteligencia analitica de big data](https://github.com/user-attachments/assets/69f2f967-3d2e-42bb-9a7e-8d7bdae744cc) 

# Compreensão do negócio

À medida que os grandes lojistas do varejo adicionam novos locais com necessidades únicas, novos produtos, gostos sazonais em constante transição e marketing de produtos imprevisíveis os problemas se tornam ainda mais complexos. Aproveitando os dados obtidos da Corporation Favorita, um importante varejista de alimentos sediados no Equador pode-se ajudar a parti das Hipóteses e Questões do Negócio.

Hipóteses e Questões do Negócio

Hipóteses Nula(H0): A intensidade da promoção (onpromotion) não tem um impacto significativo nas vendas médias dos produtos Alternativa.
(H1): A intensidade da promoção (onpromotion) tem um impacto significativo nas vendas médias dos produtos.

Perguntas do Negócio

. Quais dados têm as menores e maiores vendas em cada ano?
. Quais lojas estão entre as 10 maiores em termos de vendas totais?
. Quais cidades sede das lojas estão vendendo mais produtos?
. Quais são as cinco famílias de produtos mais frequentemente compradas 
. Existe alguma associação entre vendas por promoções, preços de petróleo  feriados e e transações?

# Compreensão, fonte e  análise dos dados

Este é um projeto que segue uma estrutura adaptada de CRISP-MD e usa dados dos anos de 2013 a 2017 das lojas para uma implementação bem sucedida.
Para atingir o sucesso dos objetivos do projeto, os seguintes requisitos de dados são necessários: 
. Dados de treinamento 
. Dados de teste Dados de transação
. Dados das lojas 
. Dados do preço do petróleo 
. Dados de feriados e eventos

Fonte dos dados: https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data 

Notas adicionais:
As negociações no setor público são pagas a cada duas semanas no dia 15 e no último dia do mês. 
As vendas de supermercados podem ser afetadas por isso. Um terremoto de magnitude 7,8 atingiu o Equador em 16 de abril de 2016. 
As pessoas se uniram em esforços de ajuda fazendo água e outros produtos de necessidade primeiro, o que afetou muito as vendas dos 
supermercados por várias semanas após o terremoto.

# Recomendações (adaptada de Alvin Momoh)
.Revise e ajuste regularmente as estratégias de marketing com base nas mudanças na dinâmica do mercado e no comportamento do cliente. Observou-se que promoções  tem um efeito positivo nas vendas de produtos, impulsionando as vendas durante períodos específicos, levando a loja a permanecer competitiva e bem-sucedida.

.Realize uma análise verticaliza das lojas de melhor desempenho (números de loja 44, 45, 47, 3 etc.) para identificar os principais fatores que contribuem para suas altas vendas. Isso pode incluir localização, variedade de produtos, estratégias de marketing e atendimento ao cliente. Identifique também fatorem que afetam o faturamento das lojas de menor desempenho. Isso pode susbstacializar a gestão e apoiar a replicação de estratégias de sucesso em outras lojas. Desenvolva um plano  e implemente estratégias de marketing eficazes, tanto online quanto offline. Considere campanhas de marketing direcionadas, promoções e programas de fidelidade para atrair e reter clientes. Monitore regularmente as métricas de desempenho e ajuste as estratégias de acordo para manter a competitividade e a lucratividade.

. Desenvolva um plano abrangente de preparação para emergências que descreva em detalhe os procedimentos de resposta da loja durante e após desastres naturais, como terremotos. Certifique-se de que todos os funcionários estejam familiarizados com este plano e conduza exercícios regulares para praticar respostas a emergências. Isso certamente ajudará as lojas de vendas não apenas a se adaptar às mudanças no comportamento do consumidor durante emergências, mas também a desempenhar um papel vital em ajudar a comunidade a se preparar e responder a desastres, aumentando assim sua reputação e valor na área local.

.Priorize e otimize o gerenciamento de estoque para as famílias de produtos de melhor desempenho, como "MERCADOS I" e "BEBIDAS". Garanta que esses itens estejam bem estocados e em destaque. 

. Expanda e diversifique a gama de produtos dentro das principais famílias de produtos para atender a uma gama mais ampla de preferências dos clientes. Ofereça uma variedade de marcas, tamanhos e sabores para atender às diversas necessidades dos clientes. Com isso, a loja de vendas pode não apenas capitalizar suas famílias de produtos de melhor desempenho, mas também aumentar a satisfação do cliente, impulsionar o crescimento das vendas e permanecer competitiva no mercado.





