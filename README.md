
#include <stdio.h>

int main() {
    int n;
    scanf("%d",&n);
    int i,j;
    for(int i=1;i<=n;i++)
    {
        for(j=1;j<=10;j++)
        {
            printf("%d * %3d = %3d\n",i,j,i*j);
        }
        printf("\n*************\n\n");
    }

    return 0;
}
