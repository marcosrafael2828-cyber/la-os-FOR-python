# 
impar = int(input("Digite um número: "))
for i in range(1,impar+1):
 if (i % 2 == 1):
  print(i)

# media de idade
from ast import And
media_id = 0
total = 0
media = 0

for i in range(10):
  idade = int(input("digite sua idade: "))
  sexo = input("digite seu sexo M/F: ")
  total = total + idade

  if (idade >= 20 and idade <= 40 ) and (sexo == "f" or  sexo == "F"):
      media_id = media_id + 1

media = total / 10
print("a o numero de mulhores com a idade entre 20 e 40 anos e de ",media_id)

# bh
lista=[]
for i in range(10):

  tempo=float(input("digite a temperatura "))
  lista.append(tempo)
  print("numeros da temperatura ",lista)
menor = lista[0]
maior = lista[0]

for tempo in lista:
    if (tempo > maior):
        maior = tempo
    if (tempo < menor):
        menor = tempo
print("maior valor", maior)
print("menor valor", menor)

print("a maior temperatura em BH no dia 01/01/25 foi de ",maior,"graus")
print("a menor temperatura em BH no dia 01/01/25 foi de ",menor,"graus")

#fatorial
n1=int(input("digite um numero: "))
def calcular_fatorial(n1):
 result=1
 for i in range(1, n1 + 1):
    result *= i
 return result
print(calcular_fatorial(n1))

#fatorial digitado 

num1=int(input("digite um numero: "))
num2=int(input("digite o segundo numero: "))
resultado=1
for i in range(num2):
    resultado = resultado * num1
print(resultado)

#homens e mulheres
qtd_mulhres=0
qtd_homens=0

for i in range(10):
  sexoo=input("digite seu sexo M/F: ")
  pesoo=float(input("digite seu peso: "))
  
  if ( sexoo == "f" or sexoo == "F") and ( pesoo >= 50 and pesoo <=70 ):
   qtd_mulhres = qtd_mulhres+ 1
  
  elif( sexoo == "m" or sexoo =="M") and ( pesoo >= 60 and pesoo <=80 ):
   qtd_homens =  qtd_homens + 1
 
print("o numero de mulheres que pesam entre 50KG e 70KG e de " ,qtd_mulhres)
print("o numero de homens que pesam entre 60KG e 80KG e de " ,qtd_homens)

# media notas
media_notas=
alunos=0
for i in range(3):
   nota=float (input("digite a nota do aluno "))
   nota2=float(input("digite a segunda nota "))
   soma=nota+nota2
   alunos=alunos+1
  
   media_notas = soma / 2
   print("a media do aluno ", alunos , "foi de", media_notas)
 
 
 #maior e menor nota 

 lista=[]

for i in range(5):
 notas=float(input("digite a notas dos alunos "))
 lista.append(notas)
maior_nota=lista[0]
menor_nota=lista[0]
 
for notas in lista:
   if (notas > maior_nota):
     maior_nota=notas
   if (notas < menor_nota):
     menor_nota=notas
print("a maior nota foi de ",maior_nota)
print("a menor nota foi de ",menor_nota)










