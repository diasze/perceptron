# perceptron
Perceptron em Python

Este projeto implementa um Perceptron simples, o modelo de rede neural mais básico, em Python.
O Perceptron realiza um somatório ponderado dos valores de entrada com seus respectivos pesos, adiciona um viés (bias) e aplica uma função de ativação do tipo degrau.

📌 Estrutura do Código
1. perceptron_input(inputs, weights, bias)

Calcula o somatório ponderado das entradas:

resultado
=
∑
(
𝑒
𝑛
𝑡
𝑟
𝑎
𝑑
𝑎
×
𝑝
𝑒
𝑠
𝑜
)
+
𝑏
𝑖
𝑎
𝑠
resultado=∑(entrada×peso)+bias
2. perceptron_output(inputs, weights, bias)

Aplica a função de ativação:

Retorna 1 se o valor do somatório for maior ou igual a 0.

Retorna 0 caso contrário.

3. main()

Exibe mensagens no console.

Calcula e mostra o resultado do perceptron.

▶️ Como Executar

Clone este repositório ou copie o código para um arquivo perceptron.py.

Execute no terminal:

python perceptron.py

📊 Exemplo de Saída

Com as entradas [1, 2, 3], pesos [0.1, 0.2, 0.3] e viés 0.4, a saída será:

Hello, World!
This is the main file.
The result of the perceptron input is:  1.8


Se você usar a função perceptron_output, o resultado será:

1

📚 Importância

O Perceptron é importante historicamente por ser a base das redes neurais modernas.
Apesar de simples (apenas classifica de forma linear), ele abriu caminho para arquiteturas mais complexas, como redes multicamadas (MLP) e deep learning.


CONCEITO

Um perceptron é definido como um modelo computacional composto por um único neurônio com duas entradas, capaz de executar tarefas simples, como classificação binária

FUNCIONAMENTO

Quando dizemos que o Perceptron é um classificador linear, significa que ele só consegue separar os dados em duas classes usando uma reta (em 2D), um plano (em 3D) ou, de forma geral, um hiperplano.

Exemplo: em um gráfico 2D, ele consegue separar pontos vermelhos de azuis se uma única linha conseguir dividir os dois grupos.

Limitação: não consegue resolver problemas linearmente não separáveis, como o clássico problema do XOR, onde os pontos não podem ser separados apenas com uma linha reta.

CODIGO

Definer pesos iniciais, calcular saida,ajustar pesos.

APLICAÇÃO PRATICA

Um exemplo prático seria o filtro de spam em e-mails simples.
O Perceptron poderia aprender a classificar mensagens como spam ou não spam com base em palavras-chave (entradas).


