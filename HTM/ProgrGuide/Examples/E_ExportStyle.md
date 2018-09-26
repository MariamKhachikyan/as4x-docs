﻿<html>
<head>
<title>AsRepViewer</title>
    <style type="text/css">
        .style1
        {
            color: #009933;
        }
        .style2
        {
            color: #000000;
        }
    </style>
</head>

<body>

<p><strong><font size="3" face="Arial">Пример использования объекта 
    типа SpreadsheetExportRowStyle, методов AddPart, AddExportStyle, AddFooter, AddHeader, AddRow, свойств CaptionSpreadsheetExportStyle, HasDefinedStyle и 
    функции ExportStyle.</font></strong></p>

<p><font face="Arial">Dim oStyle As <strong>SpreadsheetExportRowStyle</strong><br />
    Dim xRep As <strong>AsRepViewer<br />
    </strong>Dim strRow As String<br />
    <br />
    Set oStyle = New <a href="../Functions/SpreadsheetExportRowStyle.html">SpreadsheetExportRowStyle</a><br />
    Set xRep = <a href="../Functions/Functions/CreateRepViewer.html">
CreateRepViewerr</a><br />
    <br />
    If Not xRep.<strong>HasDefinedStyle</strong> Then<br />
    <span class="style1">&nbsp;&nbsp; &#39; export style for Caption</span><br />
    &nbsp;&nbsp;
    oStyle.<strong>AddPart</strong> 1, &quot;C(100)&quot;, , False, False<br />
    &nbsp;&nbsp;
    xRep.<strong>AddExportStyle</strong> <strong>&quot;CaptionStyle&quot;</strong>, oStyle<br />
    <span class="style2">&nbsp;&nbsp; xRep.<strong>AddRow</strong> Space(25) &amp; &quot;Acc- account&#39;s 
    section, , , <strong>&quot;CaptionStyle&quot;<br />
    </strong></span>
    <br />
    <span class="style1">&nbsp;&nbsp; &#39; export style for footer<br />
    &nbsp;&nbsp;
    </span><span class="style2">Set oStyle = New SpreadsheetExportRowStyle<br />
    &nbsp;&nbsp;
    oStyle.<strong>AddPart</strong> 1, &quot;C(10)&quot;, , True, False, True, False<br />
    &nbsp;&nbsp;
    oStyle.<strong>AddPart</strong> 1+10, &quot;Summa&quot;, 4, True, True, True, True<br />
    &nbsp;&nbsp;
    oStyle.<strong>AddPart</strong> 1+10+23, &quot;Summa&quot;, 5, True, True, True, True<br />
    &nbsp;&nbsp;
    xRep.<strong>AddExportStyle</strong> <strong>&quot;FooterStyle&quot;</strong>, oStyle<br />
    &nbsp;&nbsp;
    xRep.<strong>AddRow</strong> &quot;Остаток на 01/01.2016____1250&quot;, , , 
    <strong>&quot;FooterStyle&quot;</strong><br />
    <br />
    &nbsp;&nbsp; If sView.ExportStyle(<strong>&quot;RowStyle&quot;</strong>) Is Nothing Then&nbsp;&nbsp; 
    </span><span class="style1">
    <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &#39; export style for row<br />
    <span class="style2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Set oStyle = New SpreadsheetExportRowStyle</span></span><span class="style2"><br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    oStyle.<strong>AddPart</strong> 1, &quot;C(&quot; &amp; LeftAlign(&quot;Дата&quot;, 9)&amp; &quot;)&quot;, , False, 
    True, True, True<br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    xRep.<strong>AddExportStyle </strong <strong>&quot;<strong>RowStyle</strong>&quot;</strong>, oStyle<br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    xRep.<strong>AddRow</strong> &quot;Нач.остаток&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Приход&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
    Расход &quot;, , , <strong>&quot;RowStyle&quot;<br />
&nbsp; </strong>&nbsp;End if<br />
    <br />
&nbsp;&nbsp; xRep.CaptionSpreadsheetExportStyle = <strong>&quot;CaptionStyle&quot;<br />
    </strong></span><br>
    End iff<br />
    <br>
xRep.<strong>Show</strong></font></p>
</body>
</html>