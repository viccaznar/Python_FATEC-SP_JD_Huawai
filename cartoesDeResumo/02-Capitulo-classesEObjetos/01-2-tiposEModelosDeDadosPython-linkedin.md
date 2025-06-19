# 2.1.2 Tipos de Dados & Modelo de Dados de Python 🐍📦


## 1. Tipo de Dado 📊  
**Fundamento:**  
Define a “natureza” do valor que uma variável armazena (ex.: `int` para inteiros, `float` para reais, `str` para texto). Em Python, o tipo é inferido automaticamente na atribuição.  

- **Exemplo Lúdico:**  
  Imagine frascos de poções mágicas: um frasco para poções sólidas (inteiros 🧂), outro para líquidos cintilantes (reais 💧) e um livro de feitiços (texto 📜).  

- **Exemplo Prático:**  
  ```python
  qtde = 2         # int
  puni = 36.90     # float
  msg = "Total"    # str
  ```


## 2. Tipagem Estática (C/Java) 🎛️
**Fundamento:**
    Requer declaração prévia de variável e tipo. Depois de definida, seu tipo não pode mudar durante a execução.

- **Exemplo Lúdico:**
    Pense em caixas lacradas onde cada tipo de tesouro só pode entrar na caixa certa — você não pode nunca colocar poção líquida no frasco de moedas! 🚫🧪

- **Exemplo Prático (Java):**
    ```java
    int qtde = 2;
    double puni = 36.90;
    // qtde = "texto"; // ERRO: tipo incompatível
    ```


## 3. Tipagem Dinâmica (Python/PHP) 🧙‍♀️
**Fundamento:**
    Não é preciso declarar tipo antes. A variável assume o tipo do valor atribuído e pode até mudar de tipo ao longo do programa.

- **Exemplo Lúdico:**
    Imagine uma mochila mágica que se expande para caber qualquer tipo de tesouro — moedas, pergaminhos ou poções — sem exigir caixas separadas! 🎒✨

- **Exemplo Prático:**
    ```python
    x = 10           # x é int
    x = "agora sou texto"  # x virou str sem reclamar
    ```


## 4. Classes 🏗️
**Fundamento:**
    Um molde ou “projeto” que define atributos (dados) e métodos (comportamentos). Em Python, classes são a base para criar objetos.

- **Exemplo Lúdico:**
    Pense em uma receita de bolo: lista ingredientes (atributos) e passos (métodos) para produzir bolos deliciosos! 🎂📖

- **Exemplo Prático:**
  ```python
  class Produto:
      def __init__(self, nome, preco):
          self.nome = nome
          self.preco = preco
  ```


## 5. Objetos 🎭
**Fundamento:**
    Instâncias reais de uma classe que ocupam memória e podem executar métodos definidos pelo “molde”.

- **Exemplo Lúdico:**
    Imagine usar seu cortador de biscoitos (classe) para criar biscoitos individuais (objetos) prontos para degustar! 🍪

- **Exemplo Prático:**
    ```python
    livro = Produto("Caderno", 36.90)
    print(livro.nome, livro.preco)  # usa o objeto criado
    ```


## 6. Paradigma de Programação Orientada a Objetos (POO) 📐
**Fundamento:**
    Modelo que estrutura o software em objetos, combinando dados (atributos) e comportamentos (métodos). Python adota totalmente esse paradigma.

- **Exemplo Lúdico:**
    Visualize um reino de castelos (classes) onde cada castelo ergue vários guardiões (objetos), cada um protegendo um tesouro e seguindo regras próprias! 🏰⚔️

- **Exemplo Prático:**
    Organizar seu programa em módulos de classes como Cliente, Pedido e Produto, cada um com atributos e métodos que espelham entidades reais e suas ações. 

