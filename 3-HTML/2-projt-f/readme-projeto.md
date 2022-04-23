# 🤞 Descrição do projeto
Como até esse momento só foi apresentado os conceitos de HTML, não vamos poder usar CSS e JS para poder desenvolver o site da melhor maneira possível. Mas conseguimos fazer um projeto bem bacana, com diversas imagens e páginas.

## Apresentando os conceitos

### Corpo principal

Como no caso desse site não podemos usar CSS, vamos ter que usar tabelas para pode estruturar tudo o que precisamos da forma mais notável possível. 

Tabelas são estruturas da seguinte forma

1. Precisamos definir primeiro a tabela 'principal', usando a tag *<table>*
2. Em seguida precisamos definir as linhas com as tags *<tr>* 
3. Posteriormente precisamos definir as colunas usando as tags *<td>* 

Podemos adicionar alguns atributos que nos permitem melhorar a visualização das tabelas, como *border* (bordas), *width* (largura) e *align* (alinhamento).

```html
      <table border="1" width="600" align="center">
```

### Adicionando imagem ao background

Nesse contexto, vamos adicionar a imagem de background. Como vamos fazer um arranjo simples e usando HTML puro, vamos ter que fazer dentro da tag `<body>`
``` html
<body background="/3-HTML/2-projt-f/arquivos-projetos-unes/arquivos-necessarios-projetos-unes/fundo.png ">
```
*O que está entre " " é o caminho do arquivo*

Para adicionarmos uma imagem dentro da tabela simples, obviamente usando só HTML, vai ser preciso usar a tag de `<img>` dentro da tag da tabela `<td>`
``` html
<td height="89" > <img src="/3-HTML/2-projt-f/arquivos-projetos-unes/arquivos-necessarios-projetos-unes/logo.png"> </td>
```

Após isso é basicmente usando a mesma norção de programação dentro das tags do HTML.