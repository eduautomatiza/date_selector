<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seleção de Datas</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        /* Estilos básicos */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            transition: background-color 0.3s, color 0.3s;
        }

        h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }

        label {
            font-size: 1em;
            display: block;
            margin-top: 10px;
        }

        input[type="date"] {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            font-size: 1em;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
            transition: background-color 0.3s;
        }

        button {
            width: 100%;
            padding: 12px;
            font-size: 1em;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.2s ease, color 0.2s;
        }
    </style>
</head>
<body>
    <h3>Selecione as datas:</h3>
    <label>Data Inicial:</label>
    <input type="date" id="start_date">
    
    <label>Data Final:</label>
    <input type="date" id="end_date">
    
    <button onclick="sendData()">Enviar</button>

    <script>
        function applyTheme() {
            const theme = Telegram.WebApp.themeParams;
            document.body.style.backgroundColor = theme.bg_color || "#ffffff";
            document.body.style.color = theme.text_color || "#000000";
            document.querySelector("h3").style.color = theme.button_color || "#0088cc";

            const inputElements = document.querySelectorAll("input[type='date']");
            inputElements.forEach(input => {
                input.style.backgroundColor = theme.bg_color || "#f9f9f9";
                input.style.borderColor = theme.hint_color || "#ddd";
                input.style.color = theme.text_color || "#000000";
            });

            const button = document.querySelector("button");
            button.style.backgroundColor = theme.button_color || "#0088cc";
            button.style.color = theme.button_text_color || "#ffffff";
        }

        function sendData() {
            const startDate = document.getElementById("start_date").value;
            const endDate = document.getElementById("end_date").value;

            if (startDate && endDate) {
                Telegram.WebApp.sendData(JSON.stringify({ start_date: startDate, end_date: endDate }));
                Telegram.WebApp.close();
            } else {
                alert("Por favor, selecione ambas as datas.");
            }
        }

        // Aplica o tema assim que o Web App é carregado
        Telegram.WebApp.onEvent("themeChanged", applyTheme);
        applyTheme();
    </script>
</body>
</html>
