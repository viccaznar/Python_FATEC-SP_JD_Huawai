# 2.6 Funções Matemáticas em Python ⚙️➗

## 1. Categorias de Funções Matemáticas 📚  
- **Fundamento:**  
  Python oferece funções nativas (built-in) e módulos especializados:  
    - **Built-in:** não exigem import (`abs`, `int`, `float`, `round`)  
    - **math:** funções para `int`/`float` (`sqrt`, `floor`, `ceil`, etc.)  
    - **cmath:** funções para `complex` (`sqrt`, `exp`, `rect`, `polar`, etc.)
  
- **Exemplo Lúdico:**  
    Imagine ter poções básicas e frascos especiais que ampliam poderes conforme o tipo de ingrediente! 🧪  

- **Exemplo Prático:**  
```python
    import math, cmath
```


## 2. Conversão e Valor Absoluto 🔄
- **Fundamento:**
  - abs(x): valor absoluto de x
  - int(x): converte x truncando decimais
  - float(x): converte x para real

- **Exemplo Lúdico:**
    Como lapidar uma gema bruta (x) em joia polida (abs), barra metálica (int) ou elixir líquido (float)! 💎

- **Exemplo Prático:**
```python
    x = -7.8
    print(abs(x), int(x), float(5))  # 7.8, -7, 5.0
```


## 3. Arredondamento e Toque Final 🎯
- **Fundamento:**
    - round(x, n): arredonda x com n casas
    - math.trunc(x): elimina decimais
    - math.floor(x): maior inteiro ≤ x
    - math.ceil(x): menor inteiro ≥ x

- **Exemplo Lúdico:**
    É como afiar uma lâmina mágica: trunc lasca, floor baixa o fio, ceil eleva, e round encontra a lâmina perfeita! 🔪

- **Exemplo Prático:**
```python
    import math
    print(round(3.1415, 2), math.trunc(3.9), math.floor(3.9), math.ceil(3.1))
    # 3.14 3 3 4
```


## 4. Potência, Raiz e Logaritmo 🚀
- **Fundamento:**
  - math.sqrt(x): raiz quadrada
  - math.exp(x): e^x
  - math.log(x[, base]): log de x em base

- **Exemplo Lúdico:**
    Como lançar feitiços de multiplicação explosiva (exp), desenterrar raízes ancestrais (sqrt) e decifrar segredos de crescimento (log)! 🪄

- **Exemplo Prático:**
```python
    import math
    print(math.sqrt(16), math.exp(1), math.log(100, 10))  # 4.0, 2.718..., 2.0
```


## 5. Funções Trigonométricas 🌊
- **Fundamento:**
  - math.sin(x), math.cos(x), math.tan(x): seno, cosseno e tangente de x em radianos

- **Exemplo Lúdico:**
    Imagine ondulações num lago mágico: sin cria ondas suaves, cos ondulações completas e tan picos vertiginosos! 🌊

- **Exemplo Prático:**
```python
    import math
    angle = math.pi/4
    print(math.sin(angle), math.cos(angle), math.tan(angle))  # ~0.707, ~0.707, ~1.0
```


## 6. Cálculos com Números Complexos 🌀
- **Fundamento:**
**Módulo cmath traz:**
    - cmath.sqrt, cmath.exp, cmath.log, cmath.sin, cmath.cos, cmath.tan
    - cmath.rect(r, phi): polar → retangular
    - cmath.polar(z): retangular → polar

- **Exemplo Lúdico:**
    Como converter feitiços dimensionais: do reino polar (módulo/fase) ao plano retangular (x + y j) e vice-versa! 🌀

- **Exemplo Prático:**
```python
    import cmath
    z = 1+1j
    print(cmath.polar(z), cmath.rect(1.414, cmath.pi/4))
    # (1.414..., 0.785...), (1+1j)
```