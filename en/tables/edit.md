### Creating and editing tables

Tables can be created using the drop-down grid on the **Insert Table** button ![Insert table button](https://cdn.joomlacontenteditor.net/images/docs/tables/table-insert-button.jpg) in the editor toolbar, or using the Insert Table dialog that is opened when clicking the **Insert Table** button.

**Creating a table using the drop-down grid**

Click on the drop-down arrow on the Insert Table button and select the number of columns and rows for the table by dragging the mouse over the grid. When the required number of columns and rows have been highlighted, click the left mouse button to insert the table.

![Insert a table using the grid](https://cdn.joomlacontenteditor.net/images/docs/tables/table-insert-grid.gif)

The new table is inserted with a default width and height value. To resize the table, click anywhere in the table, then drag the table using the handle in the bottom-right corner.

![Drag resize a table](https://cdn.joomlacontenteditor.net/images/docs/tables/table-drag-resize.gif)

**Creating a table using the Insert Table dialog.**

1. Click on the Insert Table button to open the **Insert Table** dialog.
2. Set the number of columns and rows for the table as required, and set a Width and Height value.
3. Set any other options as required.
4. Click the **Insert** button.

![Insert a table using the dialog](https://cdn.joomlacontenteditor.net/images/docs/tables/table-insert-dialog.jpg)

The Tables dialog consists of two tabbed areas - **General** and **Advanced**. A summary of the options available is listed below.

#### General Properties

**Cols**  
Set the number of **Columns** for the table

**Rows**  
Set the number of **Rows** for the table

**Cellpadding**  
Set the space between the cell wall and the cell content

**Cellspacing** Set the space between cells

**Width**  
Set the table width in pixels, eg: 200 (pixels) or percent, eg: 100%

**Height**  
Set the table height in pixels, eg: 200 (pxiels) or percent, eg: 100%

**Table caption**  
Check or uncheck to include or remove a table caption. The <caption> tag is used to descibe the table, eg:

 ```
<table style="width: 400px; height: 300px;">
	<caption>This is a table caption</caption>
	<tbody>
		<tr>
			<td>Table cell</td>
			<td>Table cell</td>
		</tr>
	</tbody>
</table>
```- - - - - -

#### Advanced Properties

**Classes**

Select css classes from your template stylesheet to apply to the table. Additional class names, seperated by a space, can be typed into the field.

**Id**

Set a unique id attribute value for the table.

**Summary**

Set a summary of the table content

**Style**

A list of inline css properties to be applied to the table, eg: <samp>border: 1px solid red;</samp>

**Language code**

Set the language code for the table eg: en

**Background image**

Select a background-image for the table. You can browse for an image using the File Browser dialog accessed by clicking the File Browser button

**Frame**

Select whcih parts of the tables outer borders should be visible

**Rules**

Select which parts of the tables inner borders should be visible

**Language direction**

Select the language direction for the table

**Border**

Set the table border styles by checking the checkbox and selecting a Width, Style and Colour.

**Background color**

Set the table background colour in hex format eg: #cccccc, or select a colur using the Colour Picker.