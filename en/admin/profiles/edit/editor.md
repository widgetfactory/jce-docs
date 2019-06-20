Parameters in the Editor Parameters Tab set the basic features of the editor for this profile. The settings are divided into 3 sections: **Setup**, **Options** and **Filesystem**

### **Setup**

This section sets the dimensions and styling of the editor

**Editor Width**  
Width of the Editor window in % or px. If %, add % symbol, eg: 80% Leave blank to use the original width of the textarea

**Editor Height**  
Height of the Editor window in % or px. If %, add % symbol, eg: 80% Leave blank to use the original height of the textarea.

**Editor Skin** Theme of the editor. Current options are Default and o2k7 an 'Office' style theme.

 **Editor Skin Variant** Theme variant if Editor Skin is o2k7. Options are Default (blue), Silver and Black

 **Popup Dialog Skin** Theme of plugin dialog windows. Options are _Clearlooks2_ and _Classic Blue_

 **Editor CSS** CSS file to use for editor content styling and Styles list options

- Add to list - Add the files specified in the **Custom CSS File** field to those in the **Global Configuration**
- Overwrite List- Use the files specified in the **Custom CSS File** field instead of those in the **Global Configuration**
- Inherit - Use the Global Configuration styles

**Custom CSS File** Use a custom CSS file for styling the editor content and as a source for classes in the Styles list. Enter the relative url of the replacement css file. The $template variable will be replaced by your active template name. **Editor CSS** option must be set to **Custom CSS File**. Separate multiple stylesheets with a comma, eg: templates/$template/css/sheet1.css,templates/$template/css/sheet2.css

### **Options**

This section sets various features and options for the editor.

**Relative URLs**  
Use relative urls for images, links etc. Default value of **Yes** is recommended. Set to **No** when using the editor with a newsletter component.

**Prohibited Elements**  
Comma seperated list of prohibited elements. For security purposes the following elements will always be removed unless an appropriate plugin or configuration setting is installed or enabled - **script,iframe,object,embed,param,applet**

**Extended Elements**  
Extend functionality by adding in extra elements here. Only applies if **Cleanup HTML** in the **Global Configuration** is **Yes**.

**Prohibited Attributes** Comma seperated list of prohibited attributes, eg: dynsrc,lowsrc. Can accept regular expression values, eg: on(\[a-z\]+) will remove all event attribtues (onclick, onmouseover etc.)

**Prohibited Attribute Values** Comma seperated list of prohibited attribute values in the CSS Attribute Selector format, eg: img\[title='test'\] will remove the title attribute value from all img tags with the value 'test'.

Accepts the CSS 2.1 and CSS 3 Attribute Selectors -

- Attribute starts with value : tag\[name^='value'\]  
  eg: img\[src='data:image'\] will remove all base64 encoded paths from img src attrtibutes
- Attribute equals value : tag\[name='value'\]
- Attribute is not equal to value : name!='value'
- Attribute ends with value : tag\[name$='value'\]  
  eg: img\[src$='.jpg'\] will remove all img src values that contain paths with the .jpg extension

**Format Elements**  
A comma seperated list of block elements for the Format Select List. Default is **p,div,address,pre,h1,h2,h3,h4,h5,h6,code,samp**

<div class="jce-tooltip-content">**Styles List** A comma separated list of styles for the Styles List in the editor toolbar in the format Name=style where 'style' is the name of a css class, eg: Style1=style1,Style2=style2,Style3=style3

If left blank the Styles list will be filled with classes from your template css file.

 </div>**Additional Fonts** A list of additional fonts by family, seperated by a ; eg: Arial=arial,helvetica,sans-serif;Georgia=georgia,palatino.

**Remove Fonts**  
A list of Font Familys to remove, seperated by a ; eg: Arial;Georgia;Courier New

**Font Styles**  
Comma seperated list of font style values eg: 8pt,10pt,12pt,14pt,18pt,24pt,36pt

**XHTML Attributes**  
Inline styles are used for deprecated attributes such as align, border, hspace and vspace. Default is **Yes**.

**XHTML Inline Scripts**  
Inline javascript is wrapped in CDATA tags to aid XHTML validation

**Allow Javascript**  
Allow Javascript code insertion in the source code tab

**Allow CSS**  
Allow CSS code (style elements) in the source code tab

**Allow PHP**  
Allow PHP code insertion in the source code tab. If Yes, full support may require an additional frontend content or system plugin to be installed.

**Allow IFrames**  
The iframe element is restricted by default. Set to **Yes** to allow the use of this element.

**Allow Applet**  
The applet element is restricted by default. Set to **Yes** to allow the use of this element.

### **Filesystem**

This section sets global options for plugins like the Image Manager. Each plugins individual parameters can be set to override these.

**File Directory Path**  
Relative path to file directory. Defaults to _**images**_ if left blank.  
This path can contain the variables (eg: images/$usertype/$username) :

- $id - Will be replaced with the user ID
- $username - Will be replaced with the user username
- $usertype - Will be replaced with the user usertype eg: author
- $profile - Will be replaced with the profile name
- $group - Will be replaced with the profile name
- $year - Will be replaced with current year, eg: 2010
- $month - Will be replaced with current month number, eg: 06
- $day - Will be replaced with the day number, eg: 10

**Filesystem** Select the filesystem to use. The default is the Joomla! filesystem.

**Allow Root Access**  
Allow access to the Joomla! Root directory if the **File Directory Path** value is blank. This is not recommended for security reasons. If set to **No** and if the **File Directory Path** value is **blank**, the **File Directory Path** will default to _**images/stories**_.

**Upload file size (KB)**  
Maximum allowed size in kilobytes of uploaded files. Cannot be greater than the Server Upload Size. Default value is 1024 KB.

**Upload Conflict Actions**  
Select the actions available to the user for dealing with upload conflicts (where a file of the same name as the uploaded file already exists in the target folder)

**File Browser Position** Position of the File Browser in the plugin dialog.

**Folder Tree** Show or hide the Folder Tree view in the File Browser.

**File Browser List Size**  
Number of files and folders to display in the File Browser list.

**Validate Mimetype**  
Set whether the mimetype of uploaded files should be checked and validated against the file extension.