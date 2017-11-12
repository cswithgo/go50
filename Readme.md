## Go50: A port of the CS50 Library for Go
---
### To install:

```
$go get github.com/cswithgo/go50
```

### Import the package in your code like so:
<pre>
package main

import (
    "fmt"
    <b>"github.com/cswithgo/go50"</b>
)

func main() {
    name := go50.GetString("Enter your name:")
    fmt.Printf("Hello %s", name)
}
</pre>

