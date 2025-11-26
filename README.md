# Atividade.avaliativa03

hile True:
    nota1 = float(input())
    while nota1 < 0 or nota1 > 10:
        print("nota invalida")
        nota1 = float(input())

    nota2 = float(input())
    while nota2 < 0 or nota2 > 10:
        print("nota invalida")
        nota2 = float(input())

    media = (nota1 + nota2) / 2
    print(f"media = {media:.2f}")

    print("novo calculo (1-sim 2-nao)")
    opc = int(input())

    while opc != 1 and opc != 2:
        print("novo calculo (1-sim 2-nao)")
        opc = int(input())

    if opc == 2:
        break
