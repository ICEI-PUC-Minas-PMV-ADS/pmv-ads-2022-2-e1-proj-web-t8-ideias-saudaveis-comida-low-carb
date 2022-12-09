# Plano de Testes de Software

Os requisitos para realização dos testes de software são:
● Site publicado na Internet
● Navegador da Internet - Chrome, Firefox ou Edge
● Conectividade de Internet para acesso às plataformas (APISs)

Os testes funcionais a serem realizados no aplicativo são descritos a seguir:

<table>

<tr><td>Caso de Teste</td>: <td>CT-01 - Visualizar na Home os os mais diversos assunntos ligados à Comida Low Carb</td>  </tr>

<tr><td>Requisitos Associados:</td> <td>RF-01: A seção Home é o portal de entrada, contendo um menu fixo para suas 3 seções, sendo elas: Low Carb – o que é e benefícios, Alimentos e Saúde preventiva.</td> </tr>

<tr><td>Objetivo do Teste:</td> <td>Verificar se a o direcionamento através de links está devidamente acionado e funcionando corretamente.</td></tr>

<tr><td>Passos: </td> <td>1) Acessar o Navegador <br> 2) Informar o endereço do Site <br> 3) Visualizar a página principal </td> <td> <br>4) Clicar nas seções direcionadas a determinado assunto (Low Carb, Alimentos e Saúde Preventiva) </td> </tr>
 
<tr><td>Critérios de Êxito: </td>
<td>● Deve haver uma requisição AJAX no painel NETWORK das ferramentas do Desenvolvedor (recurso do Navegador).<br>
● As informações de cada tela devem ser exibidas corretamente no site.<br>
● As informações devem trazer conteúdo direcionado ao assunto em tela.</td></tr>

</table>