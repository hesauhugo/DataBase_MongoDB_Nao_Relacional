## Filtros pelo shell
* filtrando apenas colorido `db.produtos.find({Cor:"Colorido"})` 
* colorido retornando apenas nome e preço `db.produtos.find({Cor:"Colorido"},{Preco:1,Nome:1})` 
* fazendo sort: `db.produtos.find({Cor:"Colorido"},{Preco:1,Nome:1}).sort({Preco:-1})`
* buscando valores menores ou iguais a 50 reais
    * `db.produtos.find({Cor:"Colorido",Preco:{$lte:50}},{Preco:1,Nome:1,_id:0}).sort({Preco:-1})`
