Previsões e Predições

Este projeto faz parte do curso de Data Analytics e foca em previsões e predições, aplicando análise de dados para prever o comportamento de clientes em uma academia.

Descrição do Projeto

Você trabalha com a rede de academias Model Fitness, que busca desenvolver uma estratégia de retenção de clientes baseada em dados. O objetivo principal é prever a probabilidade de rotatividade de clientes no próximo mês, analisar perfis típicos de usuários e identificar fatores que impactam a retenção.

O projeto envolve:

Análise do comportamento de clientes: frequência de visitas, uso de serviços adicionais e dados demográficos.

Predição da rotatividade: criação de modelos de classificação binária.

Agrupamento de clientes: identificação de grupos com diferentes padrões de comportamento.

Conclusões e recomendações: estratégias para reduzir a rotatividade e melhorar a interação com clientes.

Conjunto de Dados

O dataset fornecido contém informações sobre clientes da academia:

Churn — indicador de rotatividade do mês.

Dados do mês anterior: gender, Near_Location, Partner, Promo_friends, Phone, age, Lifetime.

Dados do log de frequência e compras: Contract_period, Month_to_end_contract, Group_visits, Avg_class_frequency_total, Avg_class_frequency_current_month, Avg_additional_charges_total.

Caminho do arquivo: /datasets/gym_churn_us.csv

Cada linha representa informações de um cliente no mês em análise.

Etapas do Projeto

Análise Exploratória de Dados (AED)

Identificação de valores ausentes, estatísticas gerais, histogramas e distribuições.

Comparação de métricas entre clientes que permaneceram e os que saíram.

Matriz de correlação entre características.

Modelagem de Predição

Criação de modelos de classificação binária:

Regressão Logística

Floresta Aleatória

Avaliação de acurácia, precisão e sensibilidade.

Comparação de modelos para selecionar o melhor.

Agrupamento de Clientes

Padronização das características.

Construção de dendrograma e definição do número de clusters.

Aplicação do K-means para identificar grupos de clientes.

Análise das características médias e da taxa de rotatividade de cada cluster.

Conclusões e Recomendações

Identificação de grupos de clientes com maior risco de rotatividade.

Sugestões de medidas de retenção.

Observações sobre padrões de interação com os clientes.

Objetivos de Negócio

Reduzir a rotatividade de clientes.

Identificar perfis de clientes mais leais e os mais propensos a sair.

Fornecer insights para ações de marketing personalizadas e eficazes.

Tecnologias e Ferramentas

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook para documentação e execução do código

Algoritmos de Machine Learning: regressão logística, floresta aleatória e K-means
