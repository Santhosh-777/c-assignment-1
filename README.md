#include <stdio.h>

int main() {
    int i;
    float num = 1.0;

    for (i = 1; i <= 10; i++) {
        printf("%d   %.2f\n", i, num);
        num += 0.1;
    }
}
