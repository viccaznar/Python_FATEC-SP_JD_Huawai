# 2.5 Expressões Aritméticas em Python ➕➖✖️➗

## 1. Operandos e Operadores 📐
- **Fundamento:**  
    - **Operandos:** Valores numéricos (`int`, `float`, `complex`).  
    - **Operador:** Símbolo que indica a operação (`+`, `-`, `*`, `/`, `//`, `%`, `**`, `-unário`).

- **Exemplo Lúdico:**  
    Imagine ingredientes mágicos (operandos) e fórmulas alquímicas (operadores) que transformam um caldeirão em poção! 🧪  

- **Exemplo Prático:**  
```python
    A, B = 14, 5
    C = A + B  # 19
```


## 2. Principais Operadores Aritméticos 🛠️
  - **Adição** (+): C = A + B → Soma
  - **Subtração** (-): C = A - B → Diferença
  - **Multiplicação** (*): C = A * B → Produto
  - **Divisão** (/): C = A / B → Float
  - **Divisão Inteira** (//): C = A // B → Quociente Inteiro
  - **Módulo** (%): C = A % B → Resto
  - **Potenciação** (**): C = A ** B → Potência
  - **Negação Unária** (-A): Inverte sinal

- **Exemplo Lúdico:**
    Cada operador é como um feitiço diferente: + invoca união, * multiplica o poder, ** eleva a esfera ao infinito! ✨

- **Exemplo Prático:**
```python
    print(14 / 5)   # 2.8
    print(14 // 5)  # 2
    print(14 % 5)   # 4
    print(14 ** 5)  # 537824
```


## 3. Precedência de Operadores 🧮
- **Fundamento:**
    **Ordem de cálculo:**
      - Parênteses ()
      - Exponenciação **
      - Multiplicação *, Divisão /, //, Módulo %
      - Adição +, Subtração -

- **Exemplo Lúdico:**
    Como um ritual mágico que exige ordem: primeiro invocar o círculo (parênteses), depois erguer pilares (potências), e por fim mesclar ingredientes (multiplicação/soma)! 🔮

- **Exemplo Prático:**
```python
    A, B = 2, 5
    R1 = 2 * A + B       # 2*2 + 5 = 9
    R2 = 2 * (A + B)     # 2*(2+5) = 14
```


## 4. Expressões com Vários Operandos ➕➗➖
- **Fundamento:**
    Combinação de vários operadores seguindo precedência; use parênteses para alterar a ordem.

- **Exemplo Lúdico:**
    Conduzir um ritual com vários componentes: a ordem certa garante sucesso, ordem errada causa explosão! 💥

- **Exemplo Prático:**
```python
    A, B, C = 10, 25, 7
    print(2 * A + B)          # 45
    print((A + B) / (A + C))  # ≈1.909...
```


## 5. Atribuição Incremental (Operadores Compostos) ♻️
- **Fundamento:**
    Combina operação aritmética com atribuição.
      - A += 1  → A = A + 1
      - A -= 1  → A = A - 1
      - A *= 2  → A = A * 2
      - A /= 4  → A = A / 4

- **Exemplo Lúdico:**
    Como canalizar energia no mesmo cálice: em vez de criar um novo poção, você reforça o atual! 🔋

- **Exemplo Prático:**
```python
    A, P = 10, 4
    A += P    # 14
    A -= 10   # 4
    A *= 6    # 24
    A /= 4    # 6.0
```
