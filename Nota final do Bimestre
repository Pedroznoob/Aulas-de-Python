# Criação das variáveis by: Pedroznoob
nome = ""
nota_do_bimestre_1 = 0.0
nota_do_bimestre_2 = 0.0
nota_do_bimestre_3 = 0.0
nota_do_bimestre_4 = 0.0
nota_final = float(nota_do_bimestre_1) + float(nota_do_bimestre_2) + float(nota_do_bimestre_3) + float(nota_do_bimestre_4) / 4

# Entrada dos dados
print("****************************************")
print("*             MÉDIA FINAL              *")
print("****************************************")
nome = input("Seu nome: ")
nota_do_bimestre_1 = float(input("Nota do Primeiro Bimestre: "))
nota_do_bimestre_2 = float(input("Nota do Segundo Bimestre: "))
nota_do_bimestre_3 = float(input("Nota do Terceiro Bimestre: "))
nota_do_bimestre_4 = float(input("Nota do Quarto Bimestre: "))

# Processar os valores para obter a Nota Final

nota_final = (float(nota_do_bimestre_1) + float(nota_do_bimestre_2) + float(nota_do_bimestre_3) + float(nota_do_bimestre_4)) / 4
if nota_final >= 7:
    situacao = str('APROVADO')
elif nota_final < 5:
    situacao = str('REPROVADO')
else:
    situacao = str('RECUPERAÇÃO')

# Resultado
print("****************************************")
print(f"*{nome}, sua nota final é: {nota_final}*")
print("****************************************")
if situacao != str('RECUPERAÇÃO'):
    print(f"*{nome}, você foi {situacao} com média {nota_final}")
elif situacao == str('RECUPERAÇÃO'):
    print(f"*{nome}, você ficou de {situacao} com média {nota_final}")
if situacao == str('REPROVADO'):
    print(f'Você precisa de uma média 7.0 para ser aprovado.')
