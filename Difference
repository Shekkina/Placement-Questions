#include<stdio.h>
#include<stdlib.h>
int main()

{
    
    
    int diff,n;
    printf("Enter no of nos");
    scanf("%d",&n);
    int a[n];
    printf("Enter the difference:");
    scanf("%d",&diff);
    for(int i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    for(int i=0;i<n-1;i++)
    {
        for(int j=i+1;j<n;j++)
        {
            int d=abs(a[i]-a[j]);
            if(diff==d)
            {
               printf("%d ,%d\n",a[i],a[j]); 
            }
        }
    }
    return 0;
    
}
