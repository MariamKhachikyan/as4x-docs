﻿<html>
<head>
<title>AsDynamicTree</title>
    <style type="text/css">
        .style1 {
            height: 30px;
        }
        .style2
        {
            height: 26px;
        }
        .style3
        {
            height: 29px;
        }
    </style>
</head>

<body>

<h1><font size="4" face="Arial">Объект динамическое дерево</font></h1>

<p><font face="Arial">Создание объекта динамического дерева(<strong><em>AsDynamicTree</em></strong>) обеспечивается через 
    функцию <strong><em>CreateDynamicTree</em></strong>. Функцию<strong> <em>CreateDynamicTree</em>
    </strong>необходимо описать в скриптовой части общедоступного модуля, чтобы она 
    была доступна из любого скрипта.</font> </p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="style1" width="29%"><font face="Arial"><strong>Свойства</strong></font></td>
    <td class="style1" width="71%"><font face="Arial"><strong>Описание<br />
        </strong></font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial"><a href="AsDynamicTree/Caption_D.html">
	Caption</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или устанавливает 
        заголовок динамического дерева.</font></td>
    </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial">
        <a
    href="AsDynamicTree/CaptionCode_D.html">CaptionCode</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или устанавливает 
        заголовок кода динамического дерева.</font></td>
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial">
        <a
    href="AsDynamicTree/code_D.html">code</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает 
	    или устанавливает код динамического дерева.</font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><a href="AsDynamicTree/ECaption_D.html"><font face="Arial">
	ECaption</font></a></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или 
	устанавливает заголовок динамического дерева на иностранном языке.</font></td>
    </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><a href="AsDynamicTree/FullTree_D.html">
	    FullTree</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или устанавливает 
        разрешимость выбора узлов любого уровня из динамического дерева. </font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><a href="AsDynamicTree/isSelected_D.html">
        <font face="Arial">
        isSelected</font></a></td>
    <td class="label" width="71%"><font face="Arial">Возвращает признак того, выбран ли 
        узел из динамического дерева.</font></td>
    </tr>
  <tr>
    <td class="style2" width="29%"><a href="AsDynamicTree/Left_D.html"><font face="Arial">
	    Left</font></a></td>
    <td class="style2" width="71%"><font face="Arial">Возвращает или устанавливает 
        удаленность левого края списка динамического дерева от левого края окна 
        приложения.</font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial">
        <a href="AsDynamicTree/MultiSelectMode_D.html">MultiSelectMode</a></font><br />
      </td>
          <td class="style2" width="71%"><font face="Arial">Возвращает или устанавливает признак множественного 
              выбора из списка динамического дерева.</font></td>
  <tr>
    <td class="label" width="29%"><font face="Arial">
	    <a href="AsDynamicTree/SelectRootsOnly_D.html">SelectRootsOnly</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или устанавливает 
        признак выбора корневых узлов из динамического дерева.</font></td>
  </tr>
    <tr>
    <td class="style3" width="29%"><font face="Arial">
        <a href="AsDynamicTree/Top_D.html">Top</a></font><br />
      </td>
          <td class="style2" width="71%"><font face="Arial">Возвращает или устанавливает 
        удаленность верхнего края списка динамического дерева от верхного края окна&nbsp; 
        приложения.</font></td>
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><a href="AsDynamicTree/TreeId_D.html">
	TreeId</a></font></td>
    <td class="label" width="71%"><font face="Arial">Устонавливает значение идентификатора дерева.</font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial">
        <a href="AsDynamicTree/xArrayDBNodes_D.html">
	    xArrayDBNodes</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает ссылку типа <a href="Functions/CreateXArrayDB.html"> XArrayDB</a> на 
        массив узлов динамического дерева.</font></td>
    </tr>
  </table>

<p>&nbsp;</p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Методы</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><a href="AsDynamicTree/AddNode_D.html">
	AddNode</td>
    <td class="label" width="71%"><font face="Arial">Добавляет в 
	    динамическое дерево новый узел.</font></td>
  </tr>
    <tr>
    <td class="label" width="29%"><a href="AsDynamicTree/AddNodeFromTree_D.html">
        <font
    face="Arial">AddNodeFromTree</font></a></td>
    <td class="label" width="71%"><font face="Arial">Добавляет в динамическое дерево узел 
        с уже существующим TreeId.</font></td>
    </tr>
    <tr>
    <td class="label" width="29%"><font face="Arial">
        <a href="AsDynamicTree/Show_D.html">
	    Show</a></font></td>
    <td class="label" width="71%">

