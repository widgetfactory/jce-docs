#### Container Element & Enter Key

Select Container Element and Enter Key behaviour :

- Paragraph Container & Paragraph on Enter (Default)  
  All Text and non-block elements will be wrapped in a Paragraph, and pressing the Enter key will create a new Paragraph. SHIFT+Enter creates a linebreak.
- Div Container & Div on Enter  
  All Text and non-block elements will be wrapped in a DIV, and pressing the Enter key will create a new DIV. SHIFT+Enter creates a linebreak.
- No Container & Paragraph on Enter  
  Text and non-block elements will not be wrapped. Pressing the Enter key will create a new Paragraph. SHIFT+Enter creates a linebreak.
- No Container & Linebreak on Enter  
  Text and non-block elements will not be wrapped. Pressing the Enter key will create a linebreak. SHIFT+Enter creates a paragraph.

#### Reset Editor Styles

Reset the styling of the editor content, overriding some styles of your template. Forces left aligned, black text on a white background.

#### Editor Styles

CSS file to use for editor content styling and Styles list options

- Template CSS file - Use the default css file (template.css or template\_css.css) of your Joomla! template
- Custom CSS File - Use a custom CSS file specified in the Custom CSS File field
- Default - Use default JCE Editor styles

#### Editor Class

A class name, or list of class names (separated by a space) to be applied to the editor content area. eg: content-area