<html>
<head>
<title>SendDBMail</title>
    <style type="text/css">
        .style1
        {
            height: 66px;
        }
    </style>
</head>

<body>

<p><strong><font face="Arial" size="4">Метод SendDBMail</font></strong></p>
    <p><font face="Arial">Отправляет сообщение по электронной почте указанным получателям.</font></p>
    <p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>SendDBMail(</strong>[<em>profileName</em>], 
[<em>recipients</em>]<em>, </em>[<em>copyRecipients</em>]<em>, </em>[<em>blindCopyRecipients</em>]<em>, </em>[<em>subject</em>]<em>, 
   </em>[<em>body</em>]<em>, </em>[<em>bodyFormat</em>]<em>, </em>[<em>importance</em>]<em>, </em>[<em>sensitivity</em>]<em>, </em>[<em>fileAttachments</em>]<em><strong>)</strong></em></font></p>

    <em><em>

<p><font face="Arial">Синтаксис метода <strong>SendDBMail</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><em>profileName</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее имя профиля, с которого надлежит отослать 
        сообщение. </font></td>
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><em>recipients</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее список адресов элетронной почты, по которым будут 
        рассылаться сообщения. </font></td>с
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><em>copyRecipients</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее список адресов электронной почты, по 
        которым будут рассылаться копии сообщения. </font> </td>
  </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>blindCopyRecipients</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее список адресов электронной почты, по 
        которым будут рассылаться скрытые копии сообщения. </font> </td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>subject</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее тему сообщения электронной почты</sentencetext></span>.</font> </td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>body</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее текст сообщения электронной почты</sentencetext></span>.</font> </td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>bodyFormat</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее формат текста сообщения</sentencetext></span>.</font></td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>importance</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее важность сообщения. Данное 
        выражение принимает один из следующих значений: Low, Normal, High. По 
        умолчанию принимает значение = Normal.</font> </td>
    </tr>
    <tr>
    <td class="style1" width="29%"><font face="Arial"><em>sensitivity</em></font></td>
    <td class="style1" width="71%"><font face="Arial">необязательное 
	строковое выражение, определяющее пометку сообщения. Данное 
        выражение принимает один из следующих значений: Normal, Personal, Private, Confidential. По умолчанию 
        принимает значение Normal.</font> </td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><em>fileAttachments</em></font></td>
    <td class="label" width="71%"><font face="Arial">необязательное строковое выражение, 
        определяющее список имен файлов, которые надлежат прикрепить к сообщению.</font></td>
    </tr>
</table>

<p class="label">&nbsp;</p>
    </em></em>
<p class="label">&nbsp;<font face="Arial"><b>Примечание</b></font></p>
    <p class="label"><font face="Arial">Адреса получателей в списке перечисляются через точку запятую.</font></p>
<p class="label">
        <font face="Arial"><a href="../../functions.html">См. также</a></font></p>
    <em>
<p class="label">&nbsp;<font face="Arial"><br>
</font></p>
</body>
</html>