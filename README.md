# att10.06

#include <stdio.h>
#include <stdlib.h>

int main(){
	float pesoQuilos;
	
	printf("Digite seu peso: ");
	scanf("%f", &pesoQuilos);
	
	float pesoGramas = pesoQuilos * 1000;
	
	printf("Seu peso em gramas e: %f", pesoGramas);
	
return 0;
}
