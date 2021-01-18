# Primeiros comandos mongodb

## Iniciando / Criando um novo banco de dados 
 - use dbmidias 
 - Cria o banco de dados dbmidias
 
## Criando uma nova coleção
 - ```python 
      db.posts.insert() 
    ```
 - Cria a coleção posts e com as informações contidas método insert
 
## Exemplo de inserção de múltiplos documentos 
 - 
 ```python
 db.posts.insert([{nome: "Antônio Soares", postagem: "Produto com defeito", data: "17-01-2021"}]) 
 ``` 
### Selecionando todos os registros de uma coleção
 - ```python 
      db.posts.find() 
    ```

### Selecionando todos os registros de uma coleção com apresentação amigável
 - ```python 
      db.posts.find().pretty() 
    ```
### Selecionando um registro pra analisar a estrutura
 - ```python 
      db.posts.findOne()
    ```

### Selecionando um registro com filtro
 - ```python 
      db.posts.find({nome: "Andréia Gonçalves"})
    ```
