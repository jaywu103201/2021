# java ch3
### for loop
```
package ex03;
public class For {
	public static void main(String[] args) {
		int i;
		int sum = 0;
		for (i = 1; i <= 10; i++) {
		    sum += i;
		}
		System.out.println("從1加到10的總和是: " + sum);
		System.out.println("最後 i 值為: " + i);	
	}
}
```
```
$javac For.java
$java -Xmx128M -Xms16M For
從1加到10的總和是: 55
最後 i 值為: 11
```
### average
```
package ex03;
import java.util.Scanner;
public class Average {
	public static void main(String[] args) {
		Scanner scn = new Scanner(System.in);
		int score = 0;	// 輸入的分數預設為0
		int sum = 0;	// 累計的總和
		int num = 0;		   // 預設人數為0
		while (score != -1) {
			System.out.print("請輸入分數 (輸入-1結束):");
			score = scn.nextInt();	// 讀取分數
			if(score != -1) {
		    	sum += score;		// 將輸入分數的加到總和sum中
		    	num++;	// 人數加1        		
			}
		}
		System.out.printf("平均分數 = " + (double)((sum+1) / (num-1)));
		scn.close();
	}
}

 ```
 ```
  C:\Users\KSUIE\1\ex03\src\ex03>java Average.java
請輸入分數 (輸入-1結束):100
請輸入分數 (輸入-1結束):93
請輸入分數 (輸入-1結束):-1
平均分數 = 194.0
```
# download java
```
https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
```
### 質數判斷法
### 厄拉托西尼篩法
```
public class prime {
public static void main(String[] args)
     {
         int aa[]=new int [101];
         aa[2]=0;
         int k=2,tt=0;
         while(tt<101)
             {   
              for(int i=1; i<aa.length; i++) //不是質數的數篩除
                     {
                      if(i%k==0&&i!=k) //
                      aa[i]=1; 
                      
                     }
             
                 for(int i=1; i<aa.length; i++) //將篩除後的第一個數當做新的篩子(k)
                 { 
                    if(i>k&&aa[i]==0)
                    {
                      k=i;
                      break;
                    }
                 }
                 tt++;
             }
for(int i=1; i<aa.length; i++)
             if(aa[i]==0) System.out.printf("%d ",i);
     }
}
```
```
/**
 * 判斷 101-200 之間有多少個素數，並輸出所有素數。
 * @author Rain_JN
 * @data 2017年6月5日
 * @version V1.0
 */
public class CountPrimes {
    public static void main(String[] args) {
        MyMath math = new MyMath();
        for(int i = 101; i <= 200; i++){
            if(math.isPrime(i)){
                System.out.println(i);
            }
        }
    }
}

class MyMath{
    /**
     * 判斷一個數是否為質數
     * @param x 要判斷的數字
     * @return 如果是質數，返回true，否則返回false
     */
    public boolean isPrime(int x){
        //小於2的數不是質數
        if(x < 2){
            return false;
        } else{         
            for(int i = 2; i<= Math.sqrt(x); i++){
                // 若能被整除，則說明不是素數，返回false  
                if(x % i == 0){             
                    return false;
                } 
            }
            return true;    
	    
