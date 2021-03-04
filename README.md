# HtmlJavaScript
comando básicos de html e estudo do DOM 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background: rgb(68, 88, 119);
            color: white;
            font: normal 17pt Arial;
        }
    </style>
</head>
<body>
        <h1> DOM</h1>
        <p>Aqui vai o resultado</p>
        <p>Aprendendo a usar <strong>DOM </strong>em JavaScript</p>
        <div id='msg'>clique em mim </div>
        <script>
            var corpo = window.document.body
            var p1 = window.document.getElementsByTagName('p')[1]
            /* 
                             ID
            var d = window.document.getElementById("msg")
            
            d.style.background = 'green'
            d.innerText = 'Estou aguardando...'
            window.document.getElementById('msg').innerText = 'Olá!' */
            
            
            
        </script>
</body>
</html> 
