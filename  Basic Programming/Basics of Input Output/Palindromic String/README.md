# Solution

```
package main
 
import "fmt"
 
func main(){
    var str string
    fmt.Scanf("%s",&str)
    pd:=""
    for i:=0 ;i<len(str); i++ {
        pd+=string(str[len(str)-1-i])
    }
    if str==pd {
        fmt.Println("YES")
    } else{
        fmt.Println("NO")
    }
}
```