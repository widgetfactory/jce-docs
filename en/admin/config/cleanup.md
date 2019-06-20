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

Set this option to No to remove the non-breaking space when the editor is toggled or the content is saved.

#### Plugin Mode

If true, & and ' are not encoded when content is saved to compensate for poorly designed 3rd party Joomla! plugins.