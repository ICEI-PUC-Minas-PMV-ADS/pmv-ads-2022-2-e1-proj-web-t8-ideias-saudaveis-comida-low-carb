# Plano de Testes de Software

Os requisitos para realização dos testes de software são:
● Site publicado na Internet
● Navegador da Internet - Chrome, Firefox ou Edge
● Conectividade de Internet para acesso às plataformas (APISs)

Os testes funcionais a serem realizados no aplicativo são descritos a seguir.

<table>

<tr><td>Caso de Teste</td>: <td>CT-01 - Visualizar notícias principais</td>  </tr>

<tr><td>Requisitos Associados:</td> <td>RF-01 - O site deve apresentar na página principal notícias dinâmicas obtidas por meio de canais de notícias da Internet (API) RF-02 - O site deve apresentar, para cada notícia, uma imagem correspondente ao assunto apresentado (thumbnail).</td> </tr>

<tr><td>Objetivo do Teste:</td> <td>Verificar se a carga de notícias está acontecendo corretamente.</td></tr>

<tr><td>Passos: </td> <td>1) Acessar o Navegador <br> 2) Informar o endereço do Site <br> 3) Visualizar a página principal </td></tr>
 
<tr><td>Critérios de Êxito: </td>
<td>● Deve haver uma requisição AJAX no painel NETWORK das ferramentas do Desenvolvedor (recurso do Navegador).
● As notícias devem ser exibidas corretamente no site, sendo necessárias pelo menos 3 notícias sendo apresentadas
● As notícias devem trazer imagens visíveis associadas ao assunto da notícia </td></tr>

</table>