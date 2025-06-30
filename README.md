# Primeiros Códigos
Códigos realizados no primeiro semestre da faculdade 

Repositório feito para vizualização dos meus primeiros códigos!

a=float(input("Digite uma nota1: "))
print(type(a))

b=float(input("Digite uma nota2: "))
print(type(b))

c=float(input("Digite uma nota3: "))

media= print(a+b+c)/3





                     SEGUNDO CÓDIGO

minutos =(int(input("Minutos utilizados por mes: ")))
if minutos <= 200:
  precoPorMinuto = 0.20
else:
    if minutos <= 400:
        precoPorMinuto = 0.18
    else:
        if minutos <= 800:
         precoPorMinuto = 0.15
         print(f"Voce vai pagar este mes: R$ {minutos*precoPorMinuto:}")




               TERCEIRO CODIGO

Renda=float(input("valor do salario mensal"))
if Renda < R$ 2259.20
  print("Isento")
  else:
       if R$ 2259.20 > Renda < R$ 2828.65
         print(*0,075)
        else:
              if R$ 2828.65 > Renda < R$ 3751.05
                print(*0,15)
              else:
                   if R$ 3751.05 > Renda < R$ 4664.68
                      print(*0,225)
                    else:
                         if Renda < R$ 4664.68
                           print(*0,275) 



                       
                       QUARTO CÓDIGO              

 A= int(input("Digite o numero da linha:"))
A=8
B=int(input("Digite o numero da coluna:"))
B=8
if (A+B)% 2==0:
 print(0, "casa preta")
else:
 print(1,"casa branca")    




                         QUINTO CÓDIGO     

A= int(input("Digite o numero da carta1:"))
B=int(input("Digite o numero da carta2:"))
C=int(input("Digite o numero da carta3:"))
if A==B:
    print("O valor da carta4 é",C)
else:
    if A==C:
        print("O valor da carta4 é",B)
    else:
        if B==C:
            print("O valor da carta4 é",A)




                         SEXTO CÓDIGO       

media= float(input("Digite a média do aluno: "))
if media >10:
    print("Erro no sistema")
elif media >= 9.0:
    print("A")
elif media >= 8.0:
    print("B")
elif media >= 7.0:
    print("C")
elif media >= 6.0:
    print("D")
else:
    print("R")




                        SETIMO CÓDIGO

print("-"*35)
print("101 - Batata List - R$4.50")
print("305 - Suco Py - R$2.00")
print("248 - Suco Interpretado - R$4.25")
print("389 - Guaraná Lambda - R$3.50")
print("145 - Sanduiche Integral - R$9.00")
print("567 - Cerveja Derivada - R$8.50")
print("673 - Vitamina Compilada - R$7.80")
print("-"*35)
produto = int(input("Escolha seu produto: "))
if produto == 101:
    print("Batata List - R$4.50")
elif produto == 305:
     print("Suco Py - R$2.00")
elif produto == 248:
     print("Suco Interpretado - R$4.25")
elif produto == 389:
     print("Guaraná Lambda - R$3.50")
elif produto == 145:
     print("Sanduiche Integral - R$9.00")
elif produto == 567:
     print(" Cerveja Derivada - R$8.50")
elif produto == 673:
     print("Vitamina Compilada - R$7.80")
else:
    print("Produto não encontrado")     




                        OITAVO CÓDIGO

jogador1= input("Você quer ser X ou O?")
if jogador1 == "X" or "x":
    print("Jogador 1: X \nJogador 2: O")
elif jogador1 == "O" or "o":
    print("Jogador 1: O \nJogador2: X")
else:
    print("Escolha X ou O")




                        NONO CÓDIGO

n1=int(input("Digite um número:"))
n2=int(input("Digite um número:"))
n3=int(input("Digite um número:"))
if n3 > n1 and n2 > n1:
    print("esse número é ascendente")
else:
    print("esse número não é ascendente")




                         DECIMO CÓDIGO

