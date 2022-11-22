# Programação de Funcionalidades

Nesta seção, será apresentada as telas desenvolvidas de acordo com a especificação de cada Requisito Funcional:

 <strong>Tela - Home Page</strong>

A tela principal apresenta de modo geral as espefificações do consumo da Comida Low Carb, seus benefícios, indicação de alimentos e como uma dieta preventiva pode acarretar inúmeros benefífios à saúde.  

 <img id = "figma" src="../docs/img/Figura_3_Tela_Home_Page_revogado.png" width=1000px>
Figura 1 - Tela Home-Page <br>

<br>

<strong> Requisitos atendidos:</strong>

RF-01: A seção Home é o portal de entrada, contendo um menu fixo para suas 3 seções, sendo elas: Low Carb – o que é e benefícios, Alimentos e Saúde preventiva.

<strong>Artefatos da funcionalidade</strong>
<br>
<ul>
<li>index.html</li><br>
<li>Modelologo.png </li><br>
<li>style.css</li><br>

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


<strong>Instruções de acesso</strong><br>

1º. Abra um navegador de Internet e informe a seguinte URL: http://127.0.0.1:5501/src/home.html<br>
2º. A tela home é a primeira funcionalidade exibida pelo aplicativo.

<strong>Tela - Comida Low Carb</strong>

A tela conceitua o que seria uma alimentação baseada na dieta Low Carb, assim como descreve alguns benefícios advindos dessa prática.  

 <img id = "figma" src="../docs/img/Figura_2_Tela_Conceituando.png" width=1000px>
Figura 2 - Tela Conceituando <br>

<br>

<strong> Requisitos atendidos:</strong>

RF-02: O que é comida Low Carb? Quais os Benefícios?

<strong>Artefatos da funcionalidade</strong>
<br>
<ul>
<li>index.html</li><br>
<li>Modelologo.png </li><br>
<li>style.css</li><br>

<strong>Estrutura de Dados</strong>
<br>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="../src/css/conteudo.css">
    <title>Conceituando</title>

    <div class="header">
        <img id = "logop" src="../docs/img/Modelologo.png" width=100px>
    </div>

    <div id="titulo">
        
            <h1> CONCEITUANDO</h1>
        
    </div>

</head>

<body>

    <div id="enconstrucao">
        
            <p> EM CONSTRUÇÃO </p>
        
    </div>

</body>

</html>

<strong>Tela - Alimentos</strong>

A tela descreve alguns alimentos essenciais para uma dieta Low carb, bem como aqueles que NÃO podem compor o quadro de alimentos aptos para ingestão. 

 <img id = "figma" src="../docs/img/Figura_3_Tela_da_Secao_Alimentos_atualizada.png" width=1000px>
Figura 3 - Tela Alimentos <br>

<br>

<strong> Requisitos atendidos:</strong>

RF-03: A seção Alimentos deve conter uma funcionalidade de filtro/pesquisa para
permitir ao usuário localizar um alimento por nome.


<strong>Artefatos da funcionalidade</strong>
<br>
<ul>
<li>index.html</li><br>
<li>Modelologo.png </li><br>
<li>style.css</li><br>

<strong>Estrutura de Dados</strong>
<br>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="../src/css/conteudo.css">
    <title>alimentos</title>

    <div class="header">
        <img id = "logop" src="../docs/img/Modelologo.png" width=100px>
    </div>

    <div id="titulo">
        
            <h1>ALIMENTOS</h1>
    
    </div>

</head>

<body>

    <div id="enconstrucao">
        
            <p> EM CONSTRUÇÃO </p>
       
    </div>

</body>

</html>


<strong>Tela - Saúde Preventiva</strong>

A tela descreve a contribuição da Medicina Preventiva no combate à doenças ligadas ao consumo de alimentos nada saudáveis.

 <img id = "figma" src="../docs/img/Figura_4_Tela_da_Secao_Saude_Preventiva.png" width=1000px>
Figura 4 - Tela Saúde Preventiva <br>

<br>

<strong> Requisitos atendidos:</strong>

RF-04: Saúde Preventiva – benefícios diários e prevenção de doenças - portal deve apresentar uma seção destinada à prevenção de doenças devido ao consumo de alimentos saudáveis.


<strong>Artefatos da funcionalidade</strong>
<br>
<ul>
<li>index.html</li><br>
<li>Modelologo.png </li><br>
<li>style.css</li><br>

<strong>Estrutura de Dados</strong>
<br>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="../src/css/conteudo.css">
    <title>Saúde preventiva</title>

    <div class="header">
        <img id = "logop" src="../docs/img/Modelologo.png" width=100px>
    </div>

    <div id="titulo">
        
            <h1>SAÚDE PREVENTIVA</h1>
        
    </div>

</head>

<body>

    <div id="enconstrucao">
    
            <p> EM CONSTRUÇÃO </p>

    </div>

</body>

</html>