#include<stdio.h>

int main()
{
    int arr[100],i,j,n,temp;
    printf("Enter the element of numbers:");
    scanf("%d",&n);
    
    printf("enter %d element:\n",n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&arr[i]);
    }
    for(i=0;i<n-1;i++)
    {
        for(j=0;j<n-i-1;j++)
        {
            if(arr[j]>arr[j+1] )
            {
                temp=arr[j];
                arr[j]=arr[j+1];
                arr[j+1]=temp;
            }
        }
    }
    
    printf("sorted array:");
    for( i = 0 ; i < n ; i++ )
    {
        printf("%d\t", arr[i]);
    }
    return 0;
}
