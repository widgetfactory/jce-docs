The **Indent** and **Outdent** buttons are used to add and remove an amount of space at the beginning of a line of text. By default, this space is set as twice the font-size of the text, ie: 2em in css units.

For example, give a line of text:

Lorem ipsum dolor sit amet

a single indent added to the line will result in

Lorem ipsum dolor sit amet

the HTML code of which would look like

 `<p style="padding-left: 2em;">Lorem ipsum dolor sit amet</p>`Clicking the indent button again will add another 2em to the padding-left style, resulting in

Lorem ipsum dolor sit amet

that is

 `<p style="padding-left: 4em;">Lorem ipsum dolor sit amet</p>`Clicking the **Outdent** button will remove 2em from the indent, until the padding-left value is 0, ie: the indent is removed.