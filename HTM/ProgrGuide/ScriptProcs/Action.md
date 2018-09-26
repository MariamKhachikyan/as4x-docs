﻿<html>
<head>
<title>Системное событие Action</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие Action<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <a href="../Examples/E_Action.html">Пример</a>&nbsp; <a
href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Происходит при интерактивном 
сохранении документа. Генерация данного события возможна также программно 
посредством&nbsp;вызова методов <a
href="../Functions/ASDOC/Store.html">Store</a> или<a
href="../Functions/ASDOC/CheckAndStore.html"> CheckAndStore</a>. Оно генерируется 
при включенном механизме транзакции. Последовательность генерации системных 
событий приведена здесь <a
href="Events_Sequence.html"><img src="../../../IMAGES/More.gif" width="12" height="12"
alt="More.gif (304 bytes)" border="0"></a>. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>Action</strong>()<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание<br>
<br>
</b>При обработке данного события желательно производить проводки, вызывая 
функцию <a href="../Functions/Functions/AccManagement/CreateFact.html">CreateFact</a> 
и метод <a
href="../Functions/ASDOC/StoreFact.html">StoreFact</a>.</font></p>

<p class="label">&nbsp;</p>
</body>
</html>