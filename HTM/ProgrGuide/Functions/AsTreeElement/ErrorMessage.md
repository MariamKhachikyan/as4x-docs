﻿<html>
<head>
<title>Элемент дерева\ErrorMessage</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Свойство ErrorMessage<br>
<br>
</strong></font><a href="../AsFoldElement/ErrorMessage.html">См. также</a>&nbsp; <u>
Пример</u>&nbsp;
<a href="../AsTreeElement.html">Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает текст сообщения об 
ошибке при попытке добавления в дерево элемента с существующим кодом. <br>
<br>
Свойство для чтения и записи.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.ErrorMessage = [</strong><em>sValue</em><strong>]</strong></font></p>

<p><font face="Arial">Синтаксис свойства <strong>ErrorMessage</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>object</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, являющееся 
	ссылкой на экземпляр объекта элемент дерева.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>sValue</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее текст сообщения об ошибке.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Ядро системы перехватывает и не 
допускает повторения кодов в деревьях. Во избежания повторной проверки в 
скриптовых процедурах не рекомендуется делать дополнительных проверок.</font></p>
</body>
</html>