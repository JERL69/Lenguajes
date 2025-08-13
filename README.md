Para ejecutar los ejercicios:

Primero instalar flex y Bison desde la terminal con el siguiente comando 

- brew install flex bison
Ahora se complila con el siguiente comando
- # 2. Compilar
gcc lex.yy.c ejercicioX.tab.c -o programaX -lfl
Y se ejecuta con este otro:
# 3. Ejecutar
./programaX

Para esto tenemos que tener en cuenta en que carpeta esta guardado los archivos y con el comando **cd** iremos ingresando a las carpetas


**Grmaticas**

**Codigo Bison (C)**
-Para compilar este archivo, promero toca descargar el .zip
- Guardarlo
- Abrir la terminal
- Con el comando cd, entrar al archivo donde esta guardada la carpeta
-  Una vez estemos dentro de la carpeta, toca ingresar el siguiente comando : gcc -o gramaticas gramaticas.tab.c lex.yy.c -lfl
-  Luego pondremos este: ./gramaticas 2 Prueba.txt
-  El numero que aparece en medio de los nombres de los archivos, se modifica segunla regla gramatical que queramos validar, en este caso es la regla 2 (G2)

**Codigo Python **
- Para compilar este archivo, promero toca descargar el .zip
- Guardarlo
- Abrir la terminal
- Con el comando cd, entrar al archivo donde esta guardada la carpeta
- Luego ponemos este comando: python3 Gramaticas.py 2 Prueba.txt
-  El numero que aparece en medio de los nombres de los archivos, se modifica segunla regla gramatical que queramos validar, en este caso es la regla 2 (G2)

  
