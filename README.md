# **Data e hora**

## ``Índice``

* [Estrutura do HTML](#estrutura-do-html)

## ``Data e hora``

Este código é um simples script em JavaScript que imprime a data e hora atual no navegador da web. Ele utiliza a função Date() do JavaScript para obter a data e hora atual e, em seguida, usa document.write() para exibi-la no documento HTML.

## ``Como funciona``

* document.write(Date());: Este é o código JavaScript dentro da tag script. Vamos dividir isso em duas partes:

* Date(): Este é um construtor de objeto em JavaScript que cria um novo objeto de data, representando a data e hora atuais. Quando chamado sem argumentos, ele retorna a data e hora atual do sistema.

* document.write(): Este é um método em JavaScript que escreve o conteúdo especificado diretamente no documento HTML que está sendo renderizado. Aqui, estamos passando o resultado de Date() para document.write(), o que significa que a data e hora atuais serão escritas diretamente no documento HTML.

## ``Estrutura do HTML``

```html
<!-- Código HTML -->

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Data e Hora</title>
</head>
<body>
    <h1>Data e Hora Atual</h1>
    <script type="text/javascript">document.write(Date());</script>
</body>
</html>
```

## ``Nota``

* Este script não oferece nenhum tipo de interatividade com o usuário. Ele simplesmente mostra a data e hora no momento em que a página é carregada.
* Para personalizar a exibição da data e hora, é possível usar métodos da classe Date em JavaScript para formatá-la de acordo com suas preferências.

