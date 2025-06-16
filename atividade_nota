# atividade_nota
numero_de_alunos = int(input("digite seu numero:"))

media_do_aluno = 0 

for i in range (numero_de_alunos):
    print(f"\nAluno {i+1}")
    nome = input("nome do aluno:")

nota1 = float(input("Digite sua primeira nota:"))
nota2 = float(input("Digite sua segunda nota:"))
nota3 = float(input("Digite sua Terçeira nota:"))

mediana = (nota1 + nota2 + nota3) / 3 

media_do_aluno += mediana

if mediana >= 7.0:
    situação = "Aprovado"
else:
    situação = "Reprovado"

    print(f"\nNome:{nome}")
print(f"Notas: {nota1},{nota2},{nota3}")
print(f"Média:{mediana:.2f}")
print(f"Situação: {situação}")

media_geral = media_do_aluno / numero_de_alunos
print(f"\nMédia geral da turma: {media_geral:.2f}")
