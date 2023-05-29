# Realizando insercoes
* No mongo compas desktop
* Abrir a base criada na coleção criada
* Add data
    * Insert Document

```json
    {
        "Id":49,
        "Nome":"NOVO PRODUTO MONGO",
        "Cor": "COLORIDO",
        "Preco":31.50,
        "Tamanho":"P",
        "Genero": "M",
        "DataCadastro": "2023-05-07T16:35.13.78666663"
    }
```

```json
    {
        "Id":49,
        "Nome":"NOVO PRODUTO MONGO",
        "Preco":31.50,
        "Tamanho":"P",
        "Genero": "M",
        "DataCadastro": "2023-05-07T16:35.13.78666663"
    }
```
## Shell Mongo
* No canto inferioro esquerdo tem o `Mongosh` que é o shell do mongo, clique para abrir

* para trocar de database `dio` 

```psh
    use dio
```

* para inserir um documento 
```psh
    db.produtos.insertOne({
        "Id":51,
        "Nome":"NOVO PRODUTO MONGO VIA COMANDO",
        "Cor": "COLORIDO",
        "Preco":31.50,
        "Tamanho":"P",
        "Genero": "M",
        "DataCadastro": "2023-05-07T16:35.13.78666663"
    })
```
* Clicar em refresh