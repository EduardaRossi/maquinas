<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Favoritos</title>
</head>
<body>
    <center>
        <h1>Seleção de Componentes para Sistemas Automatizados em Eletroeletrônica</h1>
        <script>
            //criar uma variavel
            var opcao = parseInt(prompt(`Seu componente escolhido é: 
            1 - Relé
            2 - Sensor de próximidade
            3 - Controlador Lógico Programável (CLP)
            4 - Servomotor
            5 - Encoder
            6 -  Fonte de Alimentação`))
        switch(opcao) {
            case 1:
            document.write("Seu componente escolhido é: Relé")
            break;
            case 2:
            document.write("Seu componente escolhido é: Sensor de Próximidade")
            break;
            case 3:
            document.write("Seu componente escolhido é: Controlador Lógico Programável (CLP)")
            break;
            case 4:
            document.write("Seu componente escolhido é: Servomotor")
            break;
            case 5:
            document.write("Seu componente escolhido é: Encoder")
            break;
            case 6:
            document.write("Seu componente escolhido é: Fonte de Alimentação")
            break;
            default:
            document.write("Opção inválida")
        }
        </script>
    </center>
</body>
</html>
