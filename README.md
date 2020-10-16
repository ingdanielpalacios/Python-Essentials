# Python-Essentials
#I WILL PUT HERE ALL THE BASIC PYTHON FUNCTIONS WITH AN EXAMPLE OF EACH

#Condicionales

numero=int(input("Digite un valor entero: "))

if numero>0:

    print("El numero que ingreso el positivo")
    #Despues del if, todas las lineas de codigo que tengan la identacion estancondicionadas por if,
    #pero si le quito a identacion(sangria) es como cerrar las llaves

elif numero==0:

    print("El numero no es ni positivo ni negativo")
    
#Si se cumple el if se ejecuta, si no se va al elif y si no al else

else:

    print("El numero que ingreso es negativo")

#Condicionales combinados

edad=int(input("Digite su edad aqui: "))

if edad>0 and edad<100: #tambien se puede poner 0<edad<100

    print("edad correcta")
    
    if edad>=18:
    
        print("Es mayor de edad")
        
    else:
    
        print("Es menor de edad")
        
else:

    print("Edad incorrecta")
