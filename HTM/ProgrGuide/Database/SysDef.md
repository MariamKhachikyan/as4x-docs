﻿<html>
<head>
<title>Таблица SYSDEF</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица SYSDEF</font></h1>

<p><font face="Arial">Таблицa системных описаний. <br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%" align="left" nowrap><font face="Arial"><b>
	Поле</b></font></td>
    <td class="label" width="20%" align="left" nowrap><font face="Arial"><strong>
	Тип данных</strong></font></td>
    <td class="label" width="20%" align="left" nowrap><font face="Arial"><strong>
	Null</strong></font></td>
    <td class="label" align="left" width="40%"><font face="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fSYSTYPE</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">smallInt</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">Тип системного 
	описания </font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fNAME</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">char(20)</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">Идентификатор 
	описания</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fCAPTION</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">varchar(50)</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">наименование 
	описания</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fTYPE</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">char(1)</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">тип данных 
	(используется только<br>
    fSYSTYPE=4 и fSYSTYPE=5)</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fDESCR</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">Text</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">описание в 
	текстовом формате,<br>
    причем каждый обьект имеет<br>
    собственный язык описания, т.е.<br>
    свойственные только ему служебные<br>
    слова</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fIMAGE</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">Image</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NULL</font></td>
    <td width="40%" align="left"><font face="Arial">шаблон документа 
	Word</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fDATE</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">DateTime</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NULL</font></td>
    <td width="40%" align="left"><font face="Arial">дата изменения 
	описания</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fVERSION</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">int</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td width="40%" align="left"><font face="Arial">версия системного 
	описания. По умолчанию 0.</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fECAPTION</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">varchar(50)</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NULL</font></td>
    <td align="left" width="40%"><font face="Arial">наименование 
	описания на иностранном языке</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fROWID</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">int</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL, 
	IDENTITY</font></td>
    <td align="left" width="40%"><font face="Arial">колонка 
	идентичности</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fPRIORITY</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">int</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">колонка приоритета</font></td>
  </tr>
  <tr>
    <td width="20%" align="left" nowrap><font face="Arial">fCOMPNAME</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">varchar(32)</font></td>
    <td width="20%" align="left" nowrap><font face="Arial">NOT NULL</font></td>
    <td align="left" width="40%"><font face="Arial">имя компютера с которого было импортировано описание</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Установки</b></font></p>

<p><font face="Arial">Установки для fSYSTYPE и fNAME следующие: </font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><strong><font face="Arial">Значение 
	fSYSTYPE</font></strong></td>
    <td class="label" width="20%"><strong><font face="Arial">
	Максимально-допустимая длина fNAME</font></strong></td>
    <td class="label" width="60%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="20%"><font face="Arial">0</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/doc.html"><font face="Arial">
	описание документа</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">1</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/Data.html"><font face="Arial">
	описание источника данных</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">2</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/View.html"><font face="Arial">
	описание вида просмотра</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">3</font></td>
    <td width="20%"><font face="Arial">2</font></td>
    <td width="60%"><a href="../Defs/Accounting.html"><font face="Arial">
	описание учета</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">4</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/Tree.html"><font face="Arial">
	описание деревьев-справочников</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">5</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><font face="Arial">описание деревьев-навигаторов</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">6</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/report.html"><font face="Arial">
	описание отчетов, справок</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">7</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><a href="../Defs/Module.html"><font face="Arial">
	описание процедурных модулей</font></a></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="20%"><font face="Arial">20</font></td>
    <td width="60%"><font face="Arial">шаблон печати в формате Word</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">9</font></td>
    <td width="20%"><font face="Arial">20</font></td>
    <td width="60%"><font face="Arial"><a href="../Defs/PrintStyle.html">
	описание стиля печати</a></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">10</font></td>
    <td width="20%"><font face="Arial">16</font></td>
    <td width="60%"><font face="Arial"><a href="../Defs/Dialog.html">
	описание диалога</a></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">11</font></td>
    <td width="20%"><font face="Arial">20</font></td>
    <td width="60%"><font face="Arial">описание шаблона проводок</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">12</font></td>
    <td width="20%"><font face="Arial">20</font></td>
    <td width="60%"><font face="Arial">шаблон печати в формате Excel</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">13</font></td>
    <td width="20%"><font face="Arial">20</font></td>
    <td width="60%"><font face="Arial">описание визуального отчета</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">15</font></td>
    <td width="20%"><font face="Arial">8</font></td>
    <td width="60%"><font face="Arial">описание элемента задания</font></td>
  </tr>
</table>

<p><font face="Arial"><br>
Установки для fTYPE имеют следующие значения, в зависимости от значения 
fSYSTYPE:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="25%"><font face="Arial"><strong>Значение 
	fSYSTYPE</strong></font></td>
    <td class="label" width="25%"><font face="Arial"><strong>Значение 
	fTYPE</strong></font></td>
    <td class="label" width="50%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="25%"><font face="Arial">4</font></td>
    <td width="25%"><font face="Arial">1</font></td>
    <td width="50%"><font face="Arial">одноуровневый справочник</font></td>
  </tr>
  <tr>
    <td width="25%"><font face="Arial">4</font></td>
    <td width="25%"><font face="Arial">2</font></td>
    <td width="50%"><font face="Arial">многоуровневый справочник</font></td>
  </tr>
  <tr>
    <td width="25%"><font face="Arial">5</font></td>
    <td width="25%"><font face="Arial">0</font></td>
    <td width="50%"><font face="Arial">навигаторское дерево АРМ-а</font></td>
  </tr>
  <tr>
    <td width="25%"><font face="Arial">5</font></td>
    <td width="25%"><font face="Arial">1</font></td>
    <td width="50%"><font face="Arial">вспомогательное навигаторское 
	дерево</font></td>
  </tr>
  <tr>
    <td width="25%"><font face="Arial">5</font></td>
    <td width="25%"><font face="Arial">2</font></td>
    <td width="50%"><font face="Arial">пользовательское навигаторское 
	дерево</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%" align="left" nowrap><font face="Arial"><b>
	Имя индекса</b></font></td>
    <td class="label" width="33%" align="left" nowrap><font face="Arial"><strong>
	Тип</strong></font></td>
    <td class="label" align="left" width="33%"><font face="Arial"><strong>
	Имя столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%" align="left" nowrap><font face="Arial">iSYSDEF</font></td>
    <td width="33%" align="left" nowrap><font face="Arial">UNIQUE, 
	CLUSTERED</font></td>
    <td align="left" width="33%"><font face="Arial">fSYSTYPE, fNAME</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font face="Arial">См. 
также</font></a></p>
</body>
</html>