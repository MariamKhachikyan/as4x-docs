﻿<html>
<head>
<title>Диалог\ControlValue</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Свойство ControlValue<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asustpar.html">Применяется к</a></font></p>

<p>У<font face="Arial">станавливает значение для реквизита пользовательского диалога. Другими словами задает значение свойству <a href="Control.html">
	Control</a>. <strong>ControlValue</strong>&nbsp; предназначено для параметра 
    <strong><em>OldValue</em></strong> события <a href="../../ScriptProcs/UstPar_ValueChanged.html">ValueChanged</a>. При отсутствии 
    данного свойства, после обработки события 
    <a href="../../ScriptProcs/UstPar_ClickDropDown.html">ClickDropDown</a> значение <strong>
    <em>OldValue</em></strong> портится, и при изменении значения 
    реквизита старое значение не сохраняется.

<br>
<br>
Свойство для чтения. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object.</em><strong>ControlValue(</strong><em>RekvName</em><strong>) = </strong><em>vValue</em></font></p>

<p><font face="Arial">Синтаксис свойства <strong>ControlValue</strong>
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
	определяющее переменную, ссылающуюся на экземпляр объекта пользовательского 
	диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>RekvName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение,&nbsp; 
	определяющее идентификатор реквизита пользовательского диалога.</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>vValue</em></font></td>
    <td width="71%"><font face="Arial">выражение типа вариант, 
	определяющее значение реквизитa пользовательского диалога</font></td>
    </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

</body>
</html>