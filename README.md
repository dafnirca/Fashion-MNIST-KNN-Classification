# Fashion-MNIST K-NN Classification

Este repositório contém a aplicação do algoritmo K-Nearest Neighbors (K-NN) para classificar itens do dataset **Fashion-MNIST**, um conjunto de dados com imagens de roupas e acessórios. O projeto inclui etapas de pré-processamento, construção do modelo, análise de resultados e ajustes de parâmetros.

## 📊 Dataset
O **Fashion-MNIST** é um conjunto de dados composto por 70.000 imagens em escala de cinza (60.000 para treino e 10.000 para teste). Cada imagem tem dimensões de 28x28 pixels e pertence a uma das seguintes classes:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

Fonte: [Fashion-MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)

## 🛠️ Ferramentas e Tecnologias
- **Linguagem**: Python
- **Bibliotecas**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## 🚀 Implementação
1. **Pré-processamento dos Dados**:
   - Normalização das imagens.
   - Divisão em treino e teste.
2. **Construção do Modelo**:
   - Utilização do algoritmo K-NN.
   - Ajuste do hiperparâmetro K para diferentes valores.
3. **Validação**:
   - Validação cruzada para avaliar a estabilidade do modelo.
   - Holdout para verificar a generalização.
4. **Análise de Resultados**:
   - Matriz de confusão.
   - Avaliação de métricas como acurácia e erro.

## 📚 Conclusões
O modelo K-NN demonstrou bom desempenho para a classificação de imagens, especialmente após ajustes nos parâmetros e pré-processamento dos dados. Ainda assim, melhorias como redução de dimensionalidade (ex.: PCA) podem ser aplicadas para otimizar a performance.

## Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/dafnirca">
        <img src="https://avatars.githubusercontent.com/u/109047245?v=4" width="100px;" alt="Foto de Dafni Rosa no GitHub"/><br>
        <sub>
          <b>dafnirca</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
