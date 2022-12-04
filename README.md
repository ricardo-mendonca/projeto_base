
## 💻 Sobre o projeto

    Produto desenvolvido com base nas aulas do [@LucasSouzaDev](https://www.youtube.com/@LucasSouzaDev).
    Este projeto serve como base para novos projetos, previamente pré configurado, com o basico pronto para o uso, utilizando API.


## ⚙️ Funcionalidades

- [x] Login 
    ```c#
    Chamada
    [POST] https://localhost:44380/v1/login
    {
      "ds_email": "email@hotmail.com",
      "ds_senha": "123456" 
    }
    
    Retorno
    {
       "accessToken":
            "Token Gerado pela API"
     }
    ``` 


- [x] Tela de pagina incial
   ```c#
    Mostra tela com possibilidade de desenvolver melhorias na mesma.
   ```
- [x] Tela de cadastro de Categoria
  ```C#
  Chamado
  https://localhost:44380/v1/GetCategoria?page=1&descricao=a
  
  Retorno
  [
    {
        "id": 37,
        "ds_descricao": "ELETROPAULO",
        "id_usuario": 1,
        "fl_ativo": "1",
        "qtdTotal": 39
    }
  ]
  ```

## 🚀 Como executar o projeto

  - [x] Baixar o projeto
  - [x] alterar o nome da pasta caso queira
  - [x] rodar o comando "npm install"
  - [x] rodar o comando npm start