print("-"*35)
print("101 - Batata List - R$4.50")
print("305 - Suco Py - R$2.00")
print("248 - Suco Interpretado - R$4.25")
print("389 - Guaraná Lambda - R$3.50")
print("145 - Sanduiche Integral - R$9.00")
print("567 - Cerveja Derivada - R$8.50")
print("673 - Vitamina Compilada - R$7.80")
print("-"*35)
produto = int(input("Escolha seu produto: "))
if produto == 101:
    print("Batata List - R$4.50")
    semErro = True
elif produto == 305:
     print("Suco Py - R$2.00")
     semErro = True  
elif produto == 248:
     print("Suco Interpretado - R$4.25")
     semErro = True
elif produto == 389:
     print("Guaraná Lambda - R$3.50")
     semErro = True
elif produto == 145:
     print("Sanduiche Integral - R$9.00")
     semErro = True
elif produto == 567:
     print(" Cerveja Derivada - R$8.50")
     semErro = True
elif produto == 673:
     print("Vitamina Compilada - R$7.80")
     semErro = True
else:
     print("Produto não encontrado")




                         Décimo Primeiro Código   

from math import log, ldexp , sqrt ,e

x = float(input("Digite um valor:"))

if x <= 1:
    resultado = log(x)
elif x > 1 or x <= 2:
    resultado = log(x,10) + sqrt(x)
elif x > 2 or x <= 5:
    resultado = ldexp(x**2) +(e**x)
elif x > 5:
    resultado = ldexp(x**x/2) + log(x,2)

print(resultado)      




                        Décimo Segundo Código

def mensagem():
    print("Minha função feita em Python.")
    print("Esse é um exemplo de função sem parâmetro e sem retorno.")

    def mensagemRepetida(n):
        for _ in range (n):
            mensagem()




                        Décimo Terceiro Código

def converter(segundos):
    horas = segundos // 3600
    minutos = (segundos % 3600) // 60
    segundos_restantes = segundos % 60
    
def main():
    segundos = int(input("Digite o número de segundos: "))
    converter(segundos)
    horas = segundos // 3600
    minutos = (segundos % 3600) // 60
    segundos_restantes = segundos % 60
    print(f"{horas} horas, {minutos} minutos e {segundos_restantes} segundos")
if __name__ == "__main__":
    main()




                        DÉCIMO QUARTO CÓDIGO

from math import factorial

def combinacao(C, n, p):
    if p > n:
        return 0
    return factorial(n) // (factorial(p) * factorial(n - p)) == C

def main():
    n = int(input("Digite o valor de n: "))
    p = int(input("Digite o valor de p: "))
    
    if n < 0 or p < 0:
        print("Valores negativos não são permitidos.")
    else:
        resultado = combinacao(n, p)
        print(f"O valor de C({n}, {p}) é: {resultado}")

main()




                        DÉCIMO QUINTO CÓDIGO

def soma1():
    x = float(input("Digite um número: "))
    y = float(input("Digite outro: "))
    return x+y

def soma2(x, y):
    return x+y

def main():
    resultado1 = soma1()
    print(f"Resultado da soma:{resultado1}")

    a = float(input("Digite um número: "))
    b = float(input("Digite outro: "))
   
    resultado2 = soma2(a,b)
    print(f"Resultado da soma: {resultado2}")

main()




                        DÉCIMO SEXTO CÓDIGO

def soma3(x, y):
    print("Chegou aqui!")
    return x + y

def main():    
    x = float(input("Digite um valor:"))
    y = float(input("Digite outro valor:"))
    
    resultado3 = soma3(x,y)
    print(f"resultado: {resultado3}")

main()




                        DÉCIMO SETIMO CÓDIGO

def divisivel(x, y):
  return "Par" if x%y == 0 else y==1

def main():
    
    x = float(input("Digite um valor:"))
    y= float (input("Digite outro valor"))
    resultado1 = divisivel(x,y)
    print(f"Resultado: {resultado1}")

main()




                        DÉCIMO OITAVO CÓDIGO

def fatorial(n):
    return 1 if n == 0 or n == 1 else n*fatorial(n-1)

def main():
    n = 2
    print(f"{n}! = {fatorial(n)}")

    #n = -2
    #print(f"{n}! = {fatorial(n)}")

main()




                        DÉCIMO NONO CÓDIGO

def imprime(M, x = 1):
    if x > M:
             return
    print(x)
    imprime(M, x + 1)
       

imprime(5)