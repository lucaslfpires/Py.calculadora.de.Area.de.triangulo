
# Py.calculadora.de.Area.de.triangulo
def calcular_area_triangulo(base,altura):
area = 0.5 *base*altura
return area
# Exemplo de uso :
base = float(input("digite o valor da base do triangulo :"))
altura = float(input("digite o valor da altura do triangulo:"))

area_triangulo = calcular_area_triangulo(base, altura)
print(f"A area do triangulo com base{base}e altura {altura}e{area_triangulo}")
