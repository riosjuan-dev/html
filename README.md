<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Exercícios de Tabelas - Programação Front-End</title>
<style>
body {
font-family: Arial, sans-serif;
margin: 20px;
background-color: #f9f9f9;
}
h2 {
color: #333;
margin-top: 40px;
border-bottom: 2px solid #ccc;
padding-bottom: 5px;
}
</style>
</head>
<body>

<!-- ========================================================================= -->
<!-- EXERCÍCIO 1 -->
<!-- ========================================================================= -->
<h2>Exercício 1</h2>
<table border="1" width="250" cellspacing="0" cellpadding="6">
<tr>
<td colspan="2" align="center" bgcolor="#ffff00"><b>Vendas março 2010</b></td>
</tr>
<tr bgcolor="#99ccff">
<td><b>Carro</b></td>
<td><b>Unidades</b></td>
</tr>
<tr>
<td>Gol</td>
<td>250.000</td>
</tr>
<tr>
<td>Uno</td>
<td>123.000</td>
</tr>
<tr>
<td colspan="2" align="center" bgcolor="#ffff00"><b>Vendas fev. 2010</b></td>
</tr>
<tr bgcolor="#99ccff">
<td><b>Carro</b></td>
<td><b>Unidades</b></td>
</tr>
<tr>
<td>Gol</td>
<td>250.000</td>
</tr>
<tr>
<td>Uno</td>
<td>123.000</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 2 -->
<!-- ========================================================================= -->
<h2>Exercício 2</h2>
<table border="1" width="350" cellspacing="0" cellpadding="6">
<tr>
<td colspan="3" align="center" bgcolor="#ffff00"><b>Vendas de Carros</b></td>
</tr>
<tr bgcolor="#ccffcc">
<td colspan="2" align="center"><b>Março</b></td>
<td align="center"><b>2010</b></td>
</tr>
<tr bgcolor="#99ccff">
<td><b>Carro</b></td>
<td><b>Unidades</b></td>
<td><b>Montadora</b></td>
</tr>
<tr>
<td>Gol</td>
<td>250.000</td>
<td>VW</td>
</tr>
<tr>
<td>Celta</td>
<td>190.000</td>
<td>GM</td>
</tr>
<tr>
<td>Uno</td>
<td>123.000</td>
<td>Fiat</td>
</tr>
<tr bgcolor="#ccffcc">
<td colspan="2" align="center"><b>Fevereiro</b></td>
<td align="center"><b>2010</b></td>
</tr>
<tr bgcolor="#99ccff">
<td><b>Carro</b></td>
<td><b>Unidades</b></td>
<td><b>Montadora</b></td>
</tr>
<tr>
<td>Gol</td>
<td>230.000</td>
<td>VW</td>
</tr>
<tr>
<td>Celta</td>
<td>189.000</td>
<td>GM</td>
</tr>
<tr>
<td>Uno</td>
<td>114.000</td>
<td>Fiat</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 3 -->
<!-- ========================================================================= -->
<h2>Exercício 3</h2>
<p><b>Campeonato Brasileiro</b></p>
<table border="1" width="300" cellspacing="2" cellpadding="6">
<tr>
<td rowspan="4" align="center" bgcolor="#ffff00"><b>Serie A</b></td>
<td bgcolor="#99ccff"><b>Time</b></td>
<td bgcolor="#99ccff"><b>Pontos</b></td>
</tr>
<tr>
<td>Internacional</td>
<td>50</td>
</tr>
<tr>
<td>Juventude</td>
<td>40</td>
</tr>
<tr>
<td>Flamengo</td>
<td>30</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 4 -->
<!-- ========================================================================= -->
<h2>Exercício 4</h2>
<p><b>Campeonato Brasileiro</b></p>
<table border="1" width="300" cellspacing="2" cellpadding="6">
<tr>
<td rowspan="4" align="center" bgcolor="#ffff00"><b>Serie A</b></td>
<td bgcolor="#99ccff"><b>Time</b></td>
<td bgcolor="#99ccff"><b>Pontos</b></td>
</tr>
<tr>
<td>Internacional</td>
<td>50</td>
</tr>
<tr>
<td>Juventude</td>
<td>40</td>
</tr>
<tr>
<td>Flamengo</td>
<td>30</td>
</tr>
<tr>
<td rowspan="4" align="center" bgcolor="#ffff00"><b>Serie B</b></td>
<td bgcolor="#99ccff"><b>Time</b></td>
<td bgcolor="#99ccff"><b>Pontos</b></td>
</tr>
<tr>
<td>Grêmio</td>
<td>50</td>
</tr>
<tr>
<td>Corinthians</td>
<td>40</td>
</tr>
<tr>
<td>Flamengo</td>
<td>30</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 5 -->
<!-- ========================================================================= -->
<h2>Exercício 5</h2>
<table border="1" width="350" cellspacing="2" cellpadding="6">
<tr>
<td colspan="4" align="center" bgcolor="#99ccff"><b>Vendas Trimestrais</b></td>
</tr>
<tr>
<td rowspan="3" align="center" bgcolor="#ffff00"><b>2010</b></td>
<td align="center">144.000</td>
<td rowspan="3" align="center" bgcolor="#99ff99"><b>2009</b></td>
<td align="center">188.000</td>
</tr>
<tr>
<td align="center">139.580</td>
<td align="center">179.580</td>
</tr>
<tr>
<td align="center">254.900</td>
<td align="center">298.500</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 6 -->
<!-- ========================================================================= -->
<h2>Exercício 6</h2>
<p><b>Por onde iniciamos a tabela???</b></p>
<table border="1" width="280" cellspacing="2" cellpadding="6">
<tr>
<td colspan="3" align="center" bgcolor="#99ccff"><b>Visitas mensais</b></td>
</tr>
<tr>
<td rowspan="5" align="center" bgcolor="#ffff00"><b>2010</b></td>
<td colspan="2" align="center">144.000</td>
</tr>
<tr>
<td colspan="2" align="center">139.580</td>
</tr>
<tr>
<td colspan="2" align="center">254.900</td>
</tr>
<tr>
<td align="center"><b>Média</b></td>
<td align="center"><b>Períodos</b></td>
</tr>
<tr>
<td align="center">201.000</td>
<td align="center">3</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 7 -->
<!-- ========================================================================= -->
<h2>Exercício 7</h2>
<table border="1" width="600" cellspacing="0" cellpadding="8">
<tr bgcolor="#000000">
<td colspan="3" align="center">
<font color="#ffffff"><b>Ficha técnica</b></font>
</td>
</tr>
<tr>
<td width="250" rowspan="6" valign="top">
<p align="center">
<img src="https://unsplash.com&quot; alt="Polo GTI" style="width:100%; max-width:200px;">
</p>
<p style="font-size: 11px; text-align: justify; line-height: 1.4; margin: 0;">
O novo hatch da VW deve chegar à Europa em 2009 e sua versão esportiva vem no ano depois. O modelo deve utilizar a plataforma PQ25. A versão atual (foto) utiliza a PQ 24, que também equipa nossos Gol e Fox. A nova plataforma já é utilizada no espanhol Seat Ibiza. Também graças à PQ25 os brasileiros receberam o conjunto de suspensão dianteira do novo Gol. O motor que equipará o novo Polo GTI deve ser um 1.4 turbo TSI (com injeção direta de combustível) a gasolina e que produz 180 cv de potência. E não é só este número que impressiona: a expectativa é de que o propulsor deve entregar um consumo de cerca de 14,2 km/l.
</p>
</td>
<td width="150" align="center">Nome</td>
<td width="200" align="center">Polo GTI</td>
</tr>
<tr>
<td align="center">Valor</td>
<td align="center">99.800 reais</td>
</tr>
<tr>
<td align="center">Garantia</td>
<td align="center">1 ano sem limite de km</td>
</tr>
<tr>
<td align="center">Consumo Cidade</td>
<td align="center">9,7</td>
</tr>
<tr>
<td align="center">Consumo estrada (km/l)</td>
<td align="center">13,1</td>
</tr>
<tr>
<td align="center">Tanque de combustível/autonomia</td>
<td align="center">45 / 589,5</td>
</tr>
</table>


