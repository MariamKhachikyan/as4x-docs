﻿<html>
<head>
<title>GetObj</title>
    <style type="text/css">

        .style1 {
            font-family: Arial;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Функция GetObj</strong></font></p>

<p class="label"><font face="Arial">Вызывает функцию, возвращающую 
ссылку на объект, из указанного модуля.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>GetObj</strong>(<em>sModName, sFuncName, 
ParArray()</em>)</font></p>

<p><font face="Arial">Синтаксис функции <strong>GetObj</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sModName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее <a href="../../../Defs/Module.html">идентификатор модуля</a></font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>sFuncName</em></font></td>
    <td width="71%"><font face="Arial">имя функции из указанного 
	модуля, причем данная функция должна возвращать ссылку на объект. </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>ParArray()</em></font></td>
    <td width="71%"><font face="Arial">массив параметров для 
	подстановки в процедуру. Максимально допустимое количество параметров 10.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>
    <p class="label"><font face="Arial">При использовании данной функции 
накладываeтся следующeе ограничениe:</font></p>
<ul>
    <li>
        <p class="label"><font face="Arial">при задании необязательных параметров предыдущие 
            необязательные параметры должны быть заполнены.
            <br />
            <br />
            Например:<span class="style1"><br />
            <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1) 
      <em><strong>GetObj</strong></em>(&quot;modname&quot;, &quot;FName&quot;, param01, , Param3)
      <br />
      <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Function FName(ByVal param1 As Long<strong>,&nbsp;Optional</strong> ByVal param2 
            As Long, <strong>Optional</strong> 
      ByVal param3 As Long)<br class="style1" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
      ...<br class="style1" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End Function<br />
      <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2) <em><strong>GetObj</strong></em>(&quot;modname&quot;, 
            &quot;FName&quot;, param1)
            <br />
      <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Function FName(ByVal param1 As 
            Long<strong>,&nbsp;Optional</strong> ByVal param2 
            As Long, <strong>Optional</strong> 
      ByVal param3 As Long)<br class="style1" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
      ...<br class="style1" />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End Function<br />
      </span>
      <br>В первом примере задание параметра <span class="style1">param2 обязательно, поскольку после него 
            задается&nbsp;еще параметр 
      Param3, а во-втором примере - необязательно.</span><b><br>
  </li>
</ul>
<br>
</b><a href="RunSub.html">См. также</a></font></p>

</body>
</html>