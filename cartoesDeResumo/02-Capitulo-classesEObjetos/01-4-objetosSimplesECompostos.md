# 2.1.4 Objetos Simples & 2.1.5 Objetos Compostos em Python 🐍✨

## A) Objetos Simples 📦  
Valores indivisíveis que representam uma única informação.

1. **int**  
   - Fundamento: Armazena números inteiros (… -2, -1, 0, 1, 2 …).  
   - Lúdico: Imagine caixas de moedas mágicas que só aceitam valores exatos, sem pedaços! 🪙  
   - Prático:  
     ```python
     idade = 30          # <class 'int'>
     ```

2. **float**  
   - Fundamento: Números reais com parte decimal (usa ponto).  
   - Lúdico: Pense em poções líquidas que medem cada gota com precisão! 🧪  
   - Prático:  
     ```python
     preco = 19.99       # <class 'float'>
     ```

3. **complex**  
   - Fundamento: Números complexos (parte real + imag * j).  
   - Lúdico: Um mapa mágico que combina um reino real e um reino imaginário! 🗺️✨  
   - Prático:  
     ```python
     z = 2 + 3j          # <class 'complex'>
     ```

4. **bool**  
   - Fundamento: Valores lógicos, `True` ou `False`.  
   - Lúdico: Um dragão que, ao responder “sim” ou “não”, abre portais! 🐉👍/👎  
   - Prático:  
     ```python
     ativo = True        # <class 'bool'>
     ```

5. **NoneType (None)**  
   - Fundamento: Representa **ausência** de valor.  
   - Lúdico: Um baú vazio aguardando um tesouro; nada está dentro! 📭  
   - Prático:  
     ```python
     resultado = None    # <class 'NoneType'>
     if resultado is None:
         print("Sem valor")
     ```

---

## B) Objetos Compostos 🧩  
Coleções de objetos (simples ou compostos) que podem ser acessados ou iterados.

1. **str**  
   - Fundamento: Cadeia de caracteres (texto).  
   - Lúdico: Um pergaminho encantado que conta histórias palavra por palavra! 📜  
   - Prático:  
     ```python
     texto = "Olá, Mundo!"  # <class 'str'>
     ```

2. **list**  
   - Fundamento: Sequência mutável de objetos, acessível por índices.  
   - Lúdico: Uma fila de carruagens no festival, onde você pode adicionar ou remover convidado! 🎡  
   - Prático:  
     ```python
     frutas = ["maçã", "banana", "laranja"]  # <class 'list'>
     ```

3. **tuple**  
   - Fundamento: Sequência imutável de objetos.  
   - Lúdico: Um relicário selado que não deixa nada escapar ou mudar de lugar! 🔒  
   - Prático:  
     ```python
     coords = (10, 20)      # <class 'tuple'>
     ```

4. **range**  
   - Fundamento: Gera sequência de inteiros em progressão aritmética.  
   - Lúdico: Trilhas marcadas por lanternas que aparecem passo a passo! 🏮  
   - Prático:  
     ```python
     for i in range(1, 5): print(i)  # 1,2,3,4
     ```

5. **dict**  
   - Fundamento: Mapeamento chave→valor (dicionário).  
   - Lúdico: Um grimório onde cada feitiço (chave) conjura um efeito (valor)! 🔮  
   - Prático:  
     ```python
     estoque = {'caneta': 50, 'caderno': 20}  # <class 'dict'>
     ```

6. **set**  
   - Fundamento: Conjunto de elementos únicos, sem ordem.  
   - Lúdico: Uma reunião de cavaleiros onde ninguém repete o escudo! ⚔️  
   - Prático:  
     ```python
     unicos = {1, 2, 3, 2}  # converte para {1,2,3}  # <class 'set'>
     ```

7. **frozenset**  
   - Fundamento: Conjunto imutável de elementos únicos.  
   - Lúdico: Tatuagem mágica que sela um conjunto para sempre! 🟣  
   - Prático:  
     ```python
     selado = frozenset([1,2,3])  # <class 'frozenset'>
     ```

8. **bytes, bytearray, memoryview**  
   - Fundamento: Sequências de bytes para dados binários (áudio, imagem, rede).  
   - Lúdico: Fios energéticos que carregam sinais secretos entre reinos digitais! 🔌  
   - Prático:**  
     ```python
     dados = b'\xFF\xA0'          # <class 'bytes'>
     arr = bytearray(dados)       # <class 'bytearray'>
     mv = memoryview(arr)         # <class 'memoryview'>
     ```

---

**Resumo:**  
- **Objetos Simples:** `int`, `float`, `complex`, `bool`, `None`.  
- **Objetos Compostos:** `str`, `list`, `tuple`, `range`, `dict`, `set`, `frozenset`, `bytes`, `bytearray`, `memoryview`.  

Cada classe define **estrutura** e **comportamento**, permitindo modelar dados do mundo real (ou mágico!) de forma clara e reutilizável. 🚀🐍