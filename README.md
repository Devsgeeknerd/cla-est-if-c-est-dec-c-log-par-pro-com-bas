<!-- Título -->
# Estrutura `if()` — Teoria em C

***Conteúdo da Aula:***

A estrutura `if()` é a equivalente ao `se-então-senão` que vimos em nosso primeiro algoritmo: ela avalia uma expressão **relacional** ou **condicional**.

Caso a expressão retorne **verdadeiro**, o primeiro bloco relacional ao `if()` será executado.

Agora, caso a expressão for **falsa**, podemos criar um bloco relacionado relativo ao `senão`: o bloco `else`.

Este bloco, que é opcional, só será executado caso a condição repassada ao `if()` retorne **falso**.

A sintaxe do `if()` é exibida abaixo:

```c
if (<condição a ser verificada>) {
    // O que fazer se a expressão for verdadeira.
} [ else {
    // O que fazer se a condição for falsa.
}]
```

Vamos voltar à situação que vimos anteriormente:

* O usuário de nosso algoritmo digita um número e nós deveremos escrever uma mensagem dizendo se o número é maior ou não do que 10.

* A verificação a ser repassada para o `if()` é se o número é maior do que 10 ou não.

* A frase que será escrita por nosso algoritmo vai variar de acordo como resultado desta verificação:
  * Se o número for maior que 10, deveremos escrever **“Número maior que 10”**;
  * Caso contrário, deveremos escrever **“Número menor ou igual a 10**”.

Com a estrutura `if()`, teríamos um código similar ao descrito abaixo:

```c
printf("Usuário, digite um número");
int numeroDigitado = 0;
scanf("%d", &numeroDigitado);
if (numeroDigitado > 10) {
    printf("Número maior que 10");
} else {
    printf("Número menor ou igual a 10");
}
```

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-est-if-c-est-dec-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-est-if-c-est-dec-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-est-if-c-est-dec-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-est-if-c-est-dec-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-est-if-c-est-dec-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-est-if-c-est-dec-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
