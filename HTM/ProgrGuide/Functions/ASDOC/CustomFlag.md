﻿<html>
<head>
<title>Документ\CustomFlag</title>
    <style type="text/css">
        .style1 {
            height: 40px;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Свойство CustomFlag</strong></font></p>

<p><font face="Arial"><a href="../Asdoc.html">См. также</a>&nbsp; <u>
Пример</u>&nbsp;
<a href="../Asdoc.html">Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает свойство пользовательского флага.</font></p>

<p class="label"><font face="Arial">Свойство для чтения и записи.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><b><font face="Arial">Синтаксис</font></b></p>

<p><font face="Arial"><em>object.</em><strong>CustomFlag</strong>(<em>rekvName, 
    index</em>)[=<em>newValue</em>]</font></p>

<p><font face="Arial">Синтаксис свойства <strong>CustomFlag</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, определяющее ссылку на экземпляр документа</font></td>
  </tr>
  <tr>
    <td width="29%" class="style1"><em><font face="Arial">rekvName</font></em></td>
    <td width="71%" class="style1"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита документа</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>index</em></font></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее индекс <em>CustomFlag</em>
</font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>newValue</em></font></td>
    <td width="71%"><font face="Arial">логическое выражение, 
	определяющее новое значение <em>CustomFlag</em> </font></td>
  </tr>
</TBODY>
</table>
    <p>
        &nbsp;</p>
    <p>
        <font face="Arial"><b>Примечание<br>
<br>
        CustomFlag
</b>представляет из себя восьмибитовое свойство реквизита, каждый бит которого, в зависимости от способа использования, задает 
        какое-либо свойство реквизиту. Например 
        doc.CustomFlag(&quot;RekvName&quot;, 0) = True означает, что на реквизита&nbsp; RekvName для 
        нулевого индекса CustomFlag ставится пользовательский флаг.</font></p>
</body>
</html>