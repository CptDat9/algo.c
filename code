#include <stdio.h>
#include <stdlib.h>

int main() {
    int t;
    scanf("%d", &t);
    while (t--) {
        unsigned long long n;
        scanf("%llu", &n);
        unsigned long long ans = 0;
        while (n >= 1) {
            ans += n;
            n = n / 2;
        }
        printf("%llu\n", ans);
    }
    return 0;
}
