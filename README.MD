# Implementação e Análise de Classificação com Redes Convolucionais e o dataset CUFS


## Objetivo do Projeto: 

O objetivo deste trabalho foi utilizar o dataset CUHK Face Sketch Database (CUFS) para classificar imagens de rostos em duas categorias: masculino e feminino, com base no sexo biológico utilizando redes neurais convolucionais.



## Instalação e uso: 

1. Clone o repositório:
```
https://github.com/lusgaoliveira/restic-desafio-cnn.git
```

2. Entre na pasta:
```
cd restic-desafio-cnn
```

3. Crie o ambiente:
```
conda env create -f environment.yml
```

4. Ative o ambiente:
```
conda activate meu_projeto
```

Você pode modificar o nome no environment.yml

5. Inicie o Jupyter Notebook:
```
jupyter notebook
```

## Estrutura dos Arquivos: 

No arquivo cnn.ipynb está o notebook com o código fonte. Na pasta ./docs está o relatório técnico do projeto em PDF.


## Principais Conclusões e Considerações:

O projeto demonstrou com sucesso a aplicação de redes neurais convolucionais para classificar imagens de faces humanas por sexo biológico, utilizando como fonte de dados o dataset "CUHK Face Sketch Database (CUFS)". O modelo alcançou métricas sólidas, como um F1-Score de aproximadamente 0,90 e uma AUC de 0,98, evidenciando sua capacidade de equilibrar com eficácia precisão e recall, além de separar eficientemente as classes. Esses resultados demonstram que a arquitetura proposta é eficaz e possui potencial para ser generalizada em problemas semelhantes.
Um ponto importante a se destacar é que a análise qualitativa das previsões incorretas revelou que características faciais ambíguas podem dificultar a classificação, evidenciando os desafios intrínsecos de trabalhar com características humanas sutis.
Além disso, foi observado que o processamento do modelo demandou um tempo considerável, em parte devido à complexidade do modelo e ao uso de recursos computacionais limitados, como GPUs de menor desempenho ou CPU. Essa demora ressalta a importância de considerar a otimização de recursos computacionais, seja por meio de técnicas como quantização do modelo ou uso de hardware mais potente, para que a aplicação se torne mais acessível e eficiente.

## Tecnologias Utilizadas: 
- Anaconda
- Juptyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Numpy
- Tensorflow
- Pillow
- Pip
- Keras

## Autores e Colaboradores:
- Lucas Silva de Oliveira 
- Samy Celes Barrozo 