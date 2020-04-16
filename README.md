# NVL-HTML-P10a
formulario
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formularios</title>
</head>
<body>
    <h2 style="text-align: center;">Formulario de clientes</h2>
    <form method="post" action="miservidor.php">
    <div>
        <label for="código postal">Código postal:</label>
        <input id="código postal" type="number">
    </div>
    <div>
        <label for="nivel">Nivel de satisfacción:</label>
        <select id="nivel">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            </select>

    </div>
    <div>
        <label for="email">Email:</label>
        <input id="email" type="text">
    </div>
    <div>
        <label for="negativos">Puntos negativos:</label>
        <textarea id="negativos"></textarea>
    </div>
    <div>
        <label for="positivos">Puntos positivos:</label>
        <textarea name="" id="positivos"  ></textarea>
    </div>
    <div>
        <label for="atencion">Atención al cliente</label>
        <select name="" id="atencion">
        <option value="Excelente">Excelente</option>
        <option value="Bueno">Bueno</option>
        <option value="Regular">Regular</option>
        <option value="Pésimo">Pésimo</option>
        </select>
    </div>
    <div>

        <label for="Entrega">Entrega del producto</label>
        <select name="" id="Entrega">
        <option value="Excelente">Excelente</option>
        <option value="Bueno">Bueno</option>
        <option value="Regular">Regular</option>
        <option value="Pésimo">Pésimo</option>
        </select>
    </div>
    <div>

        <label for="Calidad">Calidad del producto</label>
        <select name="" id="Calidad">
        <option value="Excelente">Excelente</option>
        <option value="Bueno">Bueno</option>
        <option value="Regular">Regular</option>
        <option value="Pésimo">Pésimo</option>
        </select>
    </div>
    <div>

        <label for="Imagen">Imagen de marca</label>
        <select name="" id="Imagen">
        <option value="Excelente">Excelente</option>
        <option value="Bueno">Bueno</option>
        <option value="Regular">Regular</option>
        <option value="Pésimo">Pésimo</option>
        </select>
    </div>
    <div>
    <input type="submit" value="Enviar">
    </div>
</form>
    
</body>
</html>
