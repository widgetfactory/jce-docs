The Global Configuration, as the name implies, are settings that are applied to all editor instances, regardless of any Profile parameters. Some options, such as **Editor Styles**, can be overridden in a Profile

The settings are divided into 4 sections, [**Cleanup & Output**](#cleanup), [**Formatting & Display**](#formatting), [**Compression Options**](#compression) and [**Advanced**](#advanced).

<a id="cleanup"></a>Cleanup & Output
------------------------------------

#### Validate HTML

Set to Yes (recommended) to format and cleanup content based on the Doctype selected.

#### Doctype

Doctype to validate HTML with (if Validate HTML is set to Yes)

- HTML4 : Validate using the HTML4 Transitional specification
- HTML5 : Validate using the HTML5 specification
- Mixed : Validate using a combination of the HTML4 and HTML5 specification

#### Entity Encoding

Entity encoding method to be used by the editor. The default is UTF-8.

#### Keep non-breaking spaces

When Entity Encoding is set to UTF-8, convert UTF-8 spaces to non-breaking spaces (recommended)

#### Pad Empty Tags

By default, some empty tags (p, h1-6, pre, div, address, caption) are padded with a non-breaking space so they maintain there structure when rendered by the browser. Without the space, some browsers would not render the tags correctly unless additional css is used.

Set this option to **No** to remove the non-breaking space when the editor is toggled or the content is saved.

#### Plugin Mode

If true, & and ' are not encoded when content is saved to compensate for poorly designed 3rd party Joomla! plugins.

<a id="formatting"></a>Formatting & Display
-------------------------------------------

#### Container Element & Enter Key

Select Container Element and Enter Key behaviour :

- **Paragraph Container & Paragraph on Enter (Default)**  
  All Text and non-block elements will be wrapped in a Paragraph, and pressing the Enter key will create a new Paragraph. SHIFT+Enter creates a linebreak.
- **Div Container & Div on Enter**  
  All Text and non-block elements will be wrapped in a DIV, and pressing the Enter key will create a new DIV. SHIFT+Enter creates a linebreak.
- **No Container & Paragraph on Enter**  
  Text and non-block elements will not be wrapped. Pressing the Enter key will create a new Paragraph. SHIFT+Enter creates a linebreak.
- **No Container & Linebreak on Enter**  
  Text and non-block elements will not be wrapped. Pressing the Enter key will create a linebreak. SHIFT+Enter creates a paragraph.

#### Reset Editor Styles

Reset the styling of the editor content, overriding some styles of your template. Forces left aligned, black text on a white background.

#### Editor Styles

CSS file to use for editor content styling and Styles list options

- Template CSS file - Use the default css file (template.css or template\_css.css) of your Joomla! template
- Custom CSS File - Use a custom CSS file specified in the **Custom CSS File** field
- Default - Use default JCE Editor styles

#### Editor Class

A class name, or list of class names (separated by a space) to be applied to the editor content area. eg: content-area

<a id="compression"></a>Compression Options
-------------------------------------------

#### Compress Javascript

Combine and compress all editor javascript files to speed up loading.

#### Compress CSS

Combine and compress editor css files to speed up loading.

#### Compress with Gzip

Gzip compressed files to further reduce their size. Disabled by default as this may not work on all servers.

<a id="advanced"></a>Advanced
-----------------------------

#### Custom Configuration Variables

A list of custom TinyMCE configuration variables, separated by a ';' See - <http://tinymce.moxiecode.com/wiki.php/Configuration> [](http://tinymce.moxiecode.com/wiki.php/Configuration)

#### Custom Callback File

Relative url (to site root) of file containing callback functions for TinyMCE callback commands.