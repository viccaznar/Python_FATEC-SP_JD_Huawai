# 2.4 Atribuição Múltipla em Python 🔀🐍


## 1. Operador de Atribuição “=”  
- **Fundamento:** 
Liga um **identificador** (nome) a um **objeto** resultante de uma expressão. Cria o objeto se não existir.

- **Exemplo Lúdico:**  
    Imagine que você carimba seu nome em um baú vazio: daí em diante, tudo o que colocar lá passa a pertencer a esse baú! 🏺

- **Exemplo Prático:**  
```python
    a = 10    # cria objeto inteiro 10 e nomeia-o ‘a’
    b = a     # aponta b para o mesmo objeto 10
```


## 2. Atribuição em Cadeia (Chain Assignment) 🔗
- **Fundamento:**
Permite criar vários nomes que apontam ao mesmo objeto imutável em uma só linha

- **Exemplo Lúdico:**
    Como distribuir cópias de um mesmo cristal mágico para dois magos; ambos seguram a MESMA joia! 💎✨

- **Exemplo Prático:**
```python
    A = B = 100
    print(id(A), id(B))  # mesmos IDs: A e B referenciam o mesmo objeto int
```


## 3. Imutabilidade e Cadeia 🚫🔄
- **Fundamento:**
Para objetos imutáveis (int, float, str, tuple), toda alteração via atribuição descarta o objeto antigo e cria um novo com novo id.

- **Exemplo Lúdico:**
    Como derreter um cubo de gelo e congelar outro com formato diferente—você nunca altera o cubo original! ❄️🗿

- **Exemplo Prático:**
```python
    A = B = 5
    A += 1                 # cria novo objeto 6 e liga apenas A a ele
    print(A, B)            # 6, 5

    A = B = 5
    A += 1                 # cria novo objeto 6 e liga apenas A a ele
    print(A, B)            # 6, 5
```


## 4. Mutabilidade e Cadeia 🔄✨
- **Fundamento:**
    Com objetos mutáveis (list, dict, set), A e B apontam para o MESMO container. Alterar o conteúdo via um reflete no outro.

- **Exemplo Lúdico:**
    Imagine dois elfos segurando a mesma sacola mágica: se um coloca uma gema dentro, o outro também a verá! 🧝‍♀️🎒

- **Exemplo Prático:**
```python
    A = B = []
    A.append(42)
    print(B)    # [42] – B também mudou, pois A e B referenciam a mesma lista
```


## 5. Atribuição por Desempacotamento (Unpacking) 📦
- **Fundamento:**
Permite criar múltiplos nomes e atribuir valores correspondentes pela ordem dos elementos:
```python
    A, B = 10, 15
    X, Y, Z = 12, 7.5, 8.43
```

- **Exemplo Lúdico:**
    É como distribuir as fatias de uma pizza a três amigos — cada um pega sua fatia pela posição na roda! 🍕

- **Exemplo Prático:**
```python
    nome, idade = "Ana", 28
    print(nome, idade)     # Ana 28
```


## 6. Ordem Posicional na Atribuição 📋
- **Fundamento:**
O Python alinha cada nome à expressão correspondente por posição: o primeiro nome ao primeiro valor, o segundo ao segundo, etc.

- **Exemplo Lúdico:**
    Imagine corredores alinhados num pódio: o primeiro guarda o troféu de ouro, o segundo o de prata, e assim por diante! 🥇🥈

- **Exemplo Prático:**
```python
    a, b, c = 1, 2, 3
    print(a, b, c)   # 1 2 3
```


## 7. Inspeção de Objetos: type() e print() 🔍
- **Fundamento:**
- type(obj) revela a classe do objeto (int, float, str, etc.).
- print() exibe valores na tela.
  
- **Exemplo Lúdico:**
    Como olhar um artefato mágico e descobrir se é de fogo, gelo ou terra antes de usá-lo! 🔥❄️🌍

- **Exemplo Prático:**
```python
    x, y = 5, "oi"
    print(type(x), type(y))  # <class 'int'> <class 'str'>
    print(x, y)              # 5 oi
```

Estes conceitos de atribuição simples, cadeia, imutabilidade, mutabilidade e desempacotamento formam o alicerce para manipular nomes e objetos em Python de forma clara e poderosa! 🚀🐍


