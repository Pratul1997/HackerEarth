# Solution

```
package main

import "fmt"
func main(){
    var num int
    fmt.Scanf("%d",&num)
    var arr []int64
    var sum int64
    arr = make([]int64, num)
    for i:=0; i<num ;i++ {
        fmt.Scanf("%d",&arr[i])
        sum+=arr[i]
    }
    fmt.Println(sum)
}
package main
```
