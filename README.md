# factorial-program
#factorial program in c


#include <stdio.h>
#factorial program in c
int main() {
   int n,i,factorial=1;
   printf("\n enter number:");
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
       factorial=factorial*i;
   }
   printf("Factorial of number %d is %d\n",n,factorial);
}
/*OUTPUT:
enter number:5
Factorial of number 5 is 120
*/
