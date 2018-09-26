﻿<html>
<head>
<title>Таблица ACCESSLOG</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица ACCESSLOG</font></h1>
<font FACE="Arial">

<p>Таблица истории доступов. <br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font FACE="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%" height="18"><font FACE="Arial"><strong>
	Тип данных</strong></font></td>
    <td class="label" width="20%" height="18"><font FACE="Arial"><strong>
	Null</strong></font></td>
    <td class="label" width="40%" height="18"><font FACE="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fOPDATE</font></td>
    <td width="20%" height="3"><font FACE="Arial">smalldatetime</font></td>
    <td width="20%" height="3"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="3"><font face="Arial">дата изменения 
	доступа</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSTATE</font></td>
    <td width="20%" height="3"><font face="Arial">tinyint</font></td>
    <td width="20%" height="3"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="3"><font face="Arial">состояние изменения 
	доступа:<br>
	0, 125 - не обработанный<br>
	1, 126 - подтвержденный<br>
	2, 127 - отклоненный</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSUIDCHANGE</font></td>
    <td width="20%" height="3"><font FACE="Arial">smallint</font></td>
    <td width="20%" height="3"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="3"><font face="Arial">идентификатор 
	пользователя изменивший доступ</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSUIDPROCESS</font></td>
    <td width="20%" height="2"><font FACE="Arial">smallint</font></td>
    <td width="20%" height="2"><font FACE="Arial">NULL</font></td>
    <td width="40%" height="2"><font face="Arial">идентификатор 
	пользователя подтверждающий данное изменение</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fDATEPROCESS</font></td>
    <td width="20%" height="1"><font face="Arial">smalldatetime</font></td>
    <td width="20%" height="1"><font FACE="Arial">NULL</font></td>
    <td width="40%" height="1"><font face="Arial">дата подтверждения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fID</font></td>
    <td width="20%" height="3"><font face="Arial">int</font></td>
    <td width="20%" height="3"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="3"><font face="Arial">идентификатор 
	истории</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSUID</font></td>
    <td width="20%" height="3"><font FACE="Arial">smallint</font></td>
    <td width="20%" height="3"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="3"><font face="Arial">идентификатор 
	пользователя для которого меняются доступы</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fCHANGEID</font></td>
    <td width="20%" height="18"><font FACE="Arial">int</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font face="Arial">идентификатор 
	изменения, связывает с таблицой AccessLink</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font FACE="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%" height="18"><font FACE="Arial"><b>
	Имя индекса</b></font></td>
    <td class="label" width="33%" height="18"><font FACE="Arial"><strong>
	Тип </strong></font></td>
    <td class="label" width="33%" height="18"><font FACE="Arial"><strong>
	Имя столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%" height="2"><font FACE="Arial">iACCESSLOG1</font></td>
    <td width="33%" height="2"><font FACE="Arial">CLUSTERED</font></td>
    <td width="33%" height="2"><font FACE="Arial">fOPDATE</font></td>
  </tr>
  <tr>
    <td width="33%" height="1"><font FACE="Arial">iACCESSLOG2</font></td>
    <td width="33%" height="1"></td>
    <td width="33%" height="1"><font face="Arial">fID</font></td>
  </tr>
  <tr>
    <td width="33%" height="1"><font FACE="Arial">iACCESSLOG3</font></td>
    <td width="33%" height="1"></td>
    <td width="33%" height="1"><font FACE="Arial">fCHANGEID</font></td>
  </tr>
</table>

<p class="label"><font FACE="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font FACE="Arial">См. 
также</font></a></p>
</body>
</html>