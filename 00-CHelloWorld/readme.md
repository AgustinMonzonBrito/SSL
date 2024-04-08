 00-CHelloWorld
 
    1 -hello.c : Contiene el codigo fuente encargado de generar el ejecutable.
    2 -output.txt : Lo generamos a partir del comando ./hello.exe > output.txt

El compilador utilizado para trabajar es tdm64-1. Esto es lo que obtuvimos a partir del comando gcc --version.
    "gcc.exe (tdm64-1) 10.3.0
        This is free software; see the source for copying conditions.  There is NO
        warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE."

Las versiones del lenguaje de programación que el compilador compila son: 
    C11
    C18
    c2x
Esto lo obtuvimos por medio del comando -std. 
Haciendo 
    gcc hello.c -std=c18 -o helloc18.exe
    gcc hello.c -std=c11 -o helloc11.exe
    gcc hello.c -std=c2x -o helloc2x.exe