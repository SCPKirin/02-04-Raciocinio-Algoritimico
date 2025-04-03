# Joguinho de escolhas #

print("Você está em uma floresta perdido. Escolha entre o caminho da esquerda e o caminho da direita")
print("1 - Caminho da esquerda")
print("2 - Caminho da direita")

escolha = input("Qual caminho você escolhe? (1 ou 2): ")

if escolha == '1':
    print("Voce encontrou um rio. Quer atravessar o rio?")
    print("1 - Sim")
    print("2 - Não")
    if input("Escolha (1 ou 2): ") == '1':
        print("Voce atravessou o rio e encontrou uma cidade! ")
    else: 
        print("Voce decidiu continuar na floresta e se perdeu mais e mais dentro da mata...")
        
elif escolha == '2':
    print("Voce ve uma montanha a sua frente. Quer tentar subi-la?")
    print("1 - Sim")
    print("2 - Não")
    if input("Escolha (1 ou 2): ") == '1':
        print("Voce chegou ao topo e enxergou uma cidade proxima a voce!")
    else: 
        print("Voce decidiu nao escalar e se perdeu mais e mais dentro da mata...")