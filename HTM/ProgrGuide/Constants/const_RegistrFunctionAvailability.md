﻿<html>
<head>
<title>Константы типов блокировок</title>
</head>

<body>

<p><font face="Arial"><big>Константы типов пользовательских функций в контекстном меню вызовов. Они так же определяют иконки функций.</big></font></p>

<p><font face="Arial">Т.к. эти константы объявлены в системном ядре, 
то нет необходимости в их дополнительном объявлении. Их можно использовать везде 
в скриптах, взамен их значений.</font></p>

<table border="1">
  <tr>
    <td width="20%"><font size="3" face="Arial"><b>Константа</b></font></td>
    <td width="20%"><font size="3" face="Arial"><b>Значение</b></font></td>
    <td width="60%"><font size="3" face="Arial"><b>Описание</b></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>RFA_Default</strong></font></td>
    <td width="20%" align="center"><font face="Arial"><strong>0</strong></font></td>
    <td width="60%"><font face="Arial">по умолчанию. Функция видима всегда и без 
	иконки.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>RFA_CurrentRow</strong></font></td>
    <td width="20%" align="center"><font face="Arial"><strong>1</strong></font></td>
    <td width="60%"><font face="Arial">функция видима когда есть хотя бы одна 
	строка. Если ни одна строка не выделена, то и иконка не показывается, в 
	противном случае показывается иконка индицирующая, что функция расчитана на 
	текущую строку.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>RFA_SelectedRows</strong></font></td>
    <td width="20%" align="center"><font face="Arial"><strong>2</strong></font></td>
    <td width="60%"><font face="Arial">функция видима когда есть хотя бы одна 
	выделенная строка. Показывается иконка индицирующая, что функция расчитана 
	на выделенные строки.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>RFA_CurrentAndSelectedRows</strong></font></td>
    <td width="20%" align="center"><font face="Arial"><strong>4</strong></font></td>
    <td width="60%"><font face="Arial">функция видима когда есть хотя бы одна 
	строка. Если ни одна строка не выделена, то и иконка не показывается, в противном случае показывается иконка  
	индицирующая, что функция расчитана на выделенные строки.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>RFA_NoRow</strong></font></td>
    <td width="20%" align="center"><font face="Arial"><strong>8</strong></font></td>
    <td width="60%"><font face="Arial">функция видима всегда и без иконки. Можно 
	использовать с <strong>RFA_CurrentRow</strong>, <strong>RFA_SelectedRows</strong>, <strong>RFA_CurrentAndSelectedRows</strong>.</font></td>
  </tr>
</table>

<blockquote>
</blockquote>

<p><font face="Arial"><br>
Эти константы могут быть также использованы в качестве параметров методов 
<a href="../Functions/FrmPttel/RegistrFunction.html">RegistrFunction</a>,  
<a href="../Functions/FrmPttel/RegistrNode.html">RegistrNode</a> текущего вида 
просмотра и <a href="../Functions/ASDOC/RegistrFunction.html">RegistrFunction</a>,  
<a href="../Functions/ASDOC/RegistrNode.html">RegistrNode</a> документа, для 
определения видимости и иконок меню. Группировочные узлы не имеют иконок, так 
что вышесказанное относится к ним только по части видимости.</font></p>
</body>
</html>