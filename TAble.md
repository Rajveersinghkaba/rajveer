#include<stdio.h>

int main(){
    
    int a=4, i, res;
    
    printf("Enter Number :\n");
    printf("%d",&a);
    
    for (i=0;i<=30;i++) 
    {
        res=a*i;
        printf("%d\n",res);
    }
    return 0;
}
