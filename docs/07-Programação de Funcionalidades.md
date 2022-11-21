# Programação de Funcionalidades

Nesta seção, será apresentada as telas desenvolvidas de acordo com a especificação de cada Requisito Funcional:

Tela - Home Page

A tela principal apresenta de modo geral as espefificações do consumo da Comida Low Carb, seus benefícios, indicação de alimentos e como uma dieta preventiva pode acarretar inúmeros benefífios à saúde.  

 <img id = "figma" src="../docs/img/Figura_3_Tela_Home_Page_revogado.png" width=1000px>
Figura 1 - Tela Home-Page 

<br>

<strong> Requisitos atendidos:</strong>

<br>

● RF-01: A seção Home é o portal de entrada, contendo um menu fixo para suas 3 seções, sendo elas: Low Carb – o que é e benefícios, Alimentos e Saúde preventiva.

<strong>Artefatos da funcionalidade</strong>
<br>
● index.html<br>
● Modelologo.png <br>
● style.css

<strong>Estrutura de Dados</strong>
<br>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="../src/css/home.css">
    <title>Ideias Saudáveis - Comida Low Carb</title>
</head>
<body>

    <div class="header">
        <img id = "logop" src="../docs/img/Modelologo.png" width=100px>
    </div>

    <div id="section1">
            <p>
            <h3> <a href="conceituando.html">Low Carb</a></h3>
            <h4> O que é</h4>
            <h4> Beneficios</h4>
            </p>
    </div>

    <div id="section2">
            <p>
                <h3> <a href="alimentos.html">Alimentos</a></h3>
            <h4> O que pode ser consumido</h4>
            <h4> O que não pode ser consumido</h4>
            </p>
    </div>

    <div id="section3">
            <p>
            <h3> Cardápios</h3>
            <h4> Café da manhã</h4>
            <h4> Lanche da manhã</h4>
            <h4> Almoço</h4>
            <h4> Lanche da tarde</h4>
            <h4> Jantar</h4>
            </p>
    </div>

    <div id="section4">
            <p>
            <h3> Saúde preventiva</h3>
            <h4> Prevenção de doenças</h4>
            </p>
    </div>

    <div id="section5">
            <p>
            <h3> Matérias</h3>
            <h4> Depoimentos</h4>
            <h4> Notícias</h4>
            </p>
    </div>

    <div id="section6">
            <p>
            <h3> Fale conosco</h4>
                <h4> substituir por icones</h4>
            </p>
    </div>
    
    <div id="col">
            <img id = "logo" src="../docs/img/Modelologo.png" width=600px>            
    </div>   
      
    
</body>
</html>