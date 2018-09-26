﻿<html>
<head>
<title>Отчет\AddRow</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод AddRow<br>
<br>
</font></strong><font face="Arial"><a href="UseFormatting.html">См. 
также</a>&nbsp;
<a href="../../Examples/E_AsRepViewer.html">Пример</a>&nbsp; <a
href="../AsRepViewer.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет в справку новую строку.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.AddRow </strong><em>
sValue, [StrOrLngISN], [RowDesc], [sExportStyleName]</em></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddRow</strong>
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
	ссылкой на экземпляр объекта типа отчет.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sValue</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее значение строки</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">StrOrLngISN</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение типа 
	Variant, определяющее внутрисистемный уникальный идентификатор ISN. Чтобы 
	использовать значение этого параметра свойство <a href="DocBased.html">
	DocBased</a> справки должно быть установлено равным True.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">RowDesc</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее описание добавляемой строки.</font></td>
  </tr>
    <tr>
    <td width="29%"><em><font face="Arial">sExportStyleName</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое выражение, определяющее 
        имя стиля экспорта строки в <strong>Excel</strong>, заданного с 
        помощью метода <a href="AddExportStyle.html">AddExportStyle</a>.</font></td>
    </tr>
</table>

<p class="label">&nbsp;</p>
<p class="label"><font face="Arial"><b>Примечание</b></font></p>
<p class="label"><font face="Arial">При установке
<a href="UseFormatting.html">UseFormatting</a> = True, <i>sValue</i> может 
содержать форматированные теги</font></p>
</body>
</html>