﻿<html>
<head>
<title>Документ\GetDialogFromRekvs</title>
    <style type="text/css">

        .style2
        {
            font-style: italic;
        }
        .style3
        {
            font-style: italic;
        }
    </style>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод GetDialogFromRekvs<br>
<br>
</font></strong><font face="Arial"><a href="../Asdoc.html">См. также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asdoc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Добавляет диалог с заданными реквизитами документа.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b class="style2">Синтаксис</b></font></p>

<p><font face="Arial" class="style3"><em>object</em>.GetDialogFromRekvs(dlg, rekvs,  
    hiddenRekvs, startFromNewPage, viewMode)</font></p>

<p><font face="Arial">Синтаксис метода  <strong>GetDialogFromRekvs</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>object</em></font></td>
    <td width="71%"><font face="Arial">обязательное строковое выражение, являющееся 
	ссылкой на экземпляр документа</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial" class="style3">dlg</font></td>
    <td width="71%"><font face="Arial">обязательное строковое выражение, 
	    являющееся ссылкой на экземпляр пользовательского диалога</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial" class="style3">rekvs</font></td>
    <td width="71%"><font face="Arial">обязательное строковое выражение, определяющее имена 
        реквизитов документа, которые будут добавлены в качестве реквизитов 
        диалога. Перечисляемые реквизиты разделяются друг от друга пробелами.</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>hiddenRekvs</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое выражение, определяющее список тех реквизитов страницы, которые будут 
        добавлены в качестве скрытых невидимых реквизитов. Перечисляемые реквизиты разделяются 
        друг от друга пробелами.</font></td>
    </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>startFromNewPage</em></font></td>
    <td width="71%"><font face="Arial">необязательное логическое выражение, определяющее 
        признак того, что при значении True реквизиты будут добавляться с новой страницы 
        диалога, в противном случае - нет. По умолчанию принимает значение True.
        </font></td>
    </tr>
    <tr>
    <td width="29%"><font face="Arial" class="style3">viewMode</font></td>
    <td width="71%"><font face="Arial">необязательное логическое выражение, 
        определяющее режим редактирования реквизитов. При значении True все добавленные 
        реквизиты будут доступны только для чтения. По умолчанию принимает значение 
        False.</font></td>
    </tr>
</table>
    <p>
        <br />
    </p>
    </body>
</html>