# c-6
#include <stdio.h>
int main()
{
    int i,j,n,m;
    printf("enter row of matrix:");
    scanf("%d",&n);
    printf("enter column of matrix:");
    scanf("%d",&m);
    for(i=1;i<=n;i++){
        for(j=1;j<=m;j++){
        printf("@");
    }
    printf("\n");
}
    return 0;
}
