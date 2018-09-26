﻿<html>
<head>
<title>Описательный диалог\ClickDropDownEvent</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Свойство ClickDropDownEvent<br>
<br>
</strong></font><font face="Arial"><a href="../AsDialogEx.html">См. 
также</a>&nbsp;
<a href="../../Examples/E_AsDialogEx.html">Пример</a>&nbsp; <a
href="../AsDialogEx.html">Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает должно ли ядро 
системы генерировать событие <a
href="../../ScriptProcs/Dialog_ClickDropDown.html">ClickDropDown</a> для данного 
элемента управления диалога.<span lang="hy">Установка данного свойства 
происходит в <a href="../../ScriptProcs/Dialog_Activate.html">Dialog_Activate</a></span></font></p>

<p><font face="Arial">Свойство для чтения и записи. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object.</em><strong>ClickDropDownEvent(</strong><em>sControlName</em><strong>) 
= </strong>[<em>bClickValue</em>]</font></p>

<p><font face="Arial">Синтаксис свойства <strong>ClickDropDownEvent</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта описательного 
	диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sControlName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор элемента управления в описательном диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>bClickValue</em></font></td>
    <td width="71%"><font face="Arial">выражение логического типа, 
	определяющее должно ли ядро системы генерировать событие <a
    href="../../ScriptProcs/Dialog_ClickDropDown.html">ClickDropDown</a> для 
	данного элемента управления.&nbsp; </font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Данное свойство имеет смысл 
использовать только для пользовательских элементов управления типа <a href="../../Types/Folder().html">
Folder()</a>,
<a href="../../Types/FULLTREE().html">FullTree()</a> и <a href="../../Types/Tree().html">
Tree()</a>.</font></p>
</body>
</html>