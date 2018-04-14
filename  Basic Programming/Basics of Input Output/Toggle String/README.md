# Solution

```
package main
 
import ("fmt"
        "strings"
    )
    
func main(){
    var str,s string
    fmt.Scanf("%s",&str)
    for i:=0 ; i<len(str);i++{
        if(int(str[i])>=65 && int(str[i])<=90){
            s+=strings.ToLower(string(str[i]))
        }
        if(int(str[i])>=97 && int(str[i])<=122){
            s+=strings.ToUpper(string(str[i]))
        }
    }
    fmt.Println(s)
}
```
