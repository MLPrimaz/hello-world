# hello-world
O Comando introdutório universal para qualquer linguagem de programação é conhecido como **Hello World**, tem esse nome pois consiste em fazer aparecer na tela do computador essa mensagem.
Em Python esse comando se escreve assim:

```Python
  print("Hello, World!")
```

Em uma linguagem mais informal dizemos que o comando print "IMPRIME" na tela do computador o texto *Hello, World*.
Usando a linguagem Python para tentar explicar, dizemos que estamos usando a função print para imprimir a string *Hello, World* na console do terminal.

Como poderá ser percebido, uma **string** é uma **sequência de caracteres** dentre uma marcação por aspas simples `'isso é uma string'` ou aspas duplas `"outra string"`, que na maioria das vezes poderá ser interpretado como texto, podemos afirmar que  **qualquer texto é uma string, mas strings não se limitam a ser somente texto ;-)**. Se isso ficou compreendido basta me dar um retorno de 'OK'. #faz_com_python


```Python
  print("OK")`
```

Para executarmos o **Hello, World!**, na grande maioria das linguagens, fazemos uso do que se convencionou chamar de funções.`print()` é uma função do Python. E sua "**função**", como já visto, é colocar um texto na tela do computador.

`print()`, de longe, é a função mais usada por quem está aprendendo a programar em Python, mas é apenas a primeira de várias funções que usaremos nessa linguagem, **ame funções!**, sem funções programar seria uma tortura, pode acreditar, não há linguagens de programação que não use funções.

Deu para perceber que funções são algo muito importante em programação?



# def mensagem_ok()
Lembra do `print("OK")`? Em resumo podemos dizer que se colocarmos um caracter/texto, entre aspas (`' '` ou " "), entre os parentes da função `print()`, este caracter/texto será impresso na tela/console do computador. Não deve ser mais novidade nesse ponto. Que tal criarmos nossa própria funcão para termos uma idéia de como as funções funcionam.

No início do nosso arquivo colocaremos os seguintes comandos:

```Python
  def mensagem_ok():
      return "OK"

  #Programa principal
  print(mensagem_ok())
```

Percebeu que o resultado foi idêntico ao `print("OK")`? Isso aconteceu porque criamos uma função que retorna (`return`) a **string** `"OK"`. Podemos dizer que se uma função retornar uma string - "texto" - faz sentido podermos "imprimir" esse retorno na console com a função `print()`, não faz?

Esse exemplo, por ser simples, tem sentido apenas didático, pois acabamos digitando mais código para fazer a mesma coisa.
Mas façamos uma pequena alteração e começaremos a entender um pouco mais sobre o poder das funções.

```Python
def saudacao(nome):
    return nome + ", seja bem vindo ao curso de Python."
    
    
#Programa principal
print(saudacao("Misael")
```

Essa pequena modificação já nos dá o direito de dizer que nossa função saudação pode retornar um número muito grande de mensagens distintas, pois para cada nome distinto colocado na chamada da função `saudacao(nome)` retornaria uma mensagem também distinta.


```Python
def saudacao(nome):
    return nome + ", seja bem vindo ao curso de Python."
    
    
#Programa principal
print(saudacao("Misael")
print(saudacao("Valentina")
print(saudacao("Pedro Henrique")
```

A título de curiosidade vou mostrar como seria feito sem o uso de funções:

```Python
   
#Programa principal
print("Misael, seja bem vindo ao curso de Python.")
print("Valentina, seja bem vindo ao curso de Python.")
print("Pedro Henrique, seja bem vindo ao curso de Python.")
```
Temos o mesmo resultado, mas note como tivemos que repetir várias vezes algo que já haviamos digitado. Essa percepção já é um indício de que que o código está pedindo uma função, estamos repetindo coisas que podem ser automatizadas.

Fizemos algo diferente nessa função que ainda não haviamos feito, juntamos dois pedaços de textos através do operador `+`, 
