🛍️ Segmentação de Clientes de Shopping com K-Means
____________________________________________________

🎯 Problema de Negócio

Empresas de varejo precisam entender melhor o comportamento dos seus clientes para direcionar estratégias de marketing, retenção e aumento de receita.

Este projeto tem como objetivo segmentar clientes de um shopping com base em renda e comportamento de consumo, identificando grupos com perfis distintos para apoiar decisões estratégicas.
__________________________________
📊 Sobre os Dados

A base contém 200 clientes, com as seguintes variáveis:

Idade

Gênero

Renda Anual (k$)

Spending Score (pontuação de consumo de 0 a 100)

Não foram identificados valores nulos ou inconsistentes.
____________________________________________________________

⚙️ Metodologia

O projeto seguiu o seguinte fluxo:

Entendimento dos dados

Análise exploratória (EDA + Profiling)

Pré-processamento (padronização das variáveis)

Escolha do número ideal de clusters (Elbow + Silhouette)

Treinamento do modelo K-Means

Interpretação dos clusters

Geração de insights de negócio
__________________________________________________________________________

🔎 Análise Exploratória (EDA)

Foram analisadas distribuições, correlações e relações entre variáveis.

Principais achados:

Clientes mais jovens tendem a ter maior spending score

Renda e score não possuem forte correlação linear

Existem padrões visuais claros de segmentação entre renda e consumo

Também foi utilizado profiling automatizado para acelerar a análise inicial.
_______________________________________________________________________________

🤖 Modelagem

Foi utilizado o algoritmo K-Means para segmentação.

Dados padronizados com StandardScaler

Número de clusters definido como K = 5

Validação com Silhouette Score ≈ 0.55
__________________________________________________________________________________

📈 Resultado da Segmentação

Foram identificados 5 grupos distintos de clientes.

💡 Perfis dos Clientes
Cluster	Perfil
0	Renda média, consumo médio
1	Alta renda, alto consumo (clientes premium)
2	Baixa renda, alto consumo
3	Alta renda, baixo consumo (potencial de crescimento)
4	Baixa renda, baixo consumo

_______________________________________________________________________
💼 Insights de Negócio

A segmentação permite ações estratégicas como:

Programas VIP para clientes premium

Campanhas de ativação para clientes de alta renda com baixo consumo

Promoções para clientes de alto consumo com menor renda

Redução de investimento em segmentos de baixo valor
______________________________________________________________________________

🧾 Conclusão

A aplicação de técnicas de clusterização permitiu transformar dados de clientes em insights estratégicos acionáveis, possibilitando decisões mais eficientes em marketing, retenção e crescimento de receita.
_________________________________________________________________________

🚀 Próximos Passos

Testar inclusão da variável idade no modelo

Avaliar impacto da variável gênero após codificação

Testar outros algoritmos de clusterização

Criar campanhas personalizadas por cluster

Aplicar o modelo em novos dados de clientes
_____________________________________________________________________

🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn
