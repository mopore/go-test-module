This module exists to learn how to write Go modules.

The test `TestFucntion` in the `testmodule` package can be called to
return a string.

## Usage

```go
package main

import (
	"log"
	"github.com/mopore/go-test-module/testmodule"
)

func main() {
    log.Println("Hello World")
    testValue := testmodule.TestFunction()
    log.Printf("Test Value: %s", testValue)
}
```
