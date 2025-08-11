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
