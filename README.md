"""
CALCULADORA VERSÃO 1.0
"""

tema  = "$%$%$%$%$%$%$% Bem Vindo a Calculadora DSG $%$%$%$%$%$%$"
print(tema)
print("Digite por favor uma das opções a seguir: \n 1)Soma: \n 2) Subtração: \n 3)Multiplicação: \n 4)Divisão: \n")
valor_usu = int(input("O que deseja executar?"))
while valor_usu >4:
    print("Valor inválido, por favor escolha uma das opções listadas.")
    valor_usu = int(input("O que deseja executar?"))
    if valor_usu <= 4:
        pass

primeiro_valor = int(input("Digite seu primeiro número:"))
segundo_valor = int(input("Agora, por favor digite seu próximo número:"))
if valor_usu == 1:
    print("A soma dos seus valores é:", primeiro_valor + segundo_valor)
elif valor_usu == 2:
    print("A subtração dos seus valores é:", primeiro_valor - segundo_valor)
elif valor_usu == 3:
    print("A Multiplicação dos seus valores é:", primeiro_valor * segundo_valor)
elif valor_usu == 4:
    print("A Divisão dos seus valores é:", primeiro_valor / segundo_valor)

print("Muito Obrigado por usar nossa Calculadora, Volte Sempre que quiser!")

#foi de novo

#foi

#print(hello people)
## hoje flusão perde
*novo comando




 
