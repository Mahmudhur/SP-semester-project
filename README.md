#include <stdio.h>
int main(){

    int m = 8;
    int r = (m % 4) + 4;

    for (int i = 1; i <= r; i++){
        for (int j = 1; j<= i;j++){
            printf("%d", j);          
}
        printf("\n");
    }
}
