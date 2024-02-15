#include <stdio.h>

int main()
{
    int sum=0,flag=0;
    int a[4]={2,6,3,5};
    int n=5;
    for(int i=0;i<n;i++)
    {
       
        sum+=a[i];
        
    }
    for(int i=0;i<n-1;i++)
    {
        for(int j=i+1;j<n;j++)
        {
            int s=a[i]+a[j];
            int diff=sum-s;
            if(diff==s)
            {
                flag++;
            }
        }
    }
    if(flag>0)
    {
        printf("cool");
    }
    else
    {
        printf("not cool");
    }

    return 0;
}
