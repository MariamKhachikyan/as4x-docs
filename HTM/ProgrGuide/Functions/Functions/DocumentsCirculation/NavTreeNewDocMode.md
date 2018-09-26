﻿<html>
<head>
<title>NavTreeNewDocMode</title>
</head>

<body>

<h1><font face="Arial" size="4">Функция NavTreeNewDocMode</font></h1>

<p><font face="Arial">Возвращает режим создания документа с дерева 
навигации.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>dCreateMode</em><strong> = 
Util.NavTreeNewDocMode</strong>(<em>sDocType</em>)<em><br>
</em><br>
Синтаксис функции <strong> NavTreeNewDocMode</strong> состоит из следующих 
частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>dCreateMode</em></font></td>
    <td width="71%"><font face="Arial">переменная типа целое</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sDocType</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее тип документа </font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для <em>dCreateMode </em>следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><strong>Значение</strong></font></td>
    <td class="label" width="80%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">-1</font></td>
    <td width="80%"><font face="Arial">данный тип документа не 
	создается с дерева навигации</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">0</font></td>
    <td width="80%"><font face="Arial">данный тип документа создается 
	с дерева навигации в режиме
      <a href="../../../Constants/const_doc_States.html">ASRepeatableNewMode</a></font></td>
  </tr>
  <tr vAlign="top">
    <td width="20%"><font face="Arial">1</font></td>
    <td width="80%"><font face="Arial">данный тип документа создается 
	с дерева навигации в режиме
      <a href="../../../Constants/const_doc_States.html">ASNewMode</a></font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>
<p class="label"><font face="Arial"><b>Примечание</b></font></p>
<p class="label"><font face="Arial"><a href="../../../functions.html">
См. также</a></font></p>
</body>
</html>