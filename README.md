# vetores
vetores

#include <stdio.h>

int main() {
    int numeros [5];
    printf("digite 5 numeros:\n");
    for(int i = 0 ; i < 5; i++){
        scanf("%d", &numeros [i]);
    }
    printf(" os numeros digitados foram: \n");
    for( int i = 0 ; i < 5 ; i++){
    printf("%d", numeros [i]);
    
    }
printf("\n");
    return 0;
}
