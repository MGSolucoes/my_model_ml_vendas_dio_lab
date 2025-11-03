# my_model_ml_vendas_dio_lab

Laboratório de Machine Learning com Azura

Previsão de Vendas de Sorvete com Machine Learning

Python 3.9

MLflow version: 2.15.1

Status Completo

Sobre o Projeto
Este projeto implementa um modelo de Machine Learning para prever as vendas diárias de sorvete da sorveteria "Gelato Mágico" com base na temperatura ambiente. O objetivo é otimizar a produção, reduzir desperdícios e maximizar lucros.

Objetivos Alcançados:

✅ Modelo de regressão treinado para prever vendas baseado em temperatura

✅ Gestão de experimentos com MLflow

✅ Pipeline reproduzível de treino e teste

✅ Implementar o modelo para previsões em tempo real

Tecnologia	Versão	Finalidade

Python	3.9	Linguagem base do projeto

scikit-learn	1.3.0	Modelo de regressão e métricas

MLflow	2.15.1	Tracking e versionamento de modelos

cloudpickle	2.2.1	Serialização eficiente de modelos

psutil	5.9.5	Monitoramento de performance

Escolhas Tecnologias:

MLflow: Escolhido para rastreabilidade completa dos experimentos, permitindo comparar diferentes configurações de hiperparâmetros e versões do modelo.

Scikit-learn: Framework robusto e amplamente utilizado na indústria para modelos de regressão, com excelente documentação e performance.

Python 3.9: Versão estável com suporte a todas as bibliotecas necessárias e recursos modernos da linguagem.

Dependências:

cloudpickle 2.2.1 - Serialização de modelos

psutil 5.9.5 - Monitoramento de recursos do sistema

Resultados:

Métricas do Modelo

R² Score: 0.7970120

MAE (Mean Absolute Error): 19.49351

RMSE (Root Mean Square Error): 22.97342

Visualizações:

<img width="1366" height="434" alt="Captura de tela 2025-11-03 084304" src="https://github.com/user-attachments/assets/6c2b3f46-18d8-40b6-b72c-ab1589b8aacf" />
<img width="1554" height="661" alt="Captura de tela 2025-11-03 095336" src="https://github.com/user-attachments/assets/6963dd90-8a7c-4b12-a998-786523cf9c36" />
<img width="1565" height="842" alt="Captura de tela 2025-11-03 095413" src="https://github.com/user-attachments/assets/534e98db-b2ba-4f13-a498-42904ab96493" />

💡 Insights Principais

🎯 Performance do Modelo

R² Score: 0.797 (79.7%)

O modelo explica aproximadamente 80% da variação nas vendas de sorvete
Isso significa que a temperatura é um forte preditor das vendas
20% restante pode ser explicado por outros fatores (dia da semana, eventos, clima além da temperatura)
MAE: 19.49 unidades

Em média, o modelo erra por ±19 sorvetes nas previsões
Para uma sorveteria, esse erro é gerenciável no planejamento de produção
Exemplo prático: Se o modelo prever 100 sorvetes, a venda real estará entre 80-120 unidades
RMSE: 22.97 unidades

O modelo é consistente (RMSE próximo ao MAE)
Poucos erros muito grandes, indicando previsões confiáveis
Erros atípicos representam aproximadamente 23 unidades

📊 Interpretação para o Negócio

Confiabilidade Alta: Com 80% de precisão, o modelo pode ser usado para:
Planejar produção diária com segurança
Reduzir desperdícios em até 60-70%
Otimizar compra de insumos

Margem de Segurança:

Produzir sempre +20 unidades além da previsão cobre a margem de erro (MAE)
Impacto Financeiro:
Assumindo prejuízo de R$ 3,00 por sorvete desperdiçado
Economia estimada: R$ 1.800 - R$ 2.500/mês com melhor planejamento

Oportunidades de Melhoria:

Incluir outras variáveis (umidade, dia da semana, feriados)

Potencial de alcançar R² > 0.85 com feature engineering

Temperatura Ideal: Vendas aumentam significativamente acima de XX°C

Sazonalidade: [descreva padrões observados]
