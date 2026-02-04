#include <stdio.h>
// 1. Para que serve #include <stdio.h>?
// É a biblioteca que permite usar printf() para mostrar coisas na tela.
// Sem ela, não dá pra usar printf().

int main(void) 
// 2. Onde o programa começa?
// Sempre começa aqui na main(). É a primeira função que o computador executa.

{
    printf("Hello, World!\n");
    
    // 4. O que acontece se remover o \n?
    // Sem \n, o próximo texto fica na MESMA LINHA.
    // Exemplo: "Hello, World!Texto seguinte" → tudo colado.
    
    return 0;
    // 3. O que acontece se remover o return 0?
    // Normalmente funciona igual, mas pode dar aviso.
    // É bom usar: 0 = sucesso, 1 = erro.
}