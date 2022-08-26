# Solution-of-CSE-103-Lab-Test-2
The solution of CSE 103 Lab Test at 24 August 2022

Solution of 1st problem

#include<stdio.h>
int main()
{

    int a,b,n;
    int T=0;
    scanf("%d",&n);
    for(a=1;a<=n;a++)
    {
        for(b=1;b<=n;b++)
        {
            printf("%d",b+T);
        }
        T++;
        printf("\n");
    }


    return 0;
    
}

Solution of 2ed problem

#include<stdio.h>
int main()
{

    int n,i,j;
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        if(i%2==0)
        {
            for(j=1;j<=n;j++)
            {
                if(j%2==0)
                {
                    printf("0");
                }
                else
                {
                    printf("1");
                }
            }
        }
        else
        {
            for(j=1;j<=n;j++)
            {
                if(j%2==0)
                {
                    printf("1");
                }
                else
                {
                    printf("0");
                }
            }
        }
        printf("\n");
    }
    return 0;
    
}

Solution of 3rd problem

#include<stdio.h>
int main()
{

    int m;
    int numbers = 0;
    scanf("%d",&m);
    for(int a=m;a>0;a=a/10)
    {
        int digit = a%10;
        int count = 0;
        for(int b=2; b<digit;b++)
        {
            if(digit%b==0)
            {
                count++;
            }
        }
        if(digit==0)
        {
            count++;
        }
        if(count==0)
        {
            printf("%d ",digit);
            numbers = 1;
        }
    }
    if (numbers==0)
    {
        printf("none");
    }
    return 0;
    
}

Solution of 4th solution

#include<stdio.h>
#include<math.h>
int main()
{

    int i,j,n,k;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=i;j++)
            {
                for(k=1;k<=i;k++)
                {
                    printf("%d",j);
                }
            }
            printf("\n");
    }
    
}

