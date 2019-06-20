Plugin Parameters are organized by plugin. Each plugins parameters can be accessed by clicking on the plugin name. The parameters are further divied into up to 4 sections, **Standard Parameters**, **Default Values**, **Permissions** and **Advanced**. Not all plugins display all four sections.

### **Standard Parameters**

These consist of standard operating parameters for the plugin. These vary from plugin to plugin but in the case of the **File Browser** and **Image Manager** include options for **File Directory Path** and **Upload File Size**, which if set will override any values set for the same parameter in the **Editor Parameters Plugin Options**.

**Permitted File Extensions**   
Sets the list of file types the the plugin can upload and display and is edited by clicking on the pencil icon adjacent to the parameter text field. For more infomration about editing File Extensions see the [**Parameter Widgets**](index.php?option=com_content&view=article&id=336:parameter-widgets&catid=100&Itemid=93 "Parameter Widgets") article.

**File Directory Path**  
Relative path to file directory. Defaults to the **Editor Parameters File Directory Path** value if left blank.  
This path can contain the variables (eg: https://cdn.joomlacontenteditor.net/images/$usertype/$username) :

- $id - Will be replaced with the user ID
- $username - Will be replaced with the user username
- $usertype - Will be replaced with the user usertype eg: author
- $profile - Will be replaced with the profile name
- $group - Will be replaced with the profile name
- $year - Will be replaced with current year, eg: 2010
- $month - Will be replaced with current month number, eg: 06
- $day - Will be replaced with the day number, eg: 10

**Upload file size (KB)**  
Maximum allowed size in kilobytes of uploaded files. Cannot be greater than the Server Upload Size. Default value is 1024 KB.

### **Default Values**

These are parameters that set default values for fields in the plugin such as Alignment, Margins, Border properties, Link Target etc.

### **Permissions**

These parameters set which features of the plugin are available for the profile eg: Allow Uploading, Allowing File Deleting etc.

### **Advanced**

Not present in all plugins but includes advanced configuration options for the the plugins.

**A more detailed description for each plugin parameter may be available in the plugins own documentation.**