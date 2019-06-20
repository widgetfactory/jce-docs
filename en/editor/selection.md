Before any item can be formatted or styled in an article it must be selected. This can be a simple action like clicking on the item, for example an image, or a double-click to select a whole word in a sentence. It is also possible to **select a specific element** within a group of nested elements, for example the **<strong>** element that surrounds the text within a link element ie: <a href="some\_link.htm">**<strong>**text**</strong>**</a>

### **Selecting Text**

Text can be selected either by **clicking and dragging** to select a block of text, or by **double-clicking** on a specific word to select just that word. Once the text is selected it can be styles and formatted using the buttons in the editor toolbar.

### **Selecting an element**

To select any element, such as an image or table, **click once** on the element. Any button associated with that element, like the Insert / Edit Image or Insert Table button, will become active. The element can now be edited using the dialog opened by clicking the active button or styled by other buttons in the editor toolbar.

### **Selecting a specific element**

It is sometimes necessary to select a specific element within a group of nested elements, when you want to edit the attributes of that element or style it, but a normal selection, by clicking on the element or selecting the text, would result in the wrong element (usually the last in the group) being selected.

Consider the following text : **lorem <span style="text-decoration: underline;">_ipsum_</span> dolor sit amet**

if you wanted to edit the **span element** that adds the underline style to ipsum, clicking on it would select the **<em>** element that adds the italics as this was the last element added, and so any styling would be applied to the **<em>**. You could get around this problem by careful planning, making sure that each element is styled before the next is applied, but that is often not possible. Instead, the span elemnt can be selected by clicking on the word, then on **span** in the **Path** bar at the bottom of the editor ![editor_path](https://cdn.joomlacontenteditor.net/images/docs/editor/editor_path.png) The path shows all the elements in the current selection, from the parent block element, in this case a paragraph, through to the **<em>**. Clicking on any of the elements in the path will select that element directly. When clicked the selection will be shown in the article content and the element can be styled or formatted by the buttons in the editor toolbar.