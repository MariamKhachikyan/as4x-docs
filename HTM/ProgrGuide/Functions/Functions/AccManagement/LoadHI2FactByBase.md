﻿<html>
<head>
<title>LoadHI2FactByObject</title>
    <style type="text/css">
        .style1
        {
            font-family: Arial;
        }
    </style>
</head>

<body>

<h1><font size="4" face="Arial">Функция LoadHI2FactByBase<br>
</font><a href="../../Asfact.html"><font size="3" face="Arial"><strong>
свойства&nbsp;&nbsp; методы</strong></font></a></h1>

<p><font face="Arial">Возвращает коллекцию проводок для указанного 
    докумнета-основания из HI2.<br>
<br>
При отсутствии проводок с заданными параметрами возвращается Nothing. Каждый 
элемент возвращаемой коллекции является <a href="../../Asfact.html">ссылкой на 
объект типа проводки.</a></font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>set</strong> <em>sFacts</em><strong> = 
    LoadHI2FactByBase(</strong><em>BaseISN</em><strong>, </strong><em>Accounting, </em>[<em>Op</em>]<em>, </em>[<em>GLAccISN</em>]<strong>)</strong></font></p>

<p><font face="Arial">Синтаксис функции <strong>LoadHI2FactByBase</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>BaseISN</em></font></td>
    <td width="71%"><font face="Arial">обязательное численное выражение типа Long, 
	определяющее ISN
        <a href="mk:@MSITStore:D:/MainWorkSpace/Help/Progr_guide/PROGR_GUIDE.chm::/progr_guide/htm/ProgrGuide/Functions/ASFACT/Base.html">
        документа основания</a></font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>Accounting</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое выражение, 
	определяющее <a href="../../ASFACT/TypeAcc.html">код учета</a></font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Op</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее список
      <a href="../../ASFACT/Op.html">кодов операций</a>. Если список начинается со&nbsp; 
	знаком &quot;+&quot;, то учитываются все коды операции, которые перечислены после 
	него. При знаке &quot;-&quot; игнорируются те операции, коды которых перечислены в 
	списке. Коды операции перечисляются друг за другом через пробел. Список 
	также может содержать единственный элемент без знака.</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>GLAccISN</em></font></td>
    <td width="71%"><font face="Arial">численное выражение типа Long, 
	определяющее ISN аккумулирующего объекта. По умолчанию принимает значение -1.</font></td>
    </tr>
</table>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="LoadFactByObject.html"><font face="Arial">См. 
также</font></a></p>

<p class="label">&nbsp;</p>

<p><font face="Arial"><strong><font size="3">Пример функции <font size="4" face="Arial">
    LoadHI2FactByBase</font></font><br>
<br>
</strong>Ниже приведен пример удаления проводок из HI2.</font></p>

<p><span class="style1">Dim xCol As Collection </span>
    <br class="style1" />
    <span class="style1">Dim xFact As AsFact </span>
    <br class="style1" />
    <span class="style1">Dim lngTrans As Long</span></p>
    <p><font face="Arial">Set <span class="style1"><strong>xCol</strong> </span>=<strong>LoadHI2FactByBase</strong>(Doc.ISN)<br>
        If Not <strong>xCol</strong> Is Nothing Then<br>
&nbsp; For Each <strong>xFact</strong> In <strong>xCol</strong><br>
&nbsp;&nbsp;&nbsp; lngTrans = <strong>xFact</strong>.Trans
        <br />
&nbsp;&nbsp;&nbsp; <strong>DeleteHI2Trans</strong> Doc.ISN, lngTrans<br>
&nbsp;
Next <strong>xFact<br />
        </strong>End If</font></p>

<p>&nbsp;</p>
</body>
</html>