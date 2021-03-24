### Hello.java
```
public class Hello
{
	public static void main(String args[])
	{
		System.out.println("Hello World!!");
	}
}

```
### C Program To Find Area And Circumference Of Circle

## C
```
#include <stdio.h>
int main()
{
   /*Program By Ghanendra Yadav
   Visit http://www.programmingwithbasics.com/
  */
   int rad;
   float PI = 3.14, area, ci;

   printf("\nEnter radius of circle: ");
   scanf("%d", &rad);

   area = PI * rad * rad;
   printf("\nArea of circle : %f ", area);

   ci = 2 * PI * rad;
   printf("\nCircumference : %f ", ci);

   return (0);
}
```
## C++
```
#include<iostream>
using namespace std;
int main()
{
/*Program By Ghanendra Yadav
Visit http://www.programmingwithbasics.com/
*/
int rad;

float PI = 3.14, area, ci;
cout<<"Enter radius of circle: ";
cin>>rad;
area = PI * rad * rad;
cout<<"Area of circle "<< area<<endl;
ci = 2 * PI * rad;
cout<<"Circumference of circle "<< ci<<endl;
return (0);
}

```
## java
```
/* Program By Ghanendra Yadav
   Visit http://www.programmingwithbasics.com/
*/
import java.util.Scanner;
class circle
{
   static Scanner sc = new Scanner(System.in);
   public static void main(String args[])
   {
      System.out.print("Enter The Radius Of Circle: ");
      double radius = sc.nextDouble();
      
   double area = Math.PI * (radius * radius);
      System.out.println("Circle Area is : " + area);
      
   double circumference= Math.PI * 2*radius;
      System.out.println( "Circle Circumference is:"+circumference);
   }
}
```
### 作業java
```
/* Program By Ghanendra Yadav
   Visit http://www.programmingwithbasics.com/
*/
import java.util.Scanner;
class circle
{
   static Scanner sc = new Scanner(System.in);
   public static void main(String args[])
   {
      System.out.print("Enter The Radius Of Circle: ");
      double radius = sc.nextDouble();
      
   double area = Math.PI * (radius * radius* radius)*(4/3);
      System.out.println("Circle Volume is : " + area);
      
   double circumference= Math.PI * 4*radius* radius;
      System.out.println( "Circle Surfacearea is:"+circumference);
   }
}
```
