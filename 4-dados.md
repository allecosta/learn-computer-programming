# Tipos de Dados

- byte
- int
- long
- double
- float
- char
- string
- arrays

... entre outros


## Declaração de variáveis em C

```
include <stdio.h>

int main() {

   int a;
   int b;  /* ou poderia ser declarado como: int a, b; * /

}
```

*Neste exemplo, foram criadas duas variáveis, a e b, ou seja, dois espaços em memória, do tipo inteiro.*

*No PHP não é necessário declarar tipos de variáveis, porém é necessário iniciar com o simbolo de $, como podemos ver no exemplo abaixo:*
```
<?php

	$a;
	$b;

?>
```


*Só isso, e apenas isso, diz aí, PHP é ou não é a melhor do mundo? rsrsrs*

*Mas dando continuidade ao exemplo em C, outra forma, como exemplo, de se declarar é já inicializar a variável com<br>valores, note que a variável a recebe o valor 10, e a variável b recebe o valor 20.*
```
include <stdio.h>

int main() {

   int a = 10;
   int b = 20;  

}
```

<br><br>

### Fonte de referência:
https://www.tutorialspoint.com/computer_programming/index.htm