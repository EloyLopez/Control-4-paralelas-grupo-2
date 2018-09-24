# Control-4-paralelas-grupo-2



## Introducción

Es el programa base para cifrar usando el algoritmo **blowfish** es necesario tener instalado openssl (sudo apt-get install libssl-dev).

## Compilación


make

## Ejecución

./dist/cryptoapp -v

Muestra integrantes del grupo


mpiexec -n x ./dist/cryptoapp -f /tmp/prueba.txt

Donde x es el número de procesadores que se desean ocupar

Inicia el programa, y cuando encuentre la clave se creará un .txt en la ruta agregada "/tmp/prueba.txt"
