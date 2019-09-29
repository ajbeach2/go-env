# goenv

## Quick Start

```go
package main

import (
	"fmt"
	"github.com/ajbeach2/goenv"
)

func main(){
	val := goenv.GetEnv("FOO", "bar")
	fmt.fmt.Println(val)
}
```