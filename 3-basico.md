# Sintaxe básica

### Olá Mundo em C
```
include <stdio.h>

int main() {
	
	printf ("Olá, Mundo!");  /*função printf() escreve Olá, Mundo!*/

}
```
*Este pequeno programa nos ajuda a entender varios conceitos básicos relacionado a programação com C.*


## Funções

*Funções são pequenos programas que são usados para tarefas especificas.<br> 
Por exemplo, este programa utiliza duas funções:<strong>main()</strong> e <strong>printf()</strong>.<br>
A função <strong>main()</strong> inicia a execução do programa e a outra função, <strong>printf()</strong> é utilizada para printar na<br> tela uma ou mais informações.*  

## Comentários

*Um programa em C especifica um determinado comentário desta forma ```/* */```. Isto serve para durante o código realizar comentários que<br>servem de documentação.*

## Compilador

*Existe a possibilidade de rodar um programa escrito em C via linha de comando (terminal). Para isso primeiro é necessário compilar o<br>
arquivo que contém o programa. Como exemplo vamos utilizar o arquivo test.c*

```gcc test.c -o demo   /*compilando o arquivo test.c*/```

*Se tudo ocorreu sem erros, então, foi produzido um arquivo binário chamado demo*

```./demo   /*arquivo binário */```

*Ao executar, o computador entra dentro do programa a partir do <strong>main()</strong> e encontra uma instrução <strong>printf()</strong>.<br> Assim, a função <strong>printf()</strong> instrui o computador a imprimir a informação na tela.<br>
Após isso, ele encontra o fechamento do programa ```}```, que indica o fim da função <strong>main()</strong> e sai do programa.*

```a.out    /*executando o arquivo */```


<br><br>



### Fonte de referência:
https://www.tutorialspoint.com/computer_programming/index.htm