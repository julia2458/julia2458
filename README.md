print ("PROGRAMA PARA CALCULAR ÁREAS DE TRIÂNGULOS")

base = float(input("Digite a medida em CM da base: ")) #INPUT é utilizado para entrada de dados, ee entende, automaticamente, a variável como texto 
altura = float(input("Digite a medida em CM da altura: ")) #FLOAT transforma as varíaveis declaradas em números com casas decimais 

area = base * altura / 2

print("A área calculada vale", area, "CM quadrados ")
print("Obrigada por usar esse programa!")

print ("PROGRAMA PARA CALCULAR EQUAÇAO DO PRIMEIRO GRAU")

print("A equação de primeiro grau é caracterizada pela seguinte fórmula:\n Ax + B = C\n")

A = int(input("Digite o número correspondente ao A: "))
B = int(input("Digite o número correspondente ao B: "))
C = int(input("Digite o número correspondente ao C: "))

X = (C-B)/A

print("\nO valor do X da equação ",A,"x +",B, "=", C, "é:", X)

print("\n\nOBRIGADA POR USAR ESSE PROGRAMA")
