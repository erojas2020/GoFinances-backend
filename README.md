# GoFinances

Essa será uma aplicação armazena transações financeiras de entrada e saída, onde permiti o cadastro e a listagem dessas transações. 

O Backend foi desenvolvido um API RESFUL com Node.js e TypeScript. 

Inicialmento só tá desenvolvido o backend. 

## Instruções de funcionamento. 

### Cadastro de transações

Para realizar um registro de uma transação tem que enviar o seguinte:

URL: : http: // localhost:3333/repositories/

Metodo: Post

Enviar pelo body no formato Json o seguinte dados:

```
{
  title: "titulo da transação",
  type: "income' ou 'outcome",
  value: "10"

}
```

### Listar as trasações
URL: : http: // localhost:3333/repositories/

Metodo: Get