<p><font face="Arial">Активизирует, выводя на экран, динамическое дерево.</font></p>

    </td>
    </tr>
  </table>
    <p>
        &nbsp;</p&nbsp;</p>
    <p>
        <font face="Arial"><b>Примечание<br />
        <br />
        </b>Пример описания и визирования функций<b> <strong>CreateDynamicTree </strong>
        </b>и<b><strong> ShowDynamicTree </strong>
        </b>с использованием некоторых вышеописанных свойств и методов<b>.
        <br />
        <br />
        </b>Sub ForClickDropDown(ByVal Rekv As String, ByVal Top As Single, ByVal Lft As 
        Single )<b><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </b>Dim dTree As <strong>AsDynamicTree</strong><br />
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Set dDTree = CreateDynamicTree(&quot;DTree1&quot;, Doc)
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Call ShowDynamicTree(dTree, Top, Lft)
        <br />
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If dTree.<a href="AsDynamicTree/isSelected_D.html">isSelected</a> Then
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
        Doc.ControlValue(Rekv) = dTree.Code<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End If<b><br />
        <br />
        </b>End Sub<b><br />
        </b><em>
        &#39;********************************************************************************
        <br />
        &#39; <strong>Purpose</strong> :&nbsp; Creates Dynamic Tree <br />
        &#39; I<strong>nputs</strong> :&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; key : Defines which 
        tree must be created
        <br />
        &#39;<strong>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </strong>source : Source document or Dialog<br />
        &#39;<strong> Returns </strong>: Dynamic tree
        <br />
        &#39;********************************************************************************</em><b><br />
        </b>Public Function <strong>CreateDynamicTree</strong>(ByVal <strong>key
        </strong>As String, ByVal source As Object) As <strong>AsDynamicTree<br />
        <br />
        </strong>Dim dynTree As AsDynamicTree<br />
        Dim rs As rdoResultset<br />
        Dim sSql As String<strong><br />
        <br />
        </strong>Set dynTree = New <strong>AsDynamicTree
        <br />
        </strong>
        <br />
        Select Case <strong>key<br />
        </strong>Case &quot;DTree1&quot;<strong><br />
&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp;&nbsp;&nbsp;&nbsp; dynTree.<a href="AsDynamicTree/Caption_D.html">Caption</a> = 
        &quot;DynCAption&quot;
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dynTree.<a href="AsDynamicTree/ECaption_D.html">ECaption</a> = &quot;DynECaption&quot;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dynTree.<a href="AsDynamicTree/TreeId_D.html">TreeId</a> = &quot;TreeID1&quot;
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dynTree.<a href="AsDynamicTree/AddNodeFromTree_D.html">AddNodeFromTree</a>(&quot;D1&quot;)
        <strong>
        <br />
        </strong>End Select
        <br />
        <br />
        Return dynTree<strong><br />
        <br />
        </End Function<br />
        <br />
        </strong>Public Sub ShowDynamicTree(ByVal dnTree As AsDynamicTree, _<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ByVal Top As Single, 
        _<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ByVal Lft As Single, _<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Optional ByVal IsFullTree As Boolean = False, _
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Optional ByVal LookUpValue As String = &quot;&quot;, _<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Optional ByVal MultiSelectMode As Boolean = False)
        <br />
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/Left_D.html">Left</a> = Lft
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/Top_D.html">Top</a> = Top
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/FullTree_D.html">FullTree</a> = IsFullTree
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/MultiSelectMode_D.html">MultiSelectMode</a> = MultiSelectMode
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If LookUpValue &lt;&gt; &quot;&quot; Then
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/code_D.html">Code</a> = 
        LookUpValue
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End If
        <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dnTree.<a href="AsDynamicTree/Show_D.html">Show</a>
        <br />
        <br />
        End Sub</font></p>
    <strong>
    <p>
        &nbsp;</p>
</body>
</html>