# Comentários em Python 💬🐍

Comentários são trechos de texto inseridos no código para explicar trechos e documentar algoritmos, mas que o interpretador ignora durante a execução. Eles são essenciais para manter o código legível e facilitar a manutenção e colaboração.


## 1. Comentário de Uma Linha (#)  
- **Fundamento:**  
  Em Python, o caractere `#` inicia um comentário de uma única linha. Tudo o que segue após o `#` é ignorado pelo interpretador. Essa forma de comentário é ideal para adicionar explicações curtas ou anotações ao lado de uma instrução.
- **Exemplo Lúdico:**  
  Imagine que o `#` é como um marcador mágico que transforma o restante da linha em tinta invisível para o computador — mas visível para os desenvolvedores! 🕵️‍♀️✨
- **Exemplo Prático:**  

```python
  # Este comentário explica que a função soma retorna a soma de dois números
  def soma(a, b):
      return a + b  # Retorna a soma dos dois parâmetros
```

## 2. Comentário de Múltiplas Linhas (Docstring)
- **Fundamento:**
Para comentários de várias linhas, utiliza-se um par de blocos delimitados por três aspas (simples ou duplas). Conhecidos como docstrings, esses comentários são usados para documentar funções, classes e módulos. Conforme a PEP-0257, o uso de aspas duplas é recomendado.
- **Exemplo Lúdico:**
Imagine uma docstring como um pergaminho encantado repleto de informações detalhadas que você escreve para compartilhar o “feitiço” completo por trás da sua função, enquanto o computador permanece encantado e ignora a mensagem! 📜🔮
- **Exemplo Prático:**

``` python
def multiplica(a, b):
    """
    Multiplica dois números.

    Parâmetros:
      a (int/float): O primeiro número.
      b (int/float): O segundo número.

    Retorna:
      int/float: O produto de a e b.
    """
    return a * b
```

# 3. Importância dos Comentários 💡
- **Fundamento:**
Comentários são fundamentais para documentar o código, esclarecendo a lógica e facilitando a compreensão por outros desenvolvedores (ou pelo próprio programador no futuro). Bons profissionais sempre comentam seus códigos para garantir que seu trabalho seja transparente, de fácil manutenção e colaboração.
- **Exemplo Lúdico:**
Imagine um mapa do tesouro: os comentários são as anotações e indicações que guiam outros exploradores através do complexo mundo do seu código, revelando os pontos-chave para encontrar os segredos escondidos! 🗺️🏴‍☠️
- **Exemplo Prático:**
Em um projeto colaborativo, um desenvolvedor pode inserir comentários detalhados explicando decisões de design ou a lógica de um algoritmo complexo, ajudando colegas a entender e modificar o código sem confusões.


