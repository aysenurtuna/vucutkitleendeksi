#include <stdlib.h>
#include <stdio.h>
#include <math.h>

int main() { 
     int kilo;
     float boy;
     float sonuc;
     printf("Vucut kitle endeksi hesaplama\n\n");
     printf("***************\n\n");
     printf("Boyunuzu m cinsinden giriniz: \n",boy);
     scanf("%f",&boy);
     printf("Kilonuzu kg cinsinden giriniz: \n",kilo);
     scanf("%d",&kilo);
     sonuc=kilo/(boy*boy);
     printf("Vucut kitle endeksiniz: %2.2lf\n",sonuc);
        if (18.5>sonuc) {
	       printf("Olmaniz gereken kilodan zayifsiniz.");} 
       	else if (24.9>sonuc && sonuc>19.0) {
		    printf("Saglikli kilodasiniz.");}
        else if (29.9>sonuc && sonuc>25.0){
                printf("Olmaniz gereken kilodan fazla kilolusunuz.");}
        else
                printf("Obezsiniz. Lutfen bir doktora gorunun.");
		
	return 0;
	system("pause");
}
