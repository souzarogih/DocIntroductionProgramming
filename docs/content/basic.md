### **COMANDOS BÁSICOS**

#### **PRINT**

>Função print()
``` python
print()
```
>>$

# 

>Função print com um argumento
``` python
print(’Meu nome é arretado!’)
```
>>Meu nome é arretado!

# 

#### **INPUT**

>Função input()
``` python
nome = input("Digite o seu nome: ")
```
>>Digite o seu nome: 

<p>
A função input recebe como argumento um valor em string que será mostrado ao usuário, e também retorna um valor string.
</p>


#### **ESTRUTURAS DE REPETIÇÃO**

<p>
As estruturas de repetição são usadas para executar um bloco de código várias vezes. Elas nos ajudam a evitar repetir o mesmo código várias vezes manualmente. Existem dois tipos principais de estruturas de repetição em Python: o "for" e o "while".
</p>


#### **FOR**

<p>
O "for" é usado quando sabemos antecipadamente quantas vezes queremos repetir um bloco de código. Podemos percorrer uma lista, uma sequência de números ou até mesmo uma string. Aqui está um exemplo:
</p>

>Função For
```python
frutas = ["maçã", "banana", "laranja"]

for fruta in frutas:
    print(fruta)
```

#

<p>
Nesse exemplo, o bloco de código dentro do "for" será executado três vezes, uma vez para cada elemento da lista "frutas". A variável "fruta" irá assumir o valor de cada elemento a cada iteração.
</p>


#### **WHILE**

<p> 
O "while" é usado quando não sabemos quantas vezes queremos repetir um bloco de código e a repetição é baseada em uma condição. O bloco de código será repetido até que a condição não seja mais verdadeira. Aqui está um exemplo:
</p>

>Função While
```python
contador = 0

while contador < 5:
    print(contador)
    contador += 1
```

<p>
Nesse exemplo, o bloco de código dentro do "while" será repetido enquanto a variável "contador" for menor que 5. A cada iteração, o valor de "contador" será incrementado em 1.
</p>


#### **BREAK E CONTINUE**

<p>
Break e Continue:
O "break" e o "continue" são palavras-chave que podemos usar dentro das estruturas de repetição para controlar o fluxo do programa.
O "break" é usado para interromper completamente o loop. Se uma condição for atendida, o loop será encerrado imediatamente. Aqui está um exemplo:
</p>

>Função Break
```python
numeros = [1, 2, 3, 4, 5]

for numero in numeros:
    if numero == 3:
        break
    print(numero)
```
<p>
Nesse exemplo, quando o valor de "numero" for igual a 3, o "break" será acionado e o loop será interrompido.

O "continue" é usado para pular a iteração atual do loop e ir para a próxima. Se uma condição for atendida, o código abaixo do "continue" na iteração atual será ignorado. Aqui está um exemplo:
</p>

>Função Continue
```python
numeros = [1, 2, 3, 4, 5]

for numero in numeros:
    if numero == 3:
        continue
    print(numero)
```

<p>
Nesse exemplo, quando o valor de "numero" for igual a 3, o "continue" será acionado e o código abaixo dele naquela iteração será ignorado. O loop continuará com a próxima iteração.
</p>

<p>
As estruturas de repetição são muito úteis na programação, pois nos permitem executar tarefas repetitivas de maneira eficiente. O "for" é usado quando sabemos quantas vezes queremos repetir um código, enquanto o "while" é usado quando a repetição depende de uma condição. O "break" nos permite sair de um loop antes de completá-lo e o "continue" nos permite pular uma iteração e continuar com a próxima. Espero que essas explicações tenham sido úteis!
</p>