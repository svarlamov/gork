## GORK - Easy Random Key Generation in Go
## Installing
`go get github.com/svarlamov/gork`
## Testing
`go test --bench .`
## Usage
```go
package main

import (
        "fmt"
        "github.com/svarlamov/gork"
)

func main() {
        numberOfCharacters := 16
        randomKey := gork.FastAlpha(numberOfCharacters)
        fmt.Println("Random Key:", randomKey)
}
```
## Credits
http://stackoverflow.com/a/31832326/4858295
