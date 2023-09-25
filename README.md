# Primer taller de INDUSPLAYTHON 👽

## Logo:

![](https://raw.githubusercontent.com/nisaespa/Taller1/main/logoindusplaython.png)

## 1. Realice el quiz Python Beginner Quiz (20 preguntas) y adjunte pantallazo con el resultado (mínimo 90% bien).

+ Adjuntamos pantallazo, nos quedo el 90% bien ✓.
  
![](https://raw.githubusercontent.com/nisaespa/Taller1/main/punto1quizpython.jpg)

## 2. Realice un programa que lea tres números reales y determine cuál es el mayor.
+ En el desarrollo del segundo punto posterior a convertir un string a flotante, usamos los condiciionales: "If, elif y else" para determinar cual es el mayor mediante el código.

```python
N = float(input("ingrese un numero real: "))
b =  float(input("ingrese un numero real: "))
c =  float(input("ingrese un numero real: "))


if N > b and N > c:
  print("el maximo es: ",N)
 
elif b > N and b > c :
  print("el maximo es: ",b)
  
else:
       print("el maximo es: ",c)
```
## 3. Realice un programa que lea un número enteros y determine si es par o impar.
+ En el desarrollo del tercer punto unicamente se usan dos de los condicionales anteriormente nombrados después de convertir un string a flotante.

```python
numero = int(input("Ingrese un número entero: "))
if numero % 2 == 0:
    print("es un número par.")
else:
    print("es un número impar.")

```
## 4. Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.
+ El siguiente es el desarrollo del cuarto punto.

```python
a = float(input("ingrese un numero real: "))
b = float(input("ingrese un numero real: "))

if a % b == 0:
    print("a es multiplo de b")
else: 
    print("a no es multiplo de b")
```

## 5. Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.
+ El siguiente es el desarrollo del quinto punto.
  
```python
n = float(input("ingrese un numero real: "))
a = float(input("ingrese un numero real: "))
b = float(input("ingrese un numero real: "))

if (n + a) > b:
    print(" la suma de los dos primeros es > b")
elif(n + a) < b:
    print(" la suma de los dos primeros es < b")     
else:
    print(" la suma de los dos primeros es = b")
```
## 6. Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.

+ El siguiente es el desarrollo del sexto punto.
  
```python
letra = input("Ingrese una letra: ")
if letra in ['a', 'e', 'i', 'o', 'u']:
    print(" es una vocal.")
else:
    print(" es una consonante.")
```
## 7. Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:
+ El promedio
+ La mediana
+ El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
+ Ordenar los números de forma ascendente
+ Ordenar los números de forma descendente
+ La potencia del mayor número elevado al menor número
+ La raíz cúbica del menor número
+ El siguiente es el desarrollo del septimo punto.

```python
a = float(input("ingrese un numero real: "))
b = float(input("ingrese un numero real: "))
c = float(input("ingrese un numero real: "))
d = float(input("ingrese un numero real: "))
e = float(input("ingrese un numero real: "))

f = (a+b+c+d+e)/ 5 
numeros = [a,b,c,d,e]
numeros.sort()

m = numeros[len(numeros)//2]

pm = (a*b*c*d*e)**0.5
lista_ordenada = sorted(numeros, reverse=True)

mayor = max(numeros)
menor = min(numeros)
pot = mayor**menor

raizc = (menor**0.33)
print(f"El promedio de los números es: {f}")
print(f"La mediana de los números es: {m}")
print(f"El promedio multiplicativo es: {pm}")
print(f"La lista de numeros ordenados de menor a mayor es: {numeros}")
print(f"La lista de numeros ordenados de mayor a menor es {lista_ordenada}")
print(f"La potencia del mayor numero elevado al menor es: {pot}")
print(f"La raiz cubica del menor numero es: {raizc}")
```
## 8. Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnético se encuentra.
+ El siguiente es el desarrollo del octavo punto.

```python
frecuencia = float(input("Ingrese la frecuencia de la onda en Hz: "))
if frecuencia < 3e9: 
    print("La frecuencia está en la banda de radio.")
elif frecuencia < 3e12: 
    print("La frecuencia está en la banda de microondas.")
elif frecuencia < 4.3e14:  
    print("La frecuencia está en la banda de infrarrojos.")
elif frecuencia < 7.5e14: 
    print("La frecuencia está en la banda de luz visible.")
elif frecuencia < 3e17:  
    print("La frecuencia está en la banda de ultravioleta.")
elif frecuencia < 3e19:  
    print("La frecuencia está en la banda de rayos X.")
else:
    print("La frecuencia está en la banda de rayos gamma.")
```
## 9. Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.
+ El siguiente es el desarrollo del decimo punto.
  
```python
pais = input("Ingresa el nombre de un país de América en minúsculas: ")
pais = pais.lower()
if pais == "argentina":
    print("Buenos Aires")
elif pais == "bolivia":

    print("La Paz")
elif pais == "brasil":
    print("Brasilia")
elif pais == "canadá":
    print("Ottawa")
elif pais == "chile":
    print("Santiago")
elif pais == "colombia":
    print("Bogotá")
elif pais == "costa rica":
    print("San José")
elif pais == "cuba":
    print("La Habana")
elif pais == "ecuador":
    print("Quito")
elif pais == "el salvador":
    print("San Salvador")
elif pais == "estados unidos" or pais == "eeuu":
    print("Washington, D.C.")
elif pais == "guatemala":
    print("Ciudad de Guatemala")
elif pais == "honduras":
    print("Tegucigalpa")
elif pais == "jamaica":
    print("Kingston")
elif pais == "méxico":
    print("Ciudad de México")
elif pais == "nicaragua":
    print("Managua")
elif pais == "panamá":
    print("Ciudad de Panamá")
elif pais == "paraguay":
    print("Asunción")
elif pais == "perú":
    print("Lima")
elif pais == "república dominicana":
    print("Santo Domingo")
elif pais == "uruguay":
    print("Montevideo")
elif pais == "venezuela":
    print("Caracas")
elif pais == "antigua y barbuda":
    print("Saint John's")
elif pais == "bahamas":
    print("Nassau")
elif pais == "barbados":
    print("Bridgetown")
elif pais == "belice":
    print("Belmopán")
elif pais == "dominica":
    print("Roseau")
elif pais == "granada":
    print("St. George's")
elif pais == "haití":
    print("Puerto Príncipe")
elif pais == "saint kitts y nevis" or pais == "san kitts y nevis":
    print("Basseterre")
elif pais == "santa lucía":
    print("Castries")
elif pais == "san vicente y las granadinas":
    print("Kingstown")
else:
    print("País no identificado")
```
## 10. Escriba un programa que dada una distancia calcule:
+ El tiempo que le tomaría a la luz recorrer la distancia.
+ El tiempo que le tomaría al sonido (en el aire) recorrer la distancia.
+ El tiempo que le tomaría al vehiculo comercial más veloz recorrer la distancia.
+ El tiempo que le tomaría a Bolt recorrer la distancia.

+ El siguiente es el desarrollo del decimo punto.
  
```python
distancia = float(input("Ingrese la distancia en metros: "))
velocidad_luz = 299792458
tiempo_luz = distancia / velocidad_luz
velocidad_sonido_en_aire = 343  
tiempo_sonido = distancia / velocidad_sonido_en_aire
velocidad_vehiculo_comercial = 27.78 
tiempo_vehiculo_comercial = distancia / velocidad_vehiculo_comercial
velocidad_bolt = 12.42 
tiempo_bolt = distancia / velocidad_bolt
print("Tiempo que le tomaría a la luz recorrer la distancia: ", tiempo_luz ," segundos")
print("Tiempo que le tomaría al sonido en el aire recorrer la distancia: ",tiempo_sonido ,"segundos")
print("Tiempo que le tomaría al vehículo comercial más veloz recorrer la distancia:", tiempo_vehiculo_comercial,"segundos")
print("Tiempo que le tomaría a Bolt recorrer la distancia: ", tiempo_bolt, "segundos")
```

