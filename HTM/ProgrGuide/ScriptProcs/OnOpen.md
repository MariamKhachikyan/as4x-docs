﻿<html>
<head>
<title>Системное событие OnOpen</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие OnOpen<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <a href="../Examples/E_OnOpen.html">Пример</a>&nbsp; <a
href="../Defs/Data.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Происходит при открытии источника 
данных, обеспечивая выполнение некоторого действия. Активизируется также после 
использования методов <a href="../Functions/ASDATA/OpenCursor.html">OpenCursor</a>
и <a href="../Functions/FrmPttel/Update.html">Update</a>. Происходит до начала 
выполнения события <a href="OnEachRow.html">OnEachRow</a>. Она удобна для 
получения некоторых значений, которые используются затем в <a href="OnEachRow.html">
OnEachRow</a>. Последовательность генерации системных событий для источника 
данных приведена здесь <a
href="Events_Sequence_Data.html"><img src="../../../IMAGES/More.gif" width="12" height="12"
alt="More.gif (304 bytes)" border="0"></a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>OnOpen</strong>()<br>
<em>&nbsp;&nbsp; statements</em><br>
End Sub</font></p>
</body>
</html>