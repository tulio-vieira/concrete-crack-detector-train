# Treinar rede neural para classificação imagens com fissuras

Este repositório apresenta os notebooks usados para preparar o banco de dados e treinar, usar e converter um modelo de aprendizado profundo para detecção de fissuras em concreto.
Os arquivos incluídos são:

* [split.ipynb](https://github.com/tulio-vieira/concrete-crack-detector-train/blob/main/split.ipynb): Este notebook faz a divisão do dataset em conjuntos de treino, validação e teste. O dataset usado pode ser encontrado [aqui](https://data.mendeley.com/datasets/5y9wdsg2zt/1).
* [train.ipynb](https://github.com/tulio-vieira/concrete-crack-detector-train/blob/main/train.ipynb): Este notebook faz o treinamento do modelo, e o salva no presente diretório.
* [detect.ipynb](https://github.com/tulio-vieira/concrete-crack-detector-train/blob/main/detect.ipynb): Carrega o modelo treinado e o utiliza para fazer predição em imagens de qualquer resolução, por meio de uma janela deslizante.
* [convert.ipynb](https://github.com/tulio-vieira/concrete-crack-detector-train/blob/main/convert.ipynb): Realiza a conversão do modelo para o formato [tensorflowjs](https://www.tensorflow.org/js), que o permite ser usado no ambiente javascript para aplicação no browser.