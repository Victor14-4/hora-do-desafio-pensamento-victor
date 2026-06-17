# hora-do-desafio-pensamento-victor

## Desafio: Controle de Ingressos para um Evento Escolar

Imagine que você está ajudando a organizar um evento em sua escola que possui 100 ingressos disponíveis para alunos, monitores e convidados.

Para que tudo ocorra bem, é necessário garantir que o número total de pessoas não ultrapasse a quantidade de ingressos disponíveis. Além disso, a direção da escola impôs uma regra: é permitido haver, no máximo, 20 convidados no total, mesmo que sobrem ingressos.

### codigo:

### Exemplo de Solução em Python
alunos = int(input("Digite a quantidade de alunos: "))
monitores = int(input("Digite a quantidade de monitores: "))
convidados = int(input("Digite a quantidade de convidados: "))

total = alunos + monitores + convidados

if total <= 100:
    print("Há ingressos suficientes para todos.")
else:
    print("O número de pessoas ultrapassa a quantidade de ingressos disponíveis.")

if convidados <= 20:
    print("O número de convidados está dentro do limite permitido.")
else:
    print("O número de convidados ultrapassa o limite permitido.")
