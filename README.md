#include
#include

int main() {
float x, y, a;
for (y = 1.5; y > -1.5; y -= 0.05) {
for (x = -1.5; x < 1.5; x += 0.05) {
a = x * x + y * y;
putchar(a < 1 ? '*' : ' ');
}
}
system("color 0c");
putchar('\n');
return 0;
}
陈佳豪到此一尿
