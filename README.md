# BMI
BMI calculation

altura = float (input("Digite a sua altura: "))

peso = float (input("Digite o seu peso: "))

idade = int (input("Digite a sua idade: "))


imc = peso/(altura*altura)

print(f"o seu IMC é igual a: {imc: .2f} e a sua idade é igual à: {idade}")
