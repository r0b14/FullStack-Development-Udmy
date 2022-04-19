# 🤞 Descrição do projeto
Como até esse momento só foi apresentado os conceitos de HTML, não vamos poder usar CSS e JS para poder desenvolver o site da melhor maneira possível. Mas conseguimos fazer um projeto bem bacana, com diversas imagens e páginas.

## Apresentando os conceitos

Como no caso desse site não podemos usar CSS, vamos ter que usar tabelas para pode estruturar tudo o que precisamos da forma mais notável possível. 

Tabelas são estruturas da seguinte forma

1. Precisamos definir primeiro a tabela 'principal', usando a tag *<table>*
2. Em seguida precisamos definir as linhas com as tags *<tr>* 
3. Posteriormente precisamos definir as colunas usando as tags *<td>* 

Podemos adicionar alguns atributos que nos permitem melhorar a visualização das tabelas, como *border* (bordas), *width* (largura) e *align* (alinhamento).

```html
ˋˋˋ
<!DOCTYPE html>
<html lang="en">

   <head>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>IENJ</title>
   </head>

   <body>

      <table border="1" width="600" align="center">
         <tr>
            <td>Logo</td>
            <td>Menu</td>
         </tr>
      </table>

   </body>
</html>
ˋˋˋ
```
