# FIAP_Modulo1_Tech_Challenge: Modelagem de Custos de Seguro Médico com Regressão Linear

## Descrição
Este projeto visa modelar e prever os custos de seguro médico utilizando técnicas de regressão linear, baseado em um conjunto de dados que inclui características como idade, sexo, IMC, entre outros.

## Motivação
Este projeto foi selecionado como parte de um desafio tecnológico no curso de pós-graduação em Inteligência Artificial para desenvolvedores. A escolha do tema se alinha com os objetivos educacionais de aplicar conceitos teóricos de machine learning em problemas reais, proporcionando uma experiência prática e relevante na área de IA. Através deste desafio, buscamos não apenas entender as técnicas de modelagem preditiva, mas também explorar como essas técnicas podem ser aplicadas efetivamente na previsão de custos em cenários do mundo real, como o mercado de seguros médicos.
### Tecnologias Utilizadas
 - Python
 - Bibliotecas: Pandas, NumPy, Matplotlib, Scikit-Learn
 - Ambiente: Google Colab
   
### Configuração e Instalação
O notebook pode ser acessado e executado diretamente no Google Colab. Certifique-se de ter acesso à Internet e uma conta Google para executar o notebook sem problemas.

### Como Usar
1. Acesse o notebook no Google Colab.
2. Siga as instruções no notebook para instalar quaisquer dependências necessárias.
3. Execute as células do notebook sequencialmente para ver a análise e os resultados.

### Dados
O dataset utilizado neste projeto foi recuperado do Kaggle e é parte de uma análise sobre custo de seguro médico com regressão linear. Ele inclui variáveis como idade, sexo, índice de massa corporal (IMC), número de dependentes, se o indivíduo fuma e a região geográfica dos segurados, além dos custos do seguro médico. Este conjunto de dados oferece uma excelente oportunidade para explorar como diferentes características podem influenciar os custos de seguro médico. Para mais detalhes, acesse o projeto original no Kaggle através do seguinte link: https://www.kaggle.com/code/mariapushkareva/medical-insurance-cost-with-linear-regression

### Resultados e Conclusões
Ao longo deste projeto, conseguimos identificar os fatores que exercem maior impacto nos custos de seguro médico. Observamos que o principal fator é se a pessoa é fumante, seguido de perto pelo índice de massa corporal (IMC) e pela idade do segurado. Esses resultados sublinham a importância de fatores de estilo de vida e condições de saúde na determinação dos custos de seguro.

Adicionalmente, realizamos uma série de experimentos com diferentes modelos de machine learning para prever os custos de seguro, utilizando a técnica de validação cruzada para garantir a robustez de nossos resultados. O algoritmo que se destacou, apresentando melhor desempenho, foi o `Random Forest`. Este modelo provou ser particularmente eficaz em capturar as complexidades e as interações entre as variáveis do nosso dataset.
