﻿<html>
<head>
<title>Описание узла дерева навигации</title>
<style type="text/css">
.style1 {
	font-size: large;
}
.style3 {
	font-weight: bold;
	border: 1px solid #C5C5C5;
}
.style9 {
	border-color: #000000;
	border-width: 0;
}
.style10 {
	font-weight: bold;
	border: 0 solid #000000;
}
.style11 {
	border: 1px solid #C5C5C5;
}
    .style12
    {
        font-family: Arial;
    }
    .style13
    {
        width: 62%;
    }
    .style14
    {
        font-family: Arial;
        width: 62%;
    }
    .style15
    {
        height: 470px;
        width: 233px;
    }
    .style16
    {
        width: 48%;
    }
    .style18
    {
        width: 48%;
        height: 30px;
    }
    .style19
    {
        width: 62%;
        height: 30px;
        font-weight: 700;
    }
    .style20
    {
        font-family: Arial;
        width: 62%;
        height: 30px;
    }
</style>
</head>

<body>
<font face="Arial"><strong>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span class="style1">&nbsp; Описание узла дерева навигации&nbsp;&nbsp; </span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<br />

Синтаксис<br />

    <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; NODE</strong>{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Caption </strong>=<em> sNodeCaption</em>;<strong>
</strong>
    &nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ECaption </strong>=<em> sNodeECaption</em>;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; 
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Ref </strong>=<em> sNodeRef;</em><strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
    Formula </strong>= s<em>NodeFormula;&nbsp;</em><strong><br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; Icon </strong>=<em> sNodeIcon</em>;&nbsp;&nbsp;<br />
    &nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;};<br />
&nbsp;</font><table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style10" style="width: 1%">&nbsp;</td>
    <td class="style3" width="29%"><font face="Arial">Параметр</font></td>
    <td class="style11" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em> sNodeCaption</em></font></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее заголовок узла</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em> sNodeECaption</em></font></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее заголовок узла на иностранном
    языке</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em> sNodeRef</em></font></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее ссылку в дереве навигации. Ссылка может быть либо на функцию в 
        навигаторе, либо на другой узел.</font></td>
  </tr>
   <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em> sNodeFormula</em></font></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее формулу активации узла NODE.</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em> sNodeIcon</em></font></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее иконку для узла NODE. </font></td>
  </tr>
  </table>

<p class="MsoNormal"><span class="style12"><strong>&nbsp;Установки </strong></span></p>
    <p class="MsoNormal">
        <font face="Arial">Префиксы<em> sNodeRef </em>могут 
        быть следующего значения:</font></p>
    <p class="MsoNormal">
        <table border="1" cellpadding="5" cols="3" frame="below" rules="rows">
            <tr valign="top">
                <td class="label" width="20%">
                    <font face="Arial"><b>Значение</b></font></td>
                <td class="label" width="60%">
                    <font face="Arial"><b>Описание</b></font></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    N1</td>
                <td width="60%">
                    <span class="style12">New document</span></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    N2</td>
                <td class="style12" width="60%">
                    <font face="Arial">Repeatable new document</font></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    B1</td>
                <td width="60%">
                    <span class="style12">View</span></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    B2</td>
                <td width="60%">
                    <span class="style12">Tree</span></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    B3</td>
                <td width="60%">
                    <span class="style12">Report</span></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    V1</td>
                <td width="60%">
                    <span class="style12">Visual report</span></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    UR</td>
                <td class="style12" width="60%">
                    <font face="Arial">User report</font></td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    OL</td>
                <td class="style12" width="60%">
                    Olap</td>
            </tr>
            <tr valign="top">
                <td width="20%">
                    RT</td>
                <td class="style12" width="60%">
                    Reference</td>
            </tr>
        </table>
    </p>
    <p class="MsoNormal">
        <span class="style12">Иконка узла</span> <font face="Arial"><em>&nbsp;Node </em>&nbsp;принимает 
        следующие значения:</font></p>
    <p class="MsoNormal">
        <table border="1" cellpadding="5" class="style15" cols="3" frame="below" 
            rules="rows">
            <tr valign="top">
                <td class="style18">
                    <font face="Arial"><b>Значение</b></font></td>
                <td class="style19">
                    <font face="Arial"><b>Описание</b></font></td>
            </tr>
            <tr valign="top">
                <td class="style18">
                    Arm</td>
                <td class="style19">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="ARM.gif (257 bytes)" height="33" 
                        src="../../IMAGES/ARM.GIF" width="33" /> &nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    Adm</td>
                <td class="style14">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="ADM.gif (257 bytes)" height="33" 
                        src="../../IMAGES/ADM.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    Columns</td>
                <td class="style13">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="COLUMNS.gif (257 bytes)" height="33" 
                        src="../../IMAGES/COLUMNS.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    Dialog</td>
                <td class="style13">
&nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="DIALOG.gif (257 bytes)" height="33" 
                        src="../../IMAGES/DIALOG.GIF" width="33" /></td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    Folder</td>
                <td class="style13">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="FOLDER.gif (257 bytes)" height="33" 
                        src="../../IMAGES/FOLDER.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    List</td>
                <td class="style13">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="LIST.gif (257 bytes)" height="33" 
                        src="../../IMAGES/LIST.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    New</td>
                <td class="style14">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="NEW.gif (257 bytes)" height="33" 
                        src="../../IMAGES/NEW.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style18">
                    Node</td>
                <td class="style20">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="NODE.gif (257 bytes)" height="33" 
                        src="../../IMAGES/NODE.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr valign="top">
                <td class="style16">
                    RefTree</td>
                <td class="style14">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="REFTREE.gif (257 bytes)" height="33" 
                        src="../../IMAGES/REFTREE.GIF" width="33" />&nbsp;</td>
            </tr>
            <tr>
                <td class="style16">
                    User</td>
                <td class="style14">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    <img alt="USER.gif (257 bytes)" height="33" 
                        src="../../IMAGES/USER.GIF" width="33" />&nbsp;<br />
                </td>
            </tr>
            <tr>
                <td class="style16">
                    ...</td>
                <td class="style14">
                    &nbsp;&nbsp;&nbsp;&nbsp;
                    </td>
            </tr>
        </table>
    </p>
    <p class="MsoNormal">&nbsp;</p>

</body>

</html>