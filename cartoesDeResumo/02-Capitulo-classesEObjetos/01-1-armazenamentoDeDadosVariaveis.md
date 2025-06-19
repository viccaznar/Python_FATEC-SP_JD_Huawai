# Capítulo 2.1 – Conceitos de Variáveis em Python 📚🐍

Este bloco organiza os principais conceitos apresentados em 2.1.1, com explicações objetivas, exemplos lúdicos e práticos.


## 1. Variável 💾  
- **Fundamento:**  
  Uma variável é um **nome** (identificador) que referencia um **endereço de memória** capaz de reter um valor (bits). Para o programador, é uma etiqueta legível; para o computador, é um local que armazena bytes representando um dado.

- **Exemplo Lúdico:**  
  Imagine uma caixinha mágica onde você rotula “Poção de Invisibilidade” e nela guarda o líquido secreto – sempre que desejar, basta chamar o rótulo para obter o conteúdo! 🎁🔮
    
- **Exemplo Prático:**   
  ```python
  qtde = 2       # qtde é o rótulo que aponta para o valor inteiro 2
  puni = 36.90   # puni armazena um valor real (float)
  ```


## 2. Tipos de Dados 📊
- **Fundamento:**
O “tipo” define a natureza do conteúdo de uma variável:
  - **int:** números inteiros
  - **float:** números reais (com parte decimal)
  - **str:** sequências de caracteres (texto)  
Em Python, o tipo é inferido automaticamente no momento da atribuição.

- **Exemplo Lúdico:**  
 Pense em frascos de poções:
    - Frasco sólido (int) 🧂
    - Frasco líquido (float) 💧
    - Pergaminho encantado (str) 📜
  
- **Exemplo Prático:**
    ```python
    - idade = 30          # int
    - altura = 1.75       # float
    - saudacao = "Olá!"   # str
    ```


## 3. Atribuição e Operações ➕✖️
- **Fundamento:**
  - O operador = atribui um valor a uma variável.
  - Operadores aritméticos (como *) processam valores para gerar resultados.

- **Exemplo Lúdico:**
    Imagine um caldeirão onde você despeja “2 unidades” e “36.90 gotas” e, com um agitador mágico (*), obtém a poção final! 🧪

- **Exemplo Prático:**
    ```python
    ptot = qtde * puni   # multiplica quantidade por preço unitário
    ```


## 4. Exibição de Resultados – print() 🖨️
- **Fundamento:**
    A função print() envia texto e valores ao console, tornando visível o resultado das operações do programa.

- **Exemplo Lúdico:**
    Pense no print() como um alto-falante mágico que anuncia em voz alta o desfecho do seu feitiço para todos ao redor! 📣

- **Exemplo Prático:**
    ```python
    msg = 'Total ='       
    print(msg, ptot)      # exibe: Total = 73.8
    ```


## 5. Estrutura de Exemplos – Código vs Saída 📑
- **Fundamento:**
    Nos exemplos didáticos, linhas escuras mostram o código, enquanto linhas claras exibem a saída resultante na tela.

- **Exemplo Lúdico:**
    Imagine que cada cena de um teatro tem o roteiro (linhas escuras) e, ao final, as luzes acesas revelam o espetáculo (linhas claras)! 🎭

- **Exemplo Prático:**
    ```python
    qtde = 2
    puni = 36.90
    ptot = qtde * puni
    msg = 'Total ='
    print(msg, ptot)

    Total = 73.8    ← Saída clara após o código escuro
    ```