# X-Ray-Covid-Detector
Detector de Coronavírus a partir de imagens de Raio-X.
Este código é uma reprodução da abordagem sugerida no seguinte artigo: https://doi.org/10.1016/j.compbiomed.2020.103792.
Diferente da abordagem dos autores aqui não foi utilizada a biblioteca FastAI, a divisão dos dados entre teste e treino é feita através de método de validação cruzada k-fold com 5 folds.
A acurácia obtida pelo modelo ao fim do treinamento foi de 77.5%.
