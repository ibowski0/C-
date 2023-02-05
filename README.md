#include <stdio.h>
#include <stdlib.h>

int main() {
float s1,s2;
char secim;
printf("birinci sayiyi giriniz ="); scanf("%f",&s1);
printf("karakter secin[+,-,*,/] = "); scanf("%s",&secim);
printf("ikinci sayiyi giriniz =");  scanf("%f",&s2);
switch(secim)
{
case '+' : printf("toplama islemi sonucu= %f",(s1+s2)); break;
case '-' : printf("fark islemi sonucu= %f",(s1-s2)); break;
case '*' : printf("carpim islemi sonucu= %f",(s1*s2)); break;
case '/' : printf("bolum islemi sonucu= %f",(s1/s2)); break;

}


	return 0;
}



