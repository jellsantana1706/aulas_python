# aulas_python
# Faça uma	função	que calcule a	média	de	um	aluno	de	acordo	com o	critério	definido	neste	curso.	Além	disso,	 faça uma segunda	 função	que	informe	o	status	do	aluno	de acordo	com	a	tabela	a	seguir:
# Nota	acima	de	6	à “Aprovado”
# Nota	entre	4	e	6	à Conceito	“Verificação	Suplementar”
# Nota	abaixo	de	4	à Conceito	“Reprovado”

n1 = float(input('Digite a nota da AV1: '))
n2 = float(input('Digite a nota da AV2: '))
n3 = float(input('Digite a nota da AV3: '))
media = (n1 + n2 + n3) / 3
if media >= 6:
    print('A média do Aluno é: {:.1f}. O aluno está APROVADO'. format(media))
elif media >= 4 and  media < 6:
    print('A média do Aluno é: {:.1f}. O aluno está SOB VERIFICAÇÃO SUPLEMENTAR'. format(media))
else:
    print('A média do Aluno é: {:.1f}. O aluno está REPROVADO'. format(media))
