Para ejecutar los ejercicios:

Primero instalar flex y Bison desde la terminal con el siguiente comando 

- brew install flex bison
Ahora se complila con el siguiente comando

 **2. Compilar**
 
- gcc lex.yy.c ejercicioX.tab.c -o programaX -lfl
  
Y se ejecuta con este otro:

**3. Ejecutar**

- ./programaX

Para esto tenemos que tener en cuenta en que carpeta esta guardado los archivos y con el comando **cd** iremos ingresando a las carpetas


# 2. Gramàticas

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


  
# 3. AFD

1. Hay que ubucarse  en la carpeta donde quedò el proyecto

Luego hay que entrar así:

**cd /Desktop/AFD**
Este es un ejemplo si el proyecto quedò en el escritorio

2. Ahora en la misma terminal ejecutamos el programa de la siguiente manera, primero con el C:
   
**gcc -o afd afd.c**

3. Luego usaremos este comando:

   **./afd Conf.txt Cadenas.txt**
Una vez haya ejecutado, se podra visualizar el resultado.

4. Para el Phyton tendremos que hacer algo similar:

- Solo tendremos que poner el siguiente comando en la tuerminal
.  **python3 afd.py**

Si se quiere modificar las entradas, somo tenemos que entrar al archivo txt directamente y modificarlos manualmente.



