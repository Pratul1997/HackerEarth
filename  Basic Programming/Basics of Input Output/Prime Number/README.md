# Solution

```
package main
 
import "fmt"
 
func main(){
    var num int
    fmt.Scanf("%d",&num)
    for i := 1; i <= num; i++ {
        c:=0
		for j := 1; j <= i; j++{
		    if i%j==0{
		        c=c+1;
		    }
		}
		if(c==2){
		    fmt.Print(i," ")
		}
	}
}
```