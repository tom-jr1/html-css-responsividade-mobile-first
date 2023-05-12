# Base do projeto
Iniciamos adicionando no index um metadado muito importante com nome de viewport. Ele servira para nos 
informa a dimensão da tela que esta acessando nossa aplicação web

~~~ html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, inicial-scale=1.0">
    <title>Alura Books</title>
    <link rel="stylesheet" href="style.css">
</head>
~~~

## Style root
Foi apresentado um conceito de variable css. 
Para criar uma variable css (variavel css) podemos usar a tag **:root{}** e sett nossas variaveis dentro de seu escopo.
Toda variable inicia com dois traços + o nome da var + o valor daquela variable. 
para usar basta declarar uma função onde colocamos um valor de propriedade
Exemplo de uma variable de cor

~~~ css
:root {
--var-background-color: #FFF;
}

body {
background-color: var(--var-background-color);
}
~~~
