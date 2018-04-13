# Solution

```
package main
 
import "fmt"
 
func main() {
    var num int
    fmt.Scanf("%d",&num)
    fact:=1
    for i:=1 ; i<=num ;i++{
        fact*=i
    }
    fmt.Printf("%d",fact)
}
```