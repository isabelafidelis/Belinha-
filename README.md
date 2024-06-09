# Belinha-
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Namoro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #no {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            margin: auto;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Pedido de Namoro</h1>
    <p>Você quer namorar comigo? 🤔</p>
    <button id="yes">Sim! 😊</button>
    <button id="no">Não... 😔</button>

    <script>
        const noButton = document.getElementById('no');
        const yesButton = document.getElementById('yes');

        noButton.addEventListener('mouseover', () => {
            noButton.style.top = `${Math.random() * window.innerHeight}px`;
            noButton.style.left = `${Math.random() * window.innerWidth}px`;
        });

        yesButton.addEventListener('click', () => {
            alert('Parabéns! Você aceitou o pedido de namoro! 🎉');
        });
    </script>
</body>
</html>
