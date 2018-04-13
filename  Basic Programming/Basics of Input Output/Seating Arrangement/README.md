# Solution

```
package main
 
import "fmt"
 
func main(){
    var n int
    fmt.Scanf("%d",&n)
    for i:=0;i<n;i++{
        var num int
        fmt.Scanf("%d",&num)
        switch num%12 {
            case 1:fmt.Printf("%d WS",(num+11))
            case 2:fmt.Printf("%d MS",(num+9))
            case 3:fmt.Printf("%d AS",(num+7))
            case 4:fmt.Printf("%d AS",(num+5))
            case 5:fmt.Printf("%d MS",(num+3))
            case 6:fmt.Printf("%d WS",(num+1))
            case 7:fmt.Printf("%d WS",(num-1))
            case 8:fmt.Printf("%d MS",(num-3))
            case 9:fmt.Printf("%d AS",(num-5))
            case 10:fmt.Printf("%d AS",(num-7))
            case 11:fmt.Printf("%d MS",(num-9))
            case 0:fmt.Printf("%d WS",(num-11))
        }
        fmt.Println()
    }
}
```