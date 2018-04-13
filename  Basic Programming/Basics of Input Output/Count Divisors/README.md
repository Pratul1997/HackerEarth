# Solution

```
package main
import "fmt"
 
func main(){
    var l,r,k,c int
    fmt.Scanf("%d %d %d",&l,&r,&k)
    for i:=l;i<=r;i++ {
        if i%k == 0{
            c++
        }
    }
    fmt.Println(c)
}
```