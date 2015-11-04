# Hello-in-Go
A simple Hello World in Go.



Hacemos de GOPATH apuntar al directorio del workspace
set GOPATH=HOME/gocode

Entramos a la carpeta del workspace
cd gocode

Creamos el directorio de  nuestro proyecto y entramos a la carpeta
mkdir -p src\github.com\marianagh
cd src\github.com\marianagh

Creamos el directorio del proyecto y entramos en el
mkdir hello
cd hello

Llamamos a vim y le indicamos que cree un archivo de extension .go
vim hello.go

dentro del archivo de vim escribimos

package main

import "fmt"

func main() {
	fmt.Println("Hola mundo!")

}


Damos esc o click para que vim espere un comando dammos :wq 
para guardar y salir, volvemos al cmd de windows

verificamos que el archiv se haya creado 
dir

Instalamos 
go install

Hasta aqui puede que no reconozca el comando.
Si no agregamos el GOBIN lo agregamos como indique en el paso 2.

Instalamos de nuevo.
go install

Si no aparece nada significa que todo va bien.
Podemos revisar el GOBIN y ver que se ha creado un nuevo archivo.

Llamamos a nuestro programa 

hello.exe

Voila.
