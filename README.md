# Proyecto_kris

<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title><3</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: rgb(72, 105, 53);
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('ahora cojamos en el monte<3 (creado por kristian)');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>
<body>
    <h3>Quieres ser mi vieja<3?</h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src="chuec.png" width="200">
</body>
</html>
