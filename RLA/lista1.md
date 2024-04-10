# Q1
```
# o print aqui
print("Digite o valor da a: ")

# entrada de a
a = input()

# o print aqui
print("Digite o valor da b: ")

# entrada de b
b = input()

# a pro b b pro a
aux = a
a = b
b = aux


# resultado
print("a=", a)
print("b=", b)
```


# Q2
```
# quantidade de notas
print ("digite a quantidade de notas dos alunos")

# input numero de notas
n = int(input())

# quantidade de notas acima de 50
cont = 0

# inicio
i = 1
for i in range(n):
print("Digite a nota do aluno", i, ":")
# receber a nota
nota = int(input())
# checar a nota
if nota >= 50 and nota <= 100:
cont = cont+1

# resultado
print("O numero de alunos aprovados e:", cont)
```



# Q3
```
# o print
print("Digite a quantidade de números /n (n >= 0):")

# quantidade de numeros
n = int(input())

# checar n
if n >= 0:
# somar n
soma = 0
i = i

while(i <= n):
# print
print("Digite um número:")
# receber
num = int(input())
# somatorio
soma = soma +num
i = i+1

# caso if seja falso
else:
print( "O valor deve ser maior ou igual a zero!")

print("A soma dos numeros é" , soma)
```
