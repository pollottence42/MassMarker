[[j]]
```java
import java.util.Scanner;

public class Main {
    public static void main (String[] args) {

		var scan = new Scanner(System.in);
		
		var x = scan.nextInt();
		var a = scan.nextInt();
		var res = x < a ? (x + a) : (x - a);
		System.out.println(res);
    }
}
```
