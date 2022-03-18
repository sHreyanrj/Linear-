#include<stdio.h>
void main()
{
 int a[]={1,0,1,0,1,0,0,1},i,j,temp;
 for(i=0;i<9;i++)
 {
 for(j=i+1;j<9;j++)
 {
 if(a[i]>a[j])
 {
 temp=a[i];
 a[i]=a[j];
 a[j]=temp;
 }
 }
 }
 printf("%d\t",a[i]);
}
