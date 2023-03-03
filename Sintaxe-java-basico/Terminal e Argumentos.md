# Terminal e Argumentos

Nem sempre executamos nosso programa Java pela IDE, já pensou, nossos clientes tendo que instalar o Eclipse ou VsCode para rodar o sistema em sua empresa ?

Com a JVM devidamente configurada, nós podemos criar um executável do nosso programa e disponibilizar o instalador para qualquer sistema operacional.

## Argumentos

Quando executamos uma classe, que contenha o método main, o mesmo permite que passemos um array `[]` de argumentos, do tipo String. Logo, podemos após a definição da classe a ser executada, informar estes parâmetros, exemplo:

## Scanner

No exemplo anteriore, de argumentos, podemos receber, dados digitados pelo usuário do nosso sistema, porém, tudo precisa estar em uma linha e também é necessário informar os valores nas posições correspondentes. Esta abordagem pode deixar margens de execução, com erro do nosso programa. Para isso, com a finalidade de deixar as nossas entradas de dados mais seguras, Podemos utilizar a entrada de dados via **Scanner**.

A **classe Scanner** tem como objetivo separar a entrada dos textos em blocos, gerando os conhecidos tokens, que são sequências de caracteres separados por delimitadores que por padrão correspondem aos espaços em branco, tabulações e mudança de linha.



![Scanner Java: Como funciona a classe Scanner do Java?](http://arquivo.devmedia.com.br/marketing/img/artigo-como-funciona-a-classe-scanner-do-java-28448.png)

Fontes: https://glysns.gitbook.io/java-basico/sintaxe/terminal-e-argumentos

https://www.devmedia.com.br/como-funciona-a-classe-scanner-do-java/28448#:~:text=A%20classe%20Scanner%20tem%20como,tabula%C3%A7%C3%B5es%20e%20mudan%C3%A7a%20de%20linha.