# Calculadora Simples #
print("\nCalculadora Simples")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")
    
escolha = input("Escolha uma opção: ")
    
if escolha not in ["1", "2", "3", "4"]:
    print("Opção inválida!")
else:
    num1 = float(input("Digite o primeiro número: "))
    num2 = float(input("Digite o segundo número: "))
    
    if escolha == "1":
        print("Resultado:", num1 + num2)
    elif escolha == "2":
        print("Resultado:", num1 - num2)
    elif escolha == "3":
        print("Resultado:", num1 * num2)
    elif escolha == "4":
        if num2 == 0:
            print("Erro: Divisão por zero.")
        else:
            print("Resultado:", num1 / num2)
