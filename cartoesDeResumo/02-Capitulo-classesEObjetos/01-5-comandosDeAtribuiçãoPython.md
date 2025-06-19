# 2.2 Comando de Atribuição em Python 📝🐍


## 1. Comando de Atribuição (“=”)  
- **Fundamento:**  
    Associa um **identificador** (nome) a um **objeto** resultante de uma **expressão**. Em Python, `=` cria e liga nomes a objetos dinamicamente.

- **Exemplo Lúdico:**  
    Imagine escrever seu nome em um baú vazio e, de repente, todos os tesouros daquela sala passam a pertencer àquele baú! 🏺✨  

- **Exemplo Prático:**  
    ```python
    a = 10         # cria o objeto inteiro 10 e liga-o ao nome 'a'
    m = "olá!"     # cria o objeto string "olá!" e liga-o ao nome 'm'
    ```


## 2. Identificador (Nome) 📛
- **Fundamento:**
    É o nome que você dá a um objeto. Deve começar com letra ou _, sem espaços, e distingue maiúsculas de minúsculas.

- **Exemplo Lúdico:**
    Como batizar seu dragão de “FúriaSombria” e garantir que só aquele dragão atenda ao seu chamado! 🐉

- **Exemplo Prático:**
    ```python
    total_vendas = 500   # identificador válido
    # 2total = 100       # inválido: não pode começar com número
    ```


## 3. Expressão ➗➕
- **Fundamento:**
    O lado direito de = pode ser:
    - Literal: valor fixo (e.g., 42, 'texto')
    - Outro objeto: b = a
    - Operação aritmética: c = a + 10
    - Chamada de função: d = len("hi")
    - Combinação: mistura dos anteriores
  
- **Exemplo Lúdico:**
    Misturar ingredientes (literals), receitas prontas (funções) e poções existentes (objetos) para criar um novo elixir! 🧪

- **Exemplo Prático:**
    ```python
    x = 5                 # literal
    y = x                 # outro objeto
    z = x * 2 + len("!")  # fórmula + função
    ```


## 4. NameError – Nome Não Definido 🚫
- **Fundamento:**
    Se você tenta usar um nome antes de atribuí-lo, o interpretador lança NameError. É sinal de que o objeto não existe ainda.

- **Exemplo Lúdico:**
    Tentar invocar um familiar mágico que você ainda não escolheu o nome resulta em silêncio absoluto—nenhum familiar atende! 🤷‍♂️

- **Exemplo Prático:**
    ```python
    print(a)  # NameError: name 'a' is not defined
    a = 10
    print(a)  # 10
    ```


## 5. type() – Identificando a Classe 🎭
- **Fundamento:**
    A função type(objeto) revela a classe do objeto (“<class 'int'>”, “<class 'str'>”, etc.), mostrando seu tipo em tempo de execução.

- **Exemplo Lúdico:**
    Como olhar para um artefato mágico e ver sua “essência”: gelo, fogo ou ar? ❄️🔥💨

- **Exemplo Prático:**
    ```python
    print(type(42))       # <class 'int'>
    print(type("texto"))  # <class 'str'>
    ```


## 6. id() – Identificador Único de Objeto 🔍
- **Fundamento:**
    Cada objeto criado recebe um número único (id) que indica seu endereço na memória. id(obj) retorna esse número.

- **Exemplo Lúdico:**
    Cada criatura mágica recebe uma impressão digital única que nunca muda durante sua vida! 🧩

- **Exemplo Prático:**
    ```python
    a = 10
    b = 10
    print(id(a), id(b))  # geralmente iguais: reuse do mesmo objeto
    ```



## 7. Reuso de Objetos Imutáveis 🔄
- **Fundamento:**
    Python reusa objetos imutáveis (como pequenos ints e strings) com mesmo valor em vez de recriá-los, economizando memória.

- **Exemplo Lúdico:**
    Em um baú de tesouros infinitos, moedas de mesmo valor aparecem como cópias perfeitas de um mesmo artefato! 💰
- **Exemplo Prático:**
    ```python
    obj1 = 10
    obj2 = 10
    print(id(obj1) == id(obj2))  # True
    


# 8. Rebinding – Alterando Ligação 🔀
- **Fundamento:**
    Atribuir um novo valor a um identificador faz com que ele se desvincule do objeto antigo e ligue a um novo objeto, com novo id.

- **Exemplo Lúdico:**
    Como mudar o destinho de um feitiço: antes estava preso a um goblin, agora invoca um dragão! 🐲

- **Exemplo Prático:**
    ```python
    z = 50
    old_id = id(z)
    z = 90
    print(old_id, id(z))  # IDs diferentes após rebinding
    z = 50
    old_id = id(z)
    z = 90
    print(old_id, id(z))  # IDs diferentes após rebinding
    ```

Cada um desses conceitos—atribuição, identificador, expressão, NameError, type(), id(), reuso e rebinding—compõe o núcleo do Modelo de Dados de Python, demonstrando como nomes e objetos interagem em memória. 🌟💻