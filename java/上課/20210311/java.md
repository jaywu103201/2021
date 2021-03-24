# java2-28=>3-14
```
package ex03;
import java.util.Scanner;
public class NestIf {
	public static void main(String[] args) {
		Scanner scn = new Scanner(System.in);
		int num1, num2, num3, num4, max;
		System.out.print("請輸入四個數字(空白區間):");
		num1 = scn.nextInt();
		num2 = scn.nextInt();
		num3 = scn.nextInt();
		num4 = scn.nextInt();
		if (num1 > num2) {        
			if (num1 > num3)
				if (num1 > num4)
					max = num1;
			    else 
				    max = num4;
		} else {
			if (num2 > num3)
				if (num2 > num4) 
					max = num2;
			    else
				    max = num4;
		} else {
			if (num3 > num4)
				 max = num3;
			 else
				 max = num4;
		}
		
		System.out.println("最大的數字是:" + max);
		scn.close();
	}
}

```
```
$javac ex03/NestIf.java
ex03/NestIf.java:24: error: 'else' without 'if'
		} else {
		  ^
1 error
```
