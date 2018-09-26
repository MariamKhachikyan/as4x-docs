﻿<html>
<head>
<title>Таблица ACCESS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица ACCESS</font></h1>
<font FACE="Arial">

<p>Таблица доступов к объектам. <br>
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
    <td width="20%"><font FACE="Arial">fISN</font></td>
    <td width="20%" height="18"><font FACE="Arial">int</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font FACE="Arial">ISN объекта, для 
	которого определяется доступ</font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fACCESSID</font></td>
    <td width="20%" height="18"><font FACE="Arial">tinyint</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font FACE="Arial">Идентификатор кода 
	доступа </font></td>
  </tr>
  <tr>
    <td width="20%"><font FACE="Arial">fVALUE</font></td>
    <td width="20%" height="18"><font FACE="Arial">binary(255)</font></td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font FACE="Arial">Дескриптор 
	доступов, где позиция, совпадающая с внутрисистемным номером пользователя, 
	определяет доступ конкретного пользователя</font></td>
  </tr>
  <tr>
    <td width="20%">fDOCTYPE </td>
    <td width="20%" height="18">char(8)</td>
    <td width="20%" height="18"><font FACE="Arial">NOT NULL</font></td>
    <td width="40%" height="18"><font face="Arial">Тип документа, 
	может быть не указан</font></td>
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
    <td width="33%" height="4"><font FACE="Arial">iACCESS1</font></td>
    <td width="33%" height="4"><font FACE="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%" height="4">fDOCTYPE, fISN, fACCESSID</td>
  </tr>
  <tr>
    <td width="33%" height="4"><font FACE="Arial">iACCESS2</font></td>
    <td width="33%" height="4"><font FACE="Arial">UNIQUE</font></td>
    <td width="33%" height="4"><font FACE="Arial">fISN, fACCESSID</font></td>
  </tr>
</table>

<p class="label"><font FACE="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font FACE="Arial">См. 
также</font></a></p>
</body>
</html>