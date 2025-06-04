#include <stdio.h>

int main() {
    
    int a, b, c;
    printf("Введите три числа a, b, c:\n");
    //Пример: a = -1, b = 2, c = 3
    scanf("%d %d %d", &a, &b, &c); 
    
    // Для проверки на наличии нулей
    int isZero = (a == 0) || (b == 0) || (c == 0); // isZero = 0
    
    /* Проверяет является ли число a, b, c отрицательным, 
    если да, то в переменную записывается 1, иначе 0 */
    //Пример: isANegative = 1, isBNegative = 0, isCNegative = 0
    int isANegative = a < 0, isBNegative = b < 0, isCNegative = c < 0; 
    
    // Счетчки отрицательныx чисел
    int negativeNumCount = isANegative + isBNegative + isCNegative; // 1
    // Для определения знака
    int compisitionSign = (1 - isZero) * (1 - 2 * (negativeNumCount % 2)); 
    /* Пример:
    compisitionSign = (1 - 0) * (1 - 2 * (1 % 2)) 
     compisitionSign = 1 * (-1) = -1
     */
    
    printf("%d", compisitionSign); //Вывод: -1
    return 0;
}
