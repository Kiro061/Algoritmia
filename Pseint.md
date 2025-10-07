´´´
# Saludo Personalizado

    Algoritmo 
        Definir nombre Como Caracter
        Definir edad Como Entero

        Escribir "¿Cómo te llamas?"
        Leer nombre

        Escribir "¿Cuántos años tienes?"
        Leer edad

        Escribir "Hola ", nombre, ", tienes ", edad, " años"
    FinAlgoritmo
´´´
# Precio Descuento
    Algoritmo 
        Definir precio, descuento, total como real

        Escribir "Digite el precio del producto"
        leer precio

        Escribir "Digite el descuento"
        Leer descuento
        
        total= precio - descuento

        Escribir " El total es ", total
    FinAlgoritmo

´´´
# Falso o Verdadero Mayor de edad
    Algoritmo
        Definir Nombre como caracter
        Definir edad como entero

        Escribir "Digite el nombre"
        Leer Nombre

        Escribir "Digite edad"
        Leer edad

        respuesta = edad >= 18

        Imprimir "Eres mayor de edad: ", respuesta
    FinAlgoritmo
´´´
# Falso o Verdadero para entrar
    Algoritmo
        Definir edad como entero
        Definir Permiso como logico
        Definir PuedeEntrar como logico

        Escribir "Ingresa tu edad"
        leer edad

        Escribir "tienes permiso? (Verdadero/Falso)"
        leer permiso

        PuedeEntrar <- (edad >=18) y permiso

        Escribir "Puede ingresar?:", Puede entrar
    FinAlgoritmo
´´´
# Notas
    Algoritmo
        Definir nota como real

        Escribir "Digite la nota"
        Leer nota

        Si nota > 5.0 o nota < 0 Entonces

        Si nota >= 4.5 y nota <= 5.0 entonces
            Escribir "Excelente"
        sino
            si nota >= 4.0 y nota < 4.5 entonces
                Escribir "Sobresaliente"
            Sino
                si nota >= 3.5 y nota < 4.0 entonces
                Escribir "Aceptable"
                Sino nota >= 3.0 y nota < 3.5 entonces
                    Escribir "Aprobado" 
    FinAlgoritmo
´´´
# Clasificacion De Notas




