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

### Selecionando registros com filtro de menor e igual
 - ```python 
      db.posts.find(data: {$lte: "13-01-2021"})
   ```
