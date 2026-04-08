while True: 
    welcome = input(" bem vindo a calculadora do samuel, deseja iniciar? (s/n): ")
    if welcome.lower() != "s":
        print("calculadora encerrada")
        break
    numero1 = int(input("digite um numero: "))
    operador = input("digite um operador matematico: ")
    numero2 = int(input("digite outro numero:  "))
    
    if operador == "+":
        print(numero1 + numero2)
    elif operador == "-":
        print(numero1 - numero2)
    elif operador == "*":
        print(numero1 * numero2)
    elif operador == "/":
        print(numero1 / numero2)
    else:
        print("operador invalido")
    continuar = input("deseja continuar? (s/n):  ")
    if continuar.lower() != "s":
     print("calculadora encerrada")
     break