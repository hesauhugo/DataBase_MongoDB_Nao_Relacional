## Realizando select pelo compas
* Clica em options
* Em filter: Digitar `{Cor:"Colorido"}`, é como se fosse um where
    * Clicar em `Find` 
* Em project `{Nome:1,Preco:1}`, é para retornar apenas as colunas desejadas
* Em project `{Nome:1,Preco:1, _id:0}`, passndo o 0 no _id é ocultada a coluna _id
* Em sort  `{Preco:1}` , para ordenar os dados de forma crescente
* Em sort `{Preco:-1}`, para ordenar os dados de forma decrescente
