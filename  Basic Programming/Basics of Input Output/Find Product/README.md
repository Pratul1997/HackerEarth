# Solution

```
package main

import ("fmt"
        "math")

func main(){
    var num int
    fmt.Scanf("%d",&num)
    var arr []int
    arr = make([]int, num)
    for i:=0; i<num ;i++ {
        fmt.Scanf("%d",&arr[i])
    }
    var ans int64
    ans=1
    for j:=0; j<num ;j++ {
        ans=ans*int64(arr[j])
        ans=ans%int64(math.Pow(10,9)+7)
    }
    fmt.Println(ans)
}
```

