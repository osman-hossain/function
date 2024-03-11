<!--function-->

__F__~~u~~_n_~~c~~`tion`

---

### sum of two three numbers using function
</br>

```c
#include<stdio.h>
int main()
{
    int num1,num2,num3,num4;
    printf("Enter number 1 : ");
    scanf("%d",&num1);
    printf("Enter number 2 : ");
    scanf("%d",&num2);
    printf("Enter number 3 : ");
    scanf("%d",&num3);
    printf("Enter number 4 : ");
    scanf("%d",&num4);

    printf("Sum = %d\n",sum(num1,num2));
    printf("Subtract = %d\n",sub(num1,num2));
    printf("Sum = %d\n",sum(num3,num4));
    printf("Subtract = %d\n",sub(num3,num4));
    printf("Total sum = %d\n",s(num1,num2,num3,num4));

}

int sum(int a,int b)
{
    return a+b;
}

int sub(int c,int d)
{
    return c-d;
}

int s(int a,int b,int c,int d)
{
    return a+b+c+d;
}
```  
another

```c
#include<stdio.h>
int sum(int a,int b)
{
    return a+b;
}

int sub(int c,int d)
{
    return c-d;
}

int s(int a,int b,int c,int d)
{
    return a+b+c+d;
}

int main()
{
    int num1,num2,num3,num4;

    printf("Enter the number 1 : ");
    scanf("%d",&num1);
    printf("Enter the number 2 : ");
    scanf("%d",&num2);
    printf("Enter the number 3 : ");
    scanf("%d",&num3);
    printf("Enter the number 4 : ");
    scanf("%d",&num4);

    printf("Sum = %d\n",sum(num1,num2));
    printf("Subtract = %d\n",sub(num1,num2));
    printf("Sum = %d\n",sum(num3,num4));
    printf("Subtract = %d\n",sub(num3,num4));
    printf("Total sum = %d\n",s(num1,num2,num3,num4));
}
```  
![function](./images/function.png)  

```c
#include<stdio.h>
int sum(int a,int b,int c)
{
    return a+b+c;
}
int sub(int a,int b,int c)
{
    return a-b-c;
}

int main()
{
    printf("Sum = %d\n",sum(4,5,6));
    printf("Sub = %d\n",sub(10,5,2));
}
```
<image src="./images/shorter.png" width="500" title="shor"/>  

```c
#include<stdio.h>
int sum(int a,int b)
{
    return a+b;
}
int sub(int a,int b)
{
    return a-b;
}

int main()
{
    int result = sum(20,15);
    int resultb = sub(30,3);
    printf("Sum = %d\n",result);
    printf("Subtract = %d\n",resultb);
}
```  
<image src="./images/alternative.png" width="500" title ="alternative"/>  

### void instead return

```c
#include<stdio.h>
void sum(int a,int b,int c)
{
    printf("Sum = %d\n",a+b+c);
}

void sub(int d,int a,int o)
{
    printf("Subtract = %d\n",d+a+o);
}

int main()
{
    sum(10,15,20);
    sub(20,10,5);
    sum(30,50,80);
    sum(90,1,2);
}
```

![void](./images/void.png)  

### Square ^

```c
#include<stdio.h>
int square(int a)
{
    return a*a;
}

int main()
{
    int num;
    printf("Enter the number : ");
    scanf("%d",&num);
    int result = square(num);
    printf("Square = %d\n",result);
    printf("Square = %d\n",square(2));
    printf("Square = %d\n",square(5));
}

```  
<image src="./images/square.png"/>

### Area of Triangle

```c
#include<stdio.h>
double at(double b, double h)
{
    return (b*h)/2;
}

int main()
{
    double base,height;
    printf("Enter the base : ");
    scanf("%lf",&base);
    printf("Enter the height : ");
    scanf("%lf",&height);
    double result=at(base,height);
    printf("Area of Triangle is : %.2lf\n",result);
    printf("Area of Triangle is : %.2lf\n",at(10,5));
}

``` 
<image src="./images/areaoftriangle.png" width="500" title="areaoftriangle"/>   
alternative

```c
#include<stdio.h>
void at(double b,double h)
{
    double result =  (b*h)/2;
    printf("Area of Triangle is : %.2lf\n",result);
}

int main()
{
    double base,height;
    printf("Enter the base : ");
    scanf("%.2f",&base);
    printf("Enter the height : ");
    scanf("%.2lf",&height);

    at(base,height);
    at(10,3.2);
}
![alter](./images/alt.png) 

### whole square unlimited

```c
#include<stdio.h>
void calculatepower(double a,double b)
{
    double i,result=1;
    for(i=1; i<=b; i++)
    {
        result=result*a;
    }
    printf("Result = %.2lf",result);
}

int main()
{
    double base,exp;
    printf("Enter the base : ");
    scanf("%lf",&base);
    printf("Enter the exponent : ");
    scanf("%lf",&exp);

    calculatepower(base,exp);
    calculatepower(10,2);
    calculatepower(3,3);
    calculatepower(4,2);
}
```  
<image src="./images/power.png" width="500" title="power"/>  

### array in function

```c
#include<stdio.h>
int main()
{
    int a[]={10,33,50,66,22};
    display(a);
}
void display(int x[])
{
    for(int i=0; i<5; i++)
    {
        printf("%d\n",x[i]);
    }
}
```  
<image src="./images/arrayfunction.png" width="500" title="arrayfunction"/>  

