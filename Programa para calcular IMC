# Programa para calcular IMC by: Pedroznoob
# Desenvolvido por Celso
print("****************************************")
print("*         CALCULADORA DE IMC          *")
print("****************************************")
print()

# Criação das Variáveis
nome = ""
peso = 0
altura = 0.0
imc = 0.0

# Entrada dos dados
print("Digite seu nome")
nome = input(": ")
print("Digite seu peso")
print("Exemplo: 80")
peso = float(input(": "))
print("Digite sua altura")
print("Exemplo: 1.90")
altura = float(input(": "))

# Processar os valores para obter o IMC
imc = float(peso) / float(altura) ** 2

# Classificação do IMC
if imc < 16:
    classificação = "Magreza grave"
elif imc >= 16 and imc < 17: 
        classificação = "Magreza moderada"
elif imc >= 17 and imc < 18.5:
        classificação = "Magreza leve"
elif imc >= 18.5 and imc < 25:
        classificação = "Saudável"
elif imc >= 25 and imc < 30:
        classificação = "Sobrepeso"
elif imc >= 30 and imc < 35:
        classificação = "Obesidade Grau I"
elif imc >= 35 and imc < 40:
        classificação = "Obesidade Grau II (considerada severa)"
else:
    classificação = "Obesidade Grau III (considerada mórbida)"

# Resultado
print("****************************************")
print("*               RESULTADO              *")
print("****************************************")
print("*                                      *")
print(f"NOME: {nome}")
print(f"PESO: {peso:.2f}kg")
print(f"ALTURA: {altura:.2f}m")
print(f"*Seu IMC é: {imc:.2f}")
print("****************************************")
print ("Classificação do IMC")
print (f"{classificação}")
