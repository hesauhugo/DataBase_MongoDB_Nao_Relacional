# Atualizando um documento
* atualizando o id 3 passando o preco 1

```console
    db.produtos.updateOne(
    {Id:3},
    {$set:{Preco:1}}
    )
```