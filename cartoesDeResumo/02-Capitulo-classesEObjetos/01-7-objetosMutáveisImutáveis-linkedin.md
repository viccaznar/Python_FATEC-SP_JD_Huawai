# 2.3.1 Objetos Imutáveis 🚫🔄

- **Fundamento:**  
    Objetos imutáveis não mudam seu conteúdo após serem criados. Se você “troca” o valor, o Python descarta o objeto antigo e cria um novo, com um `id` diferente.

- **Classes Comuns:**  
    - `int` (números inteiros)  
    - `float` (números reais)  
    - `str` (cadeias de caracteres)  
    - `tuple` (tuplas)  
  
- **Exemplo Lúdico:**
    Imagine uma estátua de gelo: para mudar seu formato você não a esculpe por dentro, você derrete e congela um novo bloco! ❄️🗿
      
- **Exemplo Prático:**  
```python
    obj1 = 8
    print(id(obj1))   # e.g. 140730012416664
    obj1 = 12         # descarta o 8 e cria um novo objeto 12
    print(id(obj1))   # diferente do anterior
```


## 2.3.2 Objetos Mutáveis 🔄✨
- **Fundamento:**
    Objetos mutáveis permitem modificar seu conteúdo “in-place” (no próprio objeto) sem mudar seu id. São ideais para coleções que você precisa atualizar.
    - **Classes Comuns:**
      - list (listas)
      - dict (dicionários)
      - set (conjuntos)
  
- **Exemplo Lúdico:**
    Pense em um balão de borracha: você pode encher, esvaziar ou mudar a cor sem trocar o balão — ele continua o mesmo! 🎈

- **Exemplo Prático:**
```python
    L = [44, 17, 26]
    print(id(L))     # e.g. 1563134844544
    L[0] = 12        # mutação do conteúdo, mesmo objeto
    print(id(L))     # id permanece igual
    print(L)         # [12, 17, 26]
```

**Visão Geral:**
O Modelo de Dados de Python agrupa classes em imutáveis e mutáveis. Conhecer essa distinção é crucial para:
  - Evitar surpresas com id e reuso de objetos.
  - Escrever código eficiente, entendendo quando um objeto será recriado ou modificado “in-place”.
  - Prevenir bugs em situações de compartilhamento de referências.
  Para detalhes completos sobre cada classe, consulte a documentação oficial em:

