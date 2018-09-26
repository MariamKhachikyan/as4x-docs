﻿<html>
<head>
<title>Шаблон печати\P</title>
<style type="text/css">
.auto-style1 {
	font-family: Arial;
}
.auto-style2 {
	color: #0000FF;
	text-decoration: underline;
}
</style>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод P<br>
<br>
</font></strong><font face="Arial"><a href="../AsDocPrint.html">См. 
также</a>&nbsp;
<a href="../../Examples/E_AsDocPrint.html">Пример</a>&nbsp; <a
href="../AsDocPrint.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет новую строку в печатную форму 
документа.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.P </strong><em> strPrint, </em><strong>
[</strong><em>StrOrLngISN</em><strong>]</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>P</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>object</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	ссылающееся на <a href="../Functions/InterfaceManagment/DocP.html">объект 
	печатной формы.</a></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>strPrint</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Variant, 
	определяющее строчку печатной формы</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">StrOrLngISN</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение типа 
	Variant, определяющее внутрисистемный уникальный идентификатор ISN. </font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">В строке <em>strPrint</em> после символа <big><strong>
^</strong></big> может быть указано:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Значение</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">число</font></td>
    <td width="71%"><font face="Arial">В макроподстановке будет 
	участвовать печатный параметр указанный в <a
    href="S.html">методе S</a>.</font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">идентификатор реквизита 
	документа</font></td>
    <td width="71%"><font face="Arial">В макроподстановке будет 
	участвовать значение указанного реквизита</font></td>
  </tr>
</table>

<p class="auto-style1">В <font face="Arial">строке <em>strPrint </em> можно 
применять <span class="auto-style2">теги </span>
<a href="../AsRepViewer/UseFormatting.html">форматировни</a><span class="auto-style2">я.</span></font></p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Данный метод вызывается из <a href="../../ScriptProcs/Print.html">
обработчика системного события Print</a>.</font></p>
</body>
</html>