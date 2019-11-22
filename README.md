 #include <stdio.h>
 int main()
{
    int a, b;
 
    printf(" ");
    scanf("%d",&a);
    
    b = 0;
    while (a > 0)  {
        b += a%10;
        a /= 10;
    }
 
    printf(" %d\a",b);
    return 0;
}
