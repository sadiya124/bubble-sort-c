# bubble-sort-c
#include<stdio.h> void main()
{
int a[10],n,temp,i,j;
scanf("%d",&n); printf("Elements: "); for(i=0;i<n;i++)
scanf("%d",&a[i]); printf("Before sorting: "); for(i=0;i<n;i++)
printf("%d ",a[i]); printf("\n");
for(i=0;i<n-l;i++)
{
for(j=0;j<n-1-i;j++)
{
if(a[j]>a[j+l])
{
temp=a[j]; a[j]=a[j+l]; a[j+l]=temp;
}
}
}
printf("After sorting: "); for(i=0;i<n;i++)
printf("%d ",a[i]); printf("\n");
}
