﻿<html>
<head>
<title>Таблица NTFRECEIVERS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица NTFRECEIVERS</font></h1>

<p><font face="Arial">Таблицa хранения получателей оповещений.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Null</strong></font></td>
    <td class="label" width="40%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fRECEIVER</font></td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор получателя</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fNID</font></td>
    <td width="20%"><font face="Arial">uniqueidentifier</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSTATE</font></td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">состояние оповещения. При 2 - 
	получатель прочитал сообщение, при 1 - получатель еще не прочитал сообшение</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font face="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%"><font face="Arial"><b>Имя индекса</b></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Тип </strong></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Имя 
	столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iNTFRECEIVERS1</font></td>
    <td width="33%"><font face="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fRECEIVER, fNID</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iNTFRECEIVERS2</font></td>
    <td width="33%">NOT CLUSTERED</td>
    <td width="33%"><font face="Arial">fNID, fRECEIVER</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><font face="Arial"><a href="database_scheme.html">См. 
также</a></font></p>
</body>
</html>