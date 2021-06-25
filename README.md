# EstudosAngular
<i>Destinado aos estudos de Angular e JavaScript</i>

Feito pensando em SPA's (Single Page Applications)
main.ts --> AppModule

baseado em componentes modularizados - encapsulamento (divisão em componentes dentro de módulos)
dentro de AppModule existe um atributo chamado bootstrap
aponta para AppComponet --> quando o AppComponent é carregado, o primeiro componente declarado é 
o App-module que carrega a árvore de componentes.


O que é um componente?

Pedaço de código que representa um pedaço da sua tela com html, css e javaScript (TypeScript)
Comportamento, estrutura e estilo.

Estrutura dos arquivos e pastas

* home.component.css
* home.component.html
* home.component.ts

Será referenciado com a notação: <br>
### <b>\<app-home>\</app-home></b>