# Documentação



Uma das maiores características da linguagem Java é que, desde suas primeiras versões, tínhamos em nossas mãos, uma documentação rica e detalhada dos recursos da linguagem.

Conforme site oficial, podemos compreender e explorar, todos os recursos organizados por pacotes e classes bem específicas, sem nem mesmo escrever uma linha de código.

Hoje, costuma-se afirmar que, para se tornar um desenvolvedor nível avançado, é um requisito imprescindível adquirir a habilidade de compreender, a documentação oficial da linguagem e dos frameworks que são incorporados nos projetos atuais.

Aqui, temos o link da documentação de uma das principais classes da linguagem Java:

https://docs.oracle.com/javase/7/docs/api/java/lang/String.html

## Tags

Mas e quais as informações, que obtemos através de classes documentadas, na linguagem ? Java Documentation é composto por tags que, representam dados relevantes para a compreensão da proposta de uma classe e os conjuntos de seus métodos e atributos conforme tabela abaixo:

| Tag      | Descrição                                              |
| -------- | ------------------------------------------------------ |
| @autor   | Autor / Criador                                        |
| @version | Versão do recurso disponibilizado                      |
| @since   | Versão / Data de início da disponibilização do recurso |
| @param   | Descrição dos parâmetros dos métodos criados           |
| @return  | Definição do tipo de retorno de um método              |
| @throws  | Se o método lança alguma exceção                       |



## Javadoc

**Javadoc** é um gerador de documentação criado pela [Sun Microsystems](https://pt.wikipedia.org/wiki/Sun_Microsystems) , para documentar a [API](https://pt.wikipedia.org/wiki/API) dos programas em [Java](https://pt.wikipedia.org/wiki/Linguagem_de_programação_Java), a partir do [código-fonte](https://pt.wikipedia.org/wiki/Código-fonte). O resultado é expresso em [HTML](https://pt.wikipedia.org/wiki/HTML). É constituído, basicamente, por algumas marcações muitos simples, inseridas nos comentários do programa.

Este sistema, é o padrão de documentação de classes em Java, onde muitas das [IDEs](https://pt.wikipedia.org/wiki/Ambiente_de_desenvolvimento_integrado) desta linguagem irão automaticamente gerar um Javadoc em [HTML](https://pt.wikipedia.org/wiki/HTML).

### Entendendo a sintaxe

A estrutura básica de um comentário de documentação tem como característica principal, o uso de uma barra e dois asteriscos /** no início e no seu final, possui um asterisco e uma barra */. Veja as **listagens 01** e **02**.

```
/** Exemplo básico de um comentário em JavaDoc */
```

**Listagem 01**. Uma linha

```
/** Exemplo básico de um comentário em JavaDoc
 * com mais de uma linha.
 */
```

**Listagem 02**. Várias linhas

Por convenção, como comentei anteriormente, sugere-se alocar os blocos de comentários, antes da definição de uma classe, interface, atributos, ou métodos, dessa forma, criamos uma introdução conceitual ao referido elemento do código



Fontes:https://glysns.gitbook.io/java-basico/sintaxe/documentacao

https://www.devmedia.com.br/javadoc-implementando-documentacao-atraves-do-netbeans/2495

