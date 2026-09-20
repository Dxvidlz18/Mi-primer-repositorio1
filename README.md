def  cuadrado():
    lado = float(input("Ingrese el tamaño del lado: "))
    area = lado*lado
    print("El área de la figura es", area)
    perimetro = lado*4
    print("El perímetro de la figura es: ", perimetro)
    
def rectangulo():
    base = float(input("Ingrese el tamaño de la base: "))
    altura = float(input("Ingrese la altura")) 
    area = base*altura
    print("El área de la figura es", area)
    perimetro = base+base+altura+altura
    print("El perímetro de la figura es: ", perimetro)
    
def circulo():
    radio = float(input("Ingrese el radio: "))
    area = 3.14*radio*radio
    print("El área de la figura es", area)
    perimetro = 2*3.14*radio
    print("El perímetro de la figura es: ", perimetro)
    
def triangulo():
    base = int(input("Ingrese el tamaño de la base: "))
    altura = int(input("Ingrese la altura: "))
    area = (base*altura)/2
    print("El área de la figura es", area)
    lado = int(input("Ingrese la longitud de los lados: "))
    perimetro = lado+lado+lado
    print("El perímetro de la figura es: ", perimetro)
    
def rombo():
        diagonal_mayor = float(input("Ingrese el valor de la diagonal mayor: "))
        diagonal_menor = float(input("Ingrese el valor de la diagonal menor: "))
        lado = float(input("Ingrese el lado: "))
        area = (diagonal_mayor*diagonal_menor)/2
        print("El área de la figura es", area)
        perimetro = 4*lado
        print("El perímetro de la figura es: ", perimetro)
        
def trapecio():
        base_mayor = float(input("Ingrese el valor de la base mayor: "))
        base_menor = float(input("Ingrese el valor de la base menor: "))
        lado = float(input("Ingrese el tamaño de los lados: "))
        altura = float(input("Ingrese la altura: "))
        area = ((base_mayor+base_menor)*altura)/2
        print("El área de la figura es", area)
        perimetro = 4*lado
        print("El perímetro de la figura es: ", perimetro)
  
     
def menu():
    print("Menú de Operaciones Artmérticas")
    print("------------------------------")
    print("1. Cuadrado")
    print("2. Rectángulo")
    print("3. Círculo")
    print("4. Triángulo")
    print("5. Rombo")
    print("6. Trapecio")
    print("------------------------------")   
    

menu()
opcion= int(input("Ingrese la Opción: "))    


if opcion == 1:
    cuadrado()
if opcion == 2:
    rectangulo()  
if opcion == 3:
    circulo()  
if opcion == 4:
    triangulo()  
if opcion == 5:
    rombo()  
if opcion == 6:
    trapecio()      
        
        
    
        
        
