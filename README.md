# Insertingarray
#include<stdio.h>
int main()
{
    int i,j,n,p,m=6;
    int arr[6];
    printf("Enter the element in in a array\n");
    for (i=0;i<5;i++)
    {
        scanf("%d",&arr[i]);
    }
    printf("Enter the element to be inserted\n");
    scanf("%d",&n);
    printf("Enter the position to enter\n");
    scanf("%d",&p);

    for (i=4;i>=p;i--)
    {
        arr[i+1]=arr[i];
    }

    arr[p]=n;


    for (i=0;i<6;i++)
    {
        printf("%d",arr[i]);
    }

    return 0;
}
