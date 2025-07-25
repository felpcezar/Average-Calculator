nome = ""
nota1 = 0.0
nota2 = 0.0
nota3 = 0.0
nota4 = 0.0

nome = input("Nome do aluno:")
nota1 = float(input("Nota 1º bimestre: "))
nota2 = float(input("Nota 2º bimestre: "))    
nota3 = float(input("Nota 3º bimestre: "))
nota4 = float(input("Nota 4º bimestre: "))

media = (nota1 + nota2 + nota3 + nota4) / 4

if media >= 5.0:
    print(f"Parabéns! Aluno(a): {nome} aprovado com média {media:.2f}")
else:
    print(f"Aluno(a): {nome} reprovado com média {media:.2f}")

print("Fim do programa!\n")
print("Obrigado por utilizar nosso sistema!")


