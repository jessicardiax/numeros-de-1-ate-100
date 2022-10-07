#include <stdio.h>

int main()
{
 int i,n;
 int mn = -1;
 int position = -1;
 i=1;
 while (i<=5){
     
     printf("informe um numero: ");
     scanf("%d",&n);
     if (n>mn){
        mn = n;
        position = i;
     }
     
     i++;
     }
     printf("o maior numero é: %d posicao %d\n", mn, position);

    return 0;
}
