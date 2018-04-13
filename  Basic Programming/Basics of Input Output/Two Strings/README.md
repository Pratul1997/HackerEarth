# Solution

```
package main
 
import( "fmt"
        "sort"
        "strings"
    )
 
func main(){
    var num int
    fmt.Scanf("%d",&num)
    for i:=0;i<num;i++{
        var str1,str2 string
        fmt.Scanf("%s %s",&str1,&str2)
        s1 := strings.Split(str1, "")
        sort.Strings(s1)
        str1=strings.Join(s1, "")
        s2 := strings.Split(str2, "")
        sort.Strings(s2)
        str2=strings.Join(s2, "")
        if strings.Compare(str1,str2) == 0{
            fmt.Println("YES")
        } else {
            fmt.Println("NO")
        }
    }
}
```