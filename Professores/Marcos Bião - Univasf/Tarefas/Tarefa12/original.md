
Considere o seguinte código:

```c
#include <stdio.h>

int main() {
    int a = 0;

    for (int i = 1; i < 10; i++) {
        if (i == 3 || i == 5) {
            continue;
        }

        if (i == 9) {
            break;
        }

        a += i;
    }

    printf("Valor final de a: %d\n", a);
    return 0;
}
```
Qual será o valor final da variável a após a conclusão da execução?

Explique todos os fatores que contribuíram para que a variável alcançasse esse valor.