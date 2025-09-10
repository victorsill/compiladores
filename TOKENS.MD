Definição de Lexemas e Tokens da Linguagem P-

Palavras-chave

| Lexema     | Token        |
| `programa` | TK_PROGRAMA  |
| `var`      | TK_VAR       |
| `int`      | TK_INT       |
| `começar`  | TK_COMECAR   |
| `se`       | TK_SE        |
| `então`    | TK_ENTAO     |
| `escreva`  | TK_ESCREVA   |
| `fim`      | TK_FIM       |

 Identificadores

| `x`     | TK_ID |
| `y`     | TK_ID |
| `teste` | TK_ID |

 Números

| `42`    | TK_NUM  |
| `3`     | TK_NUM  |
| `10`    | TK_NUM  |


Operadores

| Lexema | Token      |
|--------|------------|
| `:=`   | TK_ASSIGN  |
| `+`    | TK_PLUS    |
| `>`    | TK_GT      |


| Lexema | Token     |
|--------|-----------|
| `;`    | TK_SEMI   |
| `,`    | TK_COMMA  |
| `:`    | TK_COLON  |
| `(`    | TK_LPAREN |
| `)`    | TK_RPAREN |
| `.`    | TK_DOT    |


| Token  | Descrição                  |
|--------|----------------------------|
| TK_EOF | Fim de arquivo (end of file) |


 Observações
Todos os **identificadores** (nomes de variáveis, funções, etc.) são classificados como `TK_ID`.  
Todos os **números inteiros** são classificados como `TK_NUM`.  
Palavras-chave são reservadas e não podem ser usadas como identificadores.  
Essa tabela deve servir de referência para a implementação do scanner (analisador léxico).
