# Calculadora com Html, CSS, Bootstrap e JavaScript


## Importando Bootstrap no projeto

Utilizando html, css, bootstrap e JavaScript, podemos criar uma calculadora bem estilizada e funcional, e o melhor: é simples. 

Primeiro criaremos uma pasta para guardar nossos arquivos. Por exemplo: calculadora. Dentro dessa pasta criaremos um documento com o nome de calculadora.html. 

A estrutura desse arquivo será assim:

 `````````html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Calculadora</title>
</head>
<body>  
</body>
</html>
 ````````````
O próximo passo será acrescentar ao projeto o Bootstrap, você poderá importar através de CDN, essa é a forma de importar no seu projeto via link. Veja um exemplo:


````````````````````````````````````````
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

````````````````````````````````````````

````````````````````````````````````````
<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
``````````````````````````````````````````

````````````````````````````````````````````````````````````
<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
````````````````````````````````````````````````````````````

Essas linhas acima são importadas dentro da tag ``<head>``do html, então teriamos algo assim:

``````````````````````````````````````````````````````
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    <title>Calculadora</title>
</head>
<body>
    
</body>
</html>

``````````````````````````````````````````````````````
Mas essa prática de importar via CDN não é muito interessante, pois se o link for alterado ou retirado do ar, sua aplicação não poderá encontrar o link e perderá a estilização. Portanto, iremos baixar a dependência e alocarmos no projeto.

Para isso acessar o site do Bootstrap: https://getbootstrap.com/. Na tela inicial clicar em "Dowloand". 

Após realizar o Download, extrair a pasta dentro do projeto.

Feito isso, na tag ``<head>`` adicionaremos dois links:

```````````````````````````
<link rel="stylesheet" href="bootstrap-4.4.1-dist/css/bootstrap.min.css">

<script src="bootstrap-4.4.1-dist/js/bootstrap.min.js"></script>

``````````````````````````````
O primeiro refere-se ao CSS do Bootstrap e o segundo ao JavaScript do Bootstrap.

Pronto! Bootstrap já está adicionado ao nosso projeto.

## Mão na massa: Criando o Html














