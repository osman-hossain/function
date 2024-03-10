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

