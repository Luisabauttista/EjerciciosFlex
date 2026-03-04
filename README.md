# Ejercicios del capitulo 2 del libro Flex y Bison 

En este repositorio se encuentran 3 jercicios planeados y desarrollados en VirtualBox Ubuntu utilizando C, Flex y Bison. 
Estudiante: Luisa Fernanda Bautista Garzón 

# Ejercicio 1 

# Compilación y ejecución 

flex bloque.l 
gcc lex.yy.c -o bloque -lfl
./bloque < prueba.txt

# Ejercicio 2 

# Compilación y ejecución 

bison -d Ejercicio2.y
flex Ejercicio2.l
gcc Ejercicio2.tab.c lex.yy.c -o Ejercicio2 -lfl
./Ejercicio2

Ejemplo: Prueba PruebaEjercicio HolaMundo 

# Ejercicio 3 

# Compilación y ejecución 

bison -d Ejercicio3.y
flex Ejercicio3.l
gcc Ejercicio3.tab.c lex.yy.c -o Ejercicio3 -lfl
./Ejercicio3


Ejemplo: 2+2
10-5
5*5
4/2 

