# PySpark.

# 1 **Introdução ao PySpark**

Para avançar nas suas habilidades com dados, é preciso dominar o Apache Spark. Usando a API do Spark para Pyhton, PySpark,você aproveitará a computação paralela com grandes datasets, e irá ficar pronto para alta performance limpando dados, criando novas featrures e implementando modelos de machine learning. 

O Apache Spark é uma alternativa poderosa ao Hadoop MapReduce, com recursos avançados como aprendizado de máquina, processamento de fluxo em tempo real e cálculos gráficos.

## 1.1 O que é Spark?

Spark é uma plataforma para computação em cluster. Spark permite que você espalhe permite distribuir dados e faz cálculos em clusters com vários nós (Pense em cada nó como um computador separado). Dividir seus dados facilita o trabalho com conjuntos de dados muito grandes porque cada nó funciona apenas com uma pequena quantidade de dados.

Na medida que cada nó trabalha em cada subset dos dados total, também realiza uma parte dos cálculos totais necessários, para que o processamento de dados e a computação sejam executados em paralelo nos nós do cluster. É um fato que a computação paralela pode tornar certos tipos de tarefas de programação muito mais rápidas.

No entanto, com maior poder de computação vem maior complexidade.

Decidir se o Spark é ou não a melhor solução para o seu problema requer alguma experiência, mas você pode considerar questões como:

- Meus dados são grandes demais para trabalhar em uma única máquina?
- Meus cálculos podem ser facilmente paralelizados?

# Instalando o PySpark no Google Colab
Instalar o PySpark não é um processo direto como de praxe em Python. Não basta usar um pip install apenas. Na verdade, antes de tudo é necessário instalar dependências como o **Java 8**, **Apache Spark 2.3.2** junto com o **Hadoop 2.7**.
