# Operadores

*Um operador em uma linguagem de programação é um simbolo, compilado ou interpretado, que resolve uma matemática especifica,<br>
operação lógica ou relacional que produz um resultado final.*

## Operadores Aritméticos

*Programas de computadores são usados para calculos matemáticos.<br>
Nós podemnos escrever um programa simples de calculo de adição entre dois números ```(2 + 3)```<br>
e podemos escrever um programa que resolve uma equação complexa  ```P(x) = x4 + 7x3 - 5x + 9.```<br>
Na primeira expressão 2 e 3 são operandos, ```+``` é um operador, conceito similiar existente na programação de computadores.*<br> 

*Segue o dois exemplos:*
```
2 + 3

P(x) = x4 + 7x3 - 5x + 9. 
```

*Estes dois exemplos são expressões aritméticas, de forma similar, uma linguagem de programação possui vários operadores aritméticos.<br>
A tabela abaixo lista os importantes operadores aritméticos disponivel na linguagem C.<br>
A variável a assume o valor 10, e b assume o valor 20.*<br>
```
+		a + b = 30		(Soma os dois operandos)

-		a - b = -10		(Subtrai o segundo operando pelo o primeiro)

* 		a * b = 200		(Multiplica os dois operandos)

/ 		b / a = 2		(Divide o numerador pelo denominador)

%		b % a = 0		(O resto da divisão inteira)
```
<br>

*Segue um simples exemplo na linguagem C, para entender os operadores matemáticos.*
```
int main() {
   int a, b, c;
   
   a = 10;
   b = 20;
   
   c = a + b;   
   printf( "Valor de c = %d\n", c);
   
   c = a - b;   
   printf( "Valor de c = %d\n", c);
   
   c = a * b;   
   printf( "Valor de c = %d\n", c);
   
   c = b / a;   
   printf( "Valor de c = %d\n", c);
   
   c = b % a;   
   printf( "Valor de c = %d\n", c);
}
```
- Resultado:
```
Valor de c = 30
Valor de c = -10
Valor de c = 200
Valor de c = 2
Valor de c = 0
```


## Operadores relacional

*Considerando a situação, criamos duas variáveis:* 
```
a = 20, e b = 10		

(a > b)
```
*Aqui, nós usamos o simbolo ```>``` um operador relacional, que produz resultado booleano<br>
Segue abaixo uma lista da tabela com importantes operadores relacionais disponivel na linguagem de programação C.*<br>

*A variável a assume o valor 10, e a variável b assume o valor 20.*

```
==		(a == b) não é verdadeiro.

verifica se o valor dos dois operandos são iguais ou não, se sim, a condicional é verdadeira.


!=		(a != b) é verdadeiro.

verifica se o valor dos dois operandos são iguais ou não, se os valores não são iguais a condicional é verdadeira.


>		(a > b) não é verdadeiro.

verifica se o valor do operando da esquerda é maior que o valor do operando da direita, se sim, a condicional é verdadeira.


<		(a < b) é verdadeiro.

verifica se o valor do operando da esquerda é menor que o valor do operando da direita, se sim, a condicional é verdadeira.


>=		(a >= b) não é verdadeiro.

Verifica se o valor do operando da esquerda é maior ou igual ao valor do operando da direita, se sim, a condicional é verdadeira.

<=		(a <= b) é verdadeiro.

Verifica se o valor do operando da esquerda é menor ou igual ao valor do operando da direita, se sim, a condicional é verdadeira.
```

*Abaixo segue um exemplo em C, usando a condicional if.*
```
include <stdio.h>

int main() {
   int a, b;
   
   a = 10;
   b = 20;
   
   if( a == 10 ) {
	   
      printf( "a é igual a 10\n");
   }
   
   if( b == 10 ) {
	
      printf( "b é igual a 10\n");
   }
   
   if( a < b ) {
	
      printf( "a é menor que b\n");
   }
   
   if( a != b ) {
	
      printf( "a não é igual a b\n");
   }
}
```
- Resultado:
```
a é igual a 10
a é menor que b
a não é igual a b
```

*Note que o resultado de ```(b == 10)``` não foi printado, isso ocorreu porque é falso.*


## Operadores lógicos

*Operadores lógicos são muito importantes em uma linguagem de programação, e ajuda nas decisões baseadas em certas condições.<br>
Supondo que combinamos o resultado de duas condições, AND e OR operadores ĺógicos, que ajuda o resultado final.<br>
Seque a tabela com operadores lógicos suportados na linguagem C.
A variável a assume o valor 1 e a variável b o valor 0.*
```
&&		(a && b) é falso.

||		(a || b) é verdadeiro.

!		!(a && b ) é verdadeiro.
```

*Segue exemplo abaixo para entender os operadores lógicos disponivel em C.*
```
include <stdio.h>

int main() {
   int a = 1;
   int b = 0;

   if ( a && b ) {
	
      printf("Nunca será printado porque essa condição é falso\n" );
   }
   if ( a || b ) {
	
      printf("Foi printado porque essa condição é verdadeira\n" );
   }
   if ( !(a && b) ) {
	
      printf("Foi printado porque essa condição é verdadeira\n" );
   }
}
```
- Resultado:
```
Foi printado porque essa condição é verdadeira
Foi printado porque essa condição é verdadeira
```
<br><br>

### Fonte de referência:
https://www.tutorialspoint.com/computer_programming/index.htm
