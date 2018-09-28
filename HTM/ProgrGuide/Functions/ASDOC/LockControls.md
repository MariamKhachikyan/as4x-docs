<html>
<head>
<title>Документ\LockControls</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод LockControls</font></strong></p>

<p><font face="Arial"><a href="../Asdoc.html">См. также</a>&nbsp; <u>
Пример</u>&nbsp;
<a href="../Asdoc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Устанавливает для всех реквизитов 
документа режим только для чтения, после чего становится невозможным 
редактирование значений реквизитов.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.LockControls </strong>([<em>LockUDRs</em>])</font></p>

<p><font face="Arial">Синтаксис метода <strong>LockControls</strong>
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
	ссылкой на экземпляр документа.</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>LockUDRs</em></font></td>
    <td width="71%"><font face="Arial">логическое выражение, принимающее значения True или False. Если значение равно
        <strong>False</strong>, 
    то для всех реквизитов документа, помимо тех, которые добавлены со стороны пользователя, устанавливается режим только для чтения, 
        после чего становится невозможным редактирование значений реквизитов.
    При значении <strong>True</strong> данный режим устанавливается и для&nbsp; реквизитов, 
        добавленных со стороны пользователя. 
    По умолчанию принимает значение <strong>False</strong>.</td>
    </tr>
</table>

<p class="label">&nbsp;</p>
</body>
</html>