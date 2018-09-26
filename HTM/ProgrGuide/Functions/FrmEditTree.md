﻿<html>
<head>
  <title>CurrentTree</title>
  <link rel="stylesheet" href="../../common.css" />
</head>
<body>
  <h2>Объект текущее дерево</h2>
  <p>
    Доступ к элементам текущего дерева 
обеспечивается через функцию <a href="Functions/InterfaceManagment/CurrentTree.html">CurrentTree</a>.
  </p>

  <table>
    <thead>
      <tr>
        <th class="member">Свойства</th>
        <th>Описание</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="FrmEditTree/AllowAddNode.html">AllowAddNode</a></td>
        <td>Возвращает разрешение на добавление узла в текущем дереве.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/AllowDelete.html">AllowDelete</a></td>
        <td>Возвращает разрешение на удаление документа из текущего дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/AllowEdit.html">AllowEdit</a></td>
        <td>Возвращает разрешение на корректировку документа из текущего дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/AllowExport.html">AllowExport</a></td>
        <td>Возвращает разрешение на экспортирование документа из текущего дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/AllowHistory.html">AllowHistory</a></td>
        <td>Возвращает разрешение на просмотр истории документа в текущем дереве.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/AllowView.html">AllowView</a></td>
        <td>Возвращает или устанавливает разрешение на визирование документа из текущего дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/Caption.html">Caption</a></td>
        <td>Возвращает значение заголовка текущего дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/CurrentNode.html">CurrentNode</a></td>
        <td>Возвращает текущий элемент дерева в виде коллекции значений.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/Node.html">Node</a></td>
        <td>Возвращает указанный элемент дерева в виде коллекции.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/NodesCount.html">NodesCount</a></td>
        <td>Возвращает количество узлов в текущем дереве.</td>
      </tr>
    </tbody>
  </table>

  <p>&nbsp;</p>

  <table>
    <thead>
      <tr>
        <th class="member">Методы</th>
        <th>Описание</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="FrmEditTree/DeleteItem.html">DeleteItem</a></td>
        <td>Удаляет текущий лепесток из дерева.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/RefreshItem.html">RefreshItem</a></td>
        <td>Обновляет ветви дерева из базы, начиная с выбранного элемента.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/RegistrFunction.html">RegistrFunction</a></td>
        <td>Добавляет в контекстное меню вызов пользовательской функции.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/RegistrNode.html">RegistrNode</a></td>
        <td>Добавляет узел в дерево вызовов пользовательских функций.</td>
      </tr>
      <tr>
        <td><a href="FrmEditTree/SelectItem.html">SelectItem</a></td>
        <td>Определяет текущий элемент формы прокрутки дерева-спаравочника.</td>
      </tr>
    </tbody>
  </table>
</body>
</html>