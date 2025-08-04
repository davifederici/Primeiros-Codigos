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




                        VIGÉSIMO CÓDIGO

def imprime( n , m ):
    if n > m:
             return
    print(n)
    imprime( n + 1 , m )
       

imprime( 5 , 10 )





                        VIGÉSIMO PRIMEIRO CÓDIGO

def f1(n, m):
    if n <= m:
        print(n)
        f1(n + 1, m)

def f2(n, m):
    if n > m:
        return
    else:
        print(n)
        f2(n + 1, m)

def f3(n, m):
    print(n)
    if n == m:
        return None
    f3(n + 1, m)

def f4(n, m):
    print(n)
    if n != m:
        f4(n + 1, m)

def f5(n, m):
    if n <= m:
        f5(n + 1, m)
        print(n)

def main():
    print("f1(0, 10)")
    f1(0, 10)

    print("f2(0, 10)")
    f2(0, 10)

    print("f3(0, 10)")
    f3(0, 10)

    print("f4(0, 10)")
    f4(0, 10)

    print("f5(0, 10)")
    f5(0, 10)

main()




                        VIGÉSIMO SEGUNDO CÓDIGO

def f1(n):
    if n % 2 == 0:
        return 
        1 + f1(n - 2)
        print(n)
    else:
        return f1(n - 1) #Por que n - 1?
        print(n)
        f1(n - 1)
        
def f2(n):
    if n >= 1:
        return 
    else:
        print(n)
        n + f2(n + 1)

def main():
    print("f1(10)")
    f1(10)
    
    print("f2(5)")
    f2(5)
    
main()




                        VIGÉSIMO TERCEIRO CÓDIGO

def bx(n):
    if n == 0:
        return 0 
    else :
        return n%2 +10*bx(n//2)
def main():
    print(bx(3))
    print(bx(10))
    print(bx(4))
    print(bx(10000000000000000000000000))
main()




                        VIGÉSIMO QUARTO CÓDIGO

def eh_primo(n, i=2):
    if n <= 1:
        return False
    if i * i > n:
        return True
    if n % i == 0:
        return False
    return eh_primo(n, i + 1)

def verificar_lista(lista, idx=0):
    if idx == len(lista):
        return 
    numero = lista[idx]
    if eh_primo(numero):
        print(f"{numero} é primo.")
    else:
        print(f"{numero} não é primo.")
    verificar_lista(lista, idx + 1)  

def main():
    numeros = [2, 3, 8]
    verificar_lista(numeros)

main()




                        VIGÉSIMO QUINTO CÓDIGO

def b(n):
    if not isinstance(n, int) or n < 0:
        print("ERRO: O argumento deve ser inteiro positivo")
        return None
    if n == 0:
        return "0"
    if n == 1:
        return "1"
    return b(n // 2) + str(n % 2)

def main():
    numero = int(input("Digite um número natural: "))
    binario = b(numero)
    if binario is not None:
        print(f"Representação binária: {binario}")

main()




                        VIGÉSIMO SEXTO CÓDIGO

def M(a, b):
    if not isinstance(b, int) or b < 0:
        print("ERRO")
        return
    elif b == 0:
        return 0
    elif b == 1:
        return a
    else:
        return a + M(a, b - 1)

def DI(a, b):
    if not isinstance(a, int) or not isinstance(b, int) or a < 0 or b <= 0:
        print("ERRO")
        return
    elif a < b:
        return 0
    else:
        return 1 + DI(a - b, b)

def RD(a, b):
    if not isinstance(a, float) or not isinstance(b, float) or b <= 0:
        print("ERRO")
        return
    elif a < b:
        return a
    else:
        return RD(a - b, b)

def main():
    print(M(2, 3))
    print(M(3, 2))

    print(M(4, 2))

    print(DI(2, 3))
    print(DI(3, 2))
    print(DI(4, 2))
    print(DI(10, 6))

    print(RD(2.0, 3.0))
    print(RD(3.0, 2.0))
    print(RD(25.5, 10.5))

main()




                        VIGÉSIMO SÉTIMO CÓDIGO

def f1(n):
    
    if not isinstance(n, int) or n < 1:
        print("ERRO: n deve ser inteiro positivo")
        return None
    if n == 1:
        return 1
    return n + f1(n - 1)

def imprimeSoma_recursivo(k, m):
   
    if k >= m:
        return
    soma = f1(k)
    print(f"Soma de 1 até {k} = {soma}")
    imprimeSoma_recursivo(k + 1, m)

def imprimeSoma(m):

    if not isinstance(m, int) or m < 1:
        print("ERRO: m deve ser inteiro positivo")
        return
    imprimeSoma_recursivo(1, m)

def main():

    print("Testes da função f1:")
    print(f"f1(5) = {f1(5)}")

main()




                        VIGÉSIMO OITAVO CÓDIGO

def desenha1(n, c="*", i=1):
    if i <= n:
        print(c * n)
        desenha1(n, c, i + 1)

def desenha2(n, c="*", i=1):
    if i <= n:
        print(c * i)
        desenha2(n, c, i + 1)

def desenha3(n, c="*", i=1):
    if n % 2 == 0:
        print("n deve ser ímpar")
        return
    if i <= n:
        ne = (n - i) // 2
        print(" " * ne + c * i)
        desenha3(n, c, i + 2)

def main():
    print("desenha1(10):")
    desenha1(10)

    print("\ndesenha2(5):")
    desenha2(5)

    print("\ndesenha3(7):")
    desenha3(7)

main()




                        VIGÉSIMO NONO CÓDIGO

from os import system, name

def limpaTela():
    if name == 'nt':
        system('cls')
    else:
        system('clear')

def telaAbertura():
    print("Seja bem-vindo")
    input("Pressione uma tecla para continuar...")

def leValor(funcaoConversao, msgInput="", msgErro="ERRO: Valor inválido"):
    try:
        return funcaoConversao(input(msgInput))
    except:
        print(msgErro)
        return leValor(funcaoConversao, msgInput, msgErro)

def deposito(saldo, estoque):
    limpaTela()
    print("Depósito de notas (apenas R$ 20, R$ 50, R$ 100)")

    qtd_100 = leValor(int, "Quantidade de notas de R$100: ", "Valor inválido")
    qtd_50 = leValor(int, "Quantidade de notas de R$50: ", "Valor inválido")
    qtd_20 = leValor(int, "Quantidade de notas de R$20: ", "Valor inválido")

    valor = (qtd_100 * 100) + (qtd_50 * 50) + (qtd_20 * 20)

    if valor > 0:
        saldo += valor
        estoque[100] += qtd_100
        estoque[50] += qtd_50
        estoque[20] += qtd_20
        print(f"Depósito de R${valor:.2f} realizado com sucesso.")
    else:
        print("Nenhuma nota depositada. Tente novamente!")

    input("Pressione Enter para continuar...")
    return saldo, estoque

def saque(saldo, estoque):
    limpaTela()
    valor = leValor(float, "Valor a sacar: R$ ", "Valor inválido")
    if valor > 0:
        if valor <= saldo:
            saldo -= valor
            print(f"Saque de R${valor:.2f} realizado com sucesso.")
        else:
            print("Saldo insuficiente.")
    else:
        print("O valor do saque deve ser positivo.")
    input("Pressione Enter para continuar...")
    return saldo, estoque

def exibirEstoque(estoque):
    limpaTela()
    print("Estoque de notas no caixa:")
    print(f"Notas de R$100: {estoque[100]}")
    print(f"Notas de R$50 : {estoque[50]}")
    print(f"Notas de R$20 : {estoque[20]}")
    input("Pressione Enter para continuar...")

def caixaEletronico(saldo=0, estoque=None):
    if estoque is None:
        estoque = {100: 0, 50: 0, 20: 0}

    limpaTela()
    print("===== CAIXA ELETRÔNICO =====")
    print("1 - Depósito")
    print("2 - Saque")
    print("3 - Saldo")
    print("4 - Estoque de notas")
    print("5 - Sair")

    opcao = leValor(int, "Digite uma opção: ", "A opção deve ser um número inteiro.")

    if opcao == 1:
        saldo, estoque = deposito(saldo, estoque)
        caixaEletronico(saldo, estoque)  # chamada recursiva
    elif opcao == 2:
        saldo, estoque = saque(saldo, estoque)
        caixaEletronico(saldo, estoque)  # chamada recursiva
    elif opcao == 3:
        limpaTela()
        print(f"Saldo atual: R${saldo:.2f}")
        input("Pressione Enter para continuar...")
        caixaEletronico(saldo, estoque)  
    elif opcao == 4:
        exibirEstoque(estoque)
        caixaEletronico(saldo, estoque)  
    elif opcao == 5:
        print("Finalizando... Obrigado por usar nosso caixa eletrônico!")
        exit()
    else:
        print("Opção inválida!")
        input("Pressione Enter para continuar...")
        caixaEletronico(saldo, estoque)  

def main():
    limpaTela()
    telaAbertura()
    caixaEletronico()

main()




                        TRIGÉSIMO

def myRange1(n, L=[], i=0):
    if i == n:
        return L + [i]
    else:
        return myRange1(n, L + [i], i+1)   

L = myRange1(10)
print(L)




                        TRIGÉSIMO PRIMEIRO

def myRange2(b, a=1):
    if a > b:
        return []
    else:
        return [a] + myRange2(b , a + 1)
    return L

b = int(input("numero b : "))
L = myRange2(b)
print(L)




                        TRIGÉSIMO SEGUNDO

def myRange3(n, L=[], i=2, s=2):
    if i > n:
        return L 
    else:
        return myRange3(n, L + [i], i+2)   

L = myRange3(s = [2],n = 10,i = 2)
print(L) 




                        TRIGÉSIMO TERCEIRO

def imprime(L=[], i = 0 ):
    if i < len(L):
        print(L[i])
    imprime(L, i + 2)




                        TRIGÉSIMO QUARTO

def imprime(L=[], i=1):
    if i < len(L):
        return imprime(L, i + 1)
        print(L[i])
    else:
        return [i == 2] 
        print(False)    
        imprime(L, i + 1)




                        TRIGÉSIMO QUINTO

def soma(L, i=0):
    if i < len(L):
        return L[i] + soma(L, i + 1)
    return 0




                        TRIGÉSIMO SEXTO

def soma(lista, i=0):
    if not all(isinstance(x, str) for x in lista):
        raise TypeError("Todos os elementos da lista devem ser strings.")
    
    if i == len(lista) - 1:
        return lista[i]
    return lista[i] + soma(lista, i + 1)




                        TRIGÉSIMO SÉTIMO

def todosNumeros(n,L=[], i=0):
    if i == n:
        n = float(input("Digite um número: "))
        return True
        print("True")
    else:
        return False 
        print("False")




                        TRIGÉSIMO OITAVO

