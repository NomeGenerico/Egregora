# Redes Neurais - Semana 1

## Recursos de Aprendizado

### Python
https://docs.python.org/pt-br/3/

### Redes Neurais
https://medium.com/brasil-ai/entendendo-o-funcionamento-de-uma-rede-neural-artificial-4463fcf44dd0

### Machine Learning IMPA (Teoria)
https://www.youtube.com/watch?v=dLLw6QjADjo&t=4738s

## Objetivo

Implementar uma rede neural mínima capaz de realizar inferência em um dataset simples.

Nesta etapa não haverá treinamento.

---

## Ambiente

### Instalar

- Python 3.12+
- Spyder ou VSCode

Não utilizaremos:

- TensorFlow
- PyTorch
- Bibliotecas de Machine Learning em geral

---

## Desafio

Você deverá implementar:

### Parte A - Neurônio

Implementar uma classe representando um neurônio.

A saída deve seguir:

Saída = (Inputs × Pesos) + Bias

---

### Parte B - Função de Ativação

Implementar uma função de ativação de sua escolha.

Sugestões:

- Degrau
- Sigmoid
- Tanh

---

### Parte C - Leitura do Dataset

Implementar um leitor capaz de carregar os dados fornecidos.
Não utilizar bibliotecas externas.

O data set representa pontos em um plano e uma classificação
Formato: 

x,y,tipo
x,y,tipo
...

---

### Parte D - Inferência

ininicializar a rede com pesos aleatórios.

Percorrer todos os exemplos do dataset.

Para cada exemplo:

1. Ler entradas
2. Executar a rede
3. Gerar classificação
4. Comparar com resposta correta

---

### Parte E - Métrica de Erro

Implementar uma métrica de erro.

Sugestões:

- Erro absoluto
- Erro quadrático

Ao final exibir:

- Erro total
- Erro médio

---

## Estrutura Sugerida

projeto/

├── DatSet.txt
├── neuronio.py
├── rede.py
└── main.py

---

## Entrega

### Código

- Implementação do neurônio
- Função de ativação
- Leitura do dataset
- Inferência
- Cálculo de erro

### Relatório Curto

Responder:

1. Qual função de ativação foi utilizada?
2. Quais pesos foram escolhidos?
3. Qual erro foi obtido?
4. O que acontece quando os pesos são alterados?
5. Quais limitações você observou?

## Próxima Semana
Treinando a nossa rede
