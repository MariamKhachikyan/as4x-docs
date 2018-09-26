﻿<html>
<head>
<title>AsDataDesc\RegistrNode</title>
    <style type="text/css">
        .style1
        {
            height: 30px;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод RegistrNode<br>
<br>
</strong></font><font face="Arial"><a href="../AsDataDesc.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../AsDataDesc.html">Применяется 
к</a></font></p>

<p><font face="Arial">Добавляет узел в дерево вызовов пользовательских функций.</font></p>

<p><font face="Arial">Свойство для чтения. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object.</em><strong>RegistrNode [</strong><em>sNodeId, sCaption, 
    [sParentId], [sECaption],  
    [AvailableFor]</em><strong>]</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>RegistrNode</strong>
состоит из следующих частей:</font></p>

    <table border="1" cellpadding="5" cols="2" frame="below" rules="rows">
        <tr valign="top">
            <td class="label" width="29%">
                <font face="Arial"><b>Параметр</b></font></td>
            <td class="label" width="71%">
                <font face="Arial"><strong>Описание</strong></font></td>
        </tr>
        <tr>
            <td width="29%">
                <em><font face="Arial">object</font></em></td>
            <td width="71%">
                <font face="Arial">обязательное строковое выражение, являющееся ссылкой на 
                экземпляр объекта типа динамическое дерево.</font></td>
        </tr>
        <tr>
            <td width="29%">
                <em><font face="Arial">sNodeId</font></em></td>
            <td width="71%">
                <font face="Arial">троковое выражение, определяющее идентификатор узла</font></td>
        </tr>
        <tr>
            <td width="29%" class="style1">
                <font face="Arial"><em>sCaption</em></font></td>
            <td width="71%" class="style1">
                <font face="Arial">обязательное строковое выражение, определяющее наименование 
                добавляемого узла.</font></td>
        </tr>
        <tr>
            <td width="29%">
                <font face="Arial"><em>sParentId</em></font></td>
            <td width="71%">
                <font face="Arial">необязательное строковое выражение, определяющее ссылку на 
                идентификатор вышестоящего узла в меню контекстных вызовов. Если не задано, то 
                текущая запись меню добавляется на корневом уровне.</font></td>
        </tr>
        <tr>
            <td width="29%">
                <font face="Arial"><em>sECaption</em></font></td>
            <td width="71%">
                <font face="Arial">обязательное строковое выражение, определяющее наименование 
                добавляемого узла на иностранном языке.</font></td>
        </tr>
        <tr>
            <td width="29%">
                <font face="Arial"><em>AvailableFor</em></font></td>
            <td width="71%">
                <font face="Arial">необязательное численное выражение, определяющее
                    <a href="../../Constants/const_RegistrFunctionAvailability.html">константу  видимости</a> группировочного узла.</font></td>
        </tr>
        </table>
    <p>
        &nbsp;</p>
</body>
</html>