<!-- ========================================================================= -->
<!-- EXERCÍCIO 8 -->
<!-- ========================================================================= -->
<h2>Exercício 8</h2>

<!-- Tabela principal para criar a moldura preta e o fundo branco do certificado -->
<table border="4" width="550" cellpadding="30" cellspacing="0" bgcolor="#ffffff" style="border-style: double; border-color: black;">
<tr>
<td>
<!-- Título Principal do Exercício -->
<p align="center" style="font-size: 28px; font-family: Arial, sans-serif; font-weight: bold; margin: 0 0 10px 0;">
exercicio 8
</p>

<!-- Título Estilizado do Certificado -->
<p align="center" style="font-size: 42px; font-family: 'Times New Roman', serif; font-weight: bold; margin: 0 0 40px 0;">
Certificate
</p>

<form>
<!-- Tabela de Alinhamento para os Campos de Texto -->
<table border="0" width="100%" cellpadding="8" cellspacing="0">
<tr>
<td width="140" style="font-family: Arial, sans-serif; font-size: 16px;">Nome:</td>
<td>
<input type="text" id="nome" name="nome" style="width: 160px; height: 22px; border: 1px solid black;">
</td>
</tr>
<tr>
<td style="font-family: Arial, sans-serif; font-size: 16px;">Email:</td>
<td>
<input type="text" id="email" name="email" style="width: 160px; height: 22px; border: 1px solid black;">
</td>
</tr>
<tr>
<td style="font-family: Arial, sans-serif; font-size: 16px; padding-top: 15px; padding-bottom: 15px;">
Data<br>Nascimento:
</td>
<td valign="middle">
<input type="text" id="data-nasc" name="data-nasc" style="width: 160px; height: 22px; border: 1px solid black;">
</td>
</tr>
</table>

<!-- Tabela de Alinhamento para o Botão e o Selo no Rodapé -->
<table border="0" width="100%" style="margin-top: 20px;">
<tr>
<!-- Botão Enviar alinhado à esquerda -->
<td valign="bottom" align="left" width="50%">
<input type="submit" value="Enviar" style="padding: 4px 15px; background-color: #ffffff; border: 1px solid black; cursor: pointer; font-family: Arial, sans-serif;">
</td>
<!-- Selo / Medalha alinhado à direita -->
<td valign="bottom" align="right" width="50%">
<div style="display: inline-block; position: relative; width: 60px; height: 60px;">
<!-- Círculo do Selo -->
<div style="width: 45px; height: 45px; border: 2px solid black; border-radius: 50%; background-color: white; position: absolute; top: 0; right: 10px; z-index: 2;"></div>
<!-- Fita Esquerda do Selo -->
<div style="width: 0; height: 0; border-left: 8px solid transparent; border-right: 8px solid transparent; border-top: 25px solid black; position: absolute; bottom: 0; right: 34px; transform: rotate(-15deg); z-index: 1;"></div>
<!-- Fita Direita do Selo -->
<div style="width: 0; height: 0; border-left: 8px solid transparent; border-right: 8px solid transparent; border-top: 25px solid black; position: absolute; bottom: 0; right: 18px; transform: rotate(15deg); z-index: 1;"></div>
</div>
</td>
</tr>
</table>
</form>
</td>
</tr>
</table>
