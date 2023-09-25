# Primer taller de INDUSPLAYTHON 👽



+ Comenzamos con el primer punto, que es realizar el Python Beginner Quiz 90% bien, adjuntamos pantallazo.
  
![](https://raw.githubusercontent.com/nisaespa/Taller1/main/punto1quizpython.jpg)

En el desarrollo del segundo punto posterior a convertir un string a flotante, usamos los condiciionales: "If, elif y else" para determinar cual es el mayor mediante el código
```
N = float(input("ingrese su porqueria: "))
b =  float(input("ingrese su porqueria: "))
c =  float(input("ingrese su porqueria: "))


if N > b and N > c:
  print("el maximo es: ",N)
 
elif b > N and b > c :
  print("el maximo es: ",b)
  
else:
       print("el maximo es: ",c)
```
En el desarrollo del tercer punto unicamente se usan dos de los condiciionales anteriormente nombrados después de convertir un string a flotante
numero = int(input("Ingrese un número entero: "))

```
if numero % 2 == 0:
    print("es un número par.")
else:
    print("es un número impar.")

```

4.
```
a = float(input("ingrese un numero real: "))
b = float(input("ingrese un numero real: "))

if a % b == 0:
    print("a es multiplo de b")
else: 
    print("a no es multiplo de b")
```

5. 
```
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

6.
```
letra = input("Ingrese una letra: ")
if letra in ['a', 'e', 'i', 'o', 'u']:
    print(" es una vocal.")
else:
    print(" es una consonante.")
```

7.
```
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
       

