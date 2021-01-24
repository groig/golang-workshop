# Variables

Una variable es un nombre que se le asigna a una porcion de memoria
para almacenar un valor de un determinado tipo.

El keyword `var` se usa para declarar variables. La sintaxis es `var
<name> <type>` seguido (opcionalmente) por un valor inicial.

Ejemplos:

```go
var a int // Inicializado por defecto

var b = 10 // Se infiere el tipo

var c, d = 20, 30 // Asignando valores múltiples

e, f := 40, 50 // Crear y asignar
```

Si no se especifica un valor inicial Golang asigna uno por defecto
dependiento del tipo de dato de la variable.

Para imprimir el valor de una variable se puede usar `Println`.

`fmt.Println("a = ", a)`

En el archivo `main.go` incluido en este ejercicio hay mas ejemplos de
uso.