﻿<html>
<head>
<title>Таблица SYSLOG</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица SYSLOG</font></h1>

<p><font face="Arial">Таблицa регистрации истории событий в системе.<br>
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
    <td width="20%"><font face="Arial">fSUID</font></td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор пользователя</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fDATE</font></td>
    <td width="20%"><font face="Arial">datetime</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">время произведенного действия</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fOP</font></td>
    <td width="20%"><font face="Arial">char (1)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">код действия:<br>
    &#39;1&#39; - вход в систему<br>
    &#39;2&#39; - выход из системы<br>
    &#39;3&#39; - смена пароля</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCOMPNAME</font></td>
    <td width="20%"><font face="Arial">varchar (32)</font></td>
    <td width="20%"><font face="Arial">NULL</font></td>
    <td width="40%"><font face="Arial">имя компьютера, с которого 
	производилось действие</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCOMMENT<b> </b></font></td>
    <td width="20%"><font face="Arial">varchar (150)</font></td>
    <td width="20%"><font face="Arial">NULL</font></td>
    <td width="40%"><font face="Arial">комментарий к действию </font></td>
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
    <td width="33%"><font face="Arial">iSYSLOG1 </font></td>
    <td width="33%"><font face="Arial">CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fSUID</font></td>
  </tr>
	<tr>
    <td width="33%"><font face="Arial">iSYSLOG2 </font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fDATE</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iSYSLOG3</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fSUID,fOP,fDATE</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b>
<br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font face="Arial">См. 
также</font></a></p>
</body>
</html>