# AulasPython1
print("|------------------------------ ----------------------------|")
print("|  Este programa informa qual o valor e quantas parcelas    |")
print("|            será possivel comprar um carro                 |")
print("|--------------------------- -------------------------------|")

print("|    (:   Seja bem vindo a calculadora de parcelas  :)      |") 


print("|          Por favor digite o valor do automovel            |")
valor_automovel = float(input("R$ "))
print("|--------------------------- -------------------------------|")
print("|--------------------------- -------------------------------|")
print ("|      Você gostaria de parcelar em quantas vezes ?         |")
print ("|Lembrando que este programa só aceita numeros como resposta| ")
print ("|      As Unicas opcoes são 0/6/12/18/24/30/42/48/54/60     | ")
print("|--------------------------- -------------------------------|")
parcelar = float(input(" "))

if parcelar==0: 
    valor_final = valor_automovel * 0.2
    valor_parcela = valor_final / 0 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar==6:
    valor_final = valor_automovel * 1.05
    valor_parcela = valor_final / 6 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==12:
    valor_final = valor_automovel * 1.06
    valor_parcela = valor_final / 12 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==18:
    valor_final = valor_automovel * 1.09
    valor_parcela = valor_final / 18 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==24:
    valor_final = valor_automovel * 1.12
    valor_parcela = valor_final / 24 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==30:
    valor_final = valor_automovel * 1.15
    valor_parcela = valor_final / 30 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==36:
    valor_final = valor_automovel * 1.18
    valor_parcela = valor_final / 36 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==42:
    valor_final = valor_automovel * 1.21
    valor_parcela = valor_final / 42 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==48:
    valor_final = valor_automovel * 1.24
    valor_parcela = valor_final / 48 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==54:
    valor_final = valor_automovel * 1.27
    valor_parcela = valor_final / 54 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
elif parcelar ==60:
    valor_final = valor_automovel * 1.30
    valor_parcela = valor_final / 60 
    print ("|O Valor com o juros é:                            | ", valor_final)
    print ("|O Valor da parcela é:                             | ", valor_parcela)
    print("|--------------------------- -------------------------------|")
else: 
    print(" ERRO") 
    
    print("|--------------------------- -------------------------------|")
    print("|----OBRIGADA POR UTILIZAR NOSSO SIMULADOR ONLINE-----------|")  
    print("|--------------------------- -------------------------------|")
