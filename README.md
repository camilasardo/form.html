<html>
    <head>
        <meta charset="UTF8">
        <title>
            Formulário de exemplo
        </title>
        <link rel="stylesheet" type="text/css" href="css/estilo.css">
    </head>
    <body>
        <h1>Formulário de exemplo</h1>
        <form id="frmTeste" name="frmTeste" onsubmit="calculaInss(); return false">
        <div>
            <label for="salario">Salário: </label>
            <input type="number" id="salario" name="salario" />
        </div>
        <br />
        <div>
            <button type="submit">Calcular</button>
        </div>
        <br />
        <div id="resultado">
            &nbsp;
        </div>
        </form>
        <script src="javascript/inss.js"></script>
    </body>
</html>
