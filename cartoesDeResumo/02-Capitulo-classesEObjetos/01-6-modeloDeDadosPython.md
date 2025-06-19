# 2.3 Modelo de Dados de Python – Aprofundamento 🐍🔍


## 1. id() – Identificador Único de Objetos 🔢  
- **Fundamento:**  
	Cada objeto Python recebe um número único (`id`) que representa seu “endereço” na memória. Use `id(obj)` para exibi-lo.

- **Exemplo Lúdico:**  
	Imagine que cada criatura mágica ganha uma impressão digital única que nunca muda até ela desaparecer! 🦄🔏

- **Exemplo Prático:**  
```python
	x = 8
	print(id(x))  # e.g. 140730012416664
	x = 12
	print(id(x))  # mudou, pois criou novo objeto
```


## 2. Objetos Imutáveis 🚫🔄
- **Fundamento:**
  Seu conteúdo não pode ser alterado após a criação. Atribuir um novo valor rebind cria um objeto distinto com novo id.

- **Exemplo Lúdico:**
  Pense em uma estátua de gelo: uma vez esculpida, você não pode mudá-la; se quiser outra forma, precisa esculpir um novo bloco! ❄️🗿

- **Exemplo Prático:**
```python
	s = "olá"
	print(id(s))
	s += " mundo"     # cria uma nova string
	print(id(s))      # id diferente
```


## 3. Objetos Mutáveis 🔄✨
- **Fundamento:**
	Seu conteúdo pode ser modificado in-place sem alterar o id do objeto. Alterar um elemento interno não recria o objeto.

- **Exemplo Lúdico:**
	Imagine um balão de borracha que você pode encher ou esvaziar sem trocá-lo: ele continua sendo o mesmo balão! 🎈
	
- **Exemplo Prático:**
```python
	L = [44, 17, 26]
	print(id(L))
	L[0] = 12         # modifica o conteúdo da lista
	print(id(L))      # id permanece igual
```


## 4. Rebinding vs. Mutação 🔀🛠️
- **Fundamento:**
  - Rebinding: nome = outro_objeto associa o identificador a um novo objeto (imutáveis sempre).
  - Mutação: para objetos mutáveis, operações (ex.: append, atribuição a índice) mudam o estado interno sem gerar novo id.

- **Exemplo Lúdico:**
	É como mudar a tampa de um frasco (rebind) versus trocar o líquido dentro do mesmo frasco (mutação)! 🧴

- **Exemplo Prático:**
```python
	a = 5            # imutável
	a = 7            # rebind: novo objeto 7
	L = [1,2,3]      # mutável
	L.append(4)      # mutação: mesmo objeto, nova forma
```


## 5. Classificação no Python Data Model 📑
- **Fundamento:**
	A documentação oficial lista cada classe como imutável ou mutável. Saber essa classificação ajuda a programar sem surpresas.

- **Exemplo Lúdico:**
	Imagine um compêndio mágico que diz quais artefatos são “selados” para sempre (imutáveis) ou “cinéticos” e maleáveis (mutáveis)! 📚🔮
	
- **Exemplo Prático:**
	Consulte na docs Python se tuple (imutável) ou dict (mutável) atende melhor ao seu caso de uso.



## 6. Importância da Distinção 🎯
- **Fundamento:**
	Entender imutabilidade vs mutabilidade é crucial para:
  - Evitar bugs (por exemplo, valores inesperados em listas compartilhadas).
  - Escrever código mais eficiente e previsível.
  
- **Exemplo Lúdico:**
	É como distinguir entre poções que se alteram sozinhas e poções que permanecem eternamente inertes – a escolha certa pode salvar (ou acabar) com sua aventura! 🧙‍♀️🧪

- **Exemplo Prático:**
```python
	def adiciona_item(lst=[]):
		lst.append(1)
		return lst

	print(adiciona_item())  # [1]
	print(adiciona_item())  # [1, 1]  ← lista mutável compartilhada causa efeito-surpresa! 
```

Este aprofundamento no Modelo de Dados de Python mostra como imutabilidade, mutabilidade, rebind e mutação in-place moldam o comportamento dos objetos em memória, garantindo que você crie programas corretos e eficientes! 🚀🐍






