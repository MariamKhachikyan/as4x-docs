﻿<html>
<head>
<title>Таблица HIPAR</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица HIPAR</font></h1>
<font FACE="Arial">

<p>Таблица хранения истории параметров. В ней хранятся параметры, имеющие 
временную характеристику. Например курсы валют и параметры законодательства, 
имеющие дату ввода в действие.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font FACE="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font FACE="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><font FACE="Arial"><strong>Null</strong></font></td>
    <td class="label" width="40%"><font FACE="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fPARID</font></td>
    <td width="20%"><font FACE="Arial">varchar(50)</font></td>
    <td width="20%"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%"><font FACE="Arial">Идентификатор параметра</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fDATE</font></td>
    <td width="20%"><font FACE="Arial">smalldatetime</font></td>
    <td width="20%"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%"><font FACE="Arial">Дата изменения значения 
	параметра </font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fVALUE</font></td>
    <td width="20%"><font FACE="Arial">varchar (255)</font></td>
    <td width="20%"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%"><font FACE="Arial">Значение параметра (для каждого 
	типа параметра каким-то образом структурированное)</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fISN</font></td>
    <td width="20%"><font FACE="Arial">int</font></td>
    <td width="20%"><font FACE="Arial">NULL</font></td>
    <td width="40%"><font FACE="Arial">ISN документа, порождающего 
	данную строку. Если параметр не имеет документа основания, то значение 
	fISN=-1</font></td>
  </tr>
  <tr>
    <td width="20%">fCREATIONDATE</td>
    <td width="20%">datetime</td>
    <td width="20%"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%"><font FACE="Arial">дата создания данной строки</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font FACE="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%"><font FACE="Arial"><b>Имя индекса</b></font></td>
    <td class="label" width="33%"><font FACE="Arial"><strong>Тип </strong></font></td>
    <td class="label" width="33%"><font FACE="Arial"><strong>Имя 
	столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%"><font FACE="Arial">iHIPAR1</font></td>
    <td width="33%"><font FACE="Arial">CLUSTERED</font></td>
    <td width="33%"><font FACE="Arial">fPARID, fDATE, fCREATIONDATE</font></td>
  </tr>
  <tr>
    <td width="33%"><font FACE="Arial">iHIPAR2</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font FACE="Arial">fISN</font></td>
  </tr>
  <tr>
    <td width="33%">iHIPAR3</td>
    <td width="33%"><font FACE="Arial">UNIQUE</font></td>
    <td width="33%">fPARID, fDATE, fISN</td>
  </tr>
</table>

<p class="label"><font FACE="Arial"><b><br>
Примечание</b></font></p>

<p class="label"><a href="../Functions/Functions/ParameterManagment/Hipar.html"><font FACE="Arial">
См. также</font></a></p>
</body>
</html>