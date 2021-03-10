# uuid: Algoritmo de generación de identificador único universal.

[![GoDoc](https://godoc.org/github.com/fabianpallares/jwt?status.svg)](https://godoc.org/github.com/fabianpallares/uuid)

## Instalación:
Para instalar el paquete, utilizar la siguiente instrucción:
```
go get -u github.com/fabianpallares/uuid
```

## Generar identificador único universal versión 4 (random):
Para generar un nuevo identificador, utilizar la siguiente función:

```GO
package main

import (
    "fmt"
    "github.com/fabianpallares/uuid"
)

func main() {
    s := uuid.NuevoV4()
    fmt.Println("UUID:", s)
}
```

#### Documentación:
[Documentación en godoc](https://godoc.org/github.com/fabianpallares/uuid)