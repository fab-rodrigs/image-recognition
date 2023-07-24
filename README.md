# image-recognition

## Classificação de Dígitos Manuscritos com KNN

Este repositório contém um código Python que implementa o algoritmo de classificação KNN (K-Nearest Neighbors) para identificar dígitos manuscritos. O código utiliza a biblioteca scikit-learn e realiza as seguintes etapas:

1. **Carrega os pacotes necessários e o conjunto de dados de dígitos manuscritos.**

2. **Visualiza algumas imagens do conjunto de dados junto com seus rótulos.**

3. **Divide os dados em conjuntos de treino e teste.**

4. **Divide o conjunto de treino em treino e validação para ajuste dos hiperparâmetros.**

5. **Normaliza os dados para evitar a influência de atributos com escalas diferentes.**

6. **Encontra o melhor valor de "k" (número de vizinhos) usando validação cruzada.**

7. **Cria o modelo final com o melhor valor de "k" encontrado.**

8. **Avalia o modelo usando os dados de teste e gera a matriz de confusão.**

9. **Realiza previsões em alguns exemplos do conjunto de teste, mostrando as imagens e as previsões do modelo.**

10. **Faz uma previsão com um novo dígito manuscrito.**

O código é acompanhado de um notebook em formato Markdown que facilita a leitura e visualização dos resultados. O objetivo é fornecer um exemplo prático de como implementar e avaliar um classificador KNN para reconhecimento de dígitos manuscritos.

## Pré-requisitos:
- Python 3.x
- Bibliotecas: numpy, scikit-learn, matplotlib

## Instruções:
1. Instale as bibliotecas necessárias usando `pip install numpy scikit-learn matplotlib`.
2. Execute o notebook `Classificacao_Digitos_Manuscritos.ipynb` para ver a implementação passo a passo.

**Observação:**
O código pode ser facilmente adaptado para outros problemas de classificação, e o valor de "k" pode ser ajustado conforme necessário para obter o melhor desempenho no conjunto de validação.
