The Template Manager is able to create new templates from existing content, that is, the contents of the article you are editing/creating when the Template Manager is open.   
  
 A template can be created from a selection or from the whole article. When just a selection is required, you must select the desired content before opening the Template Manager. This is not necessary if you are using the whole article.  
 **Creating a Template**

Once the Template Manager plugin dialog is open, click the **New Template** icon. The **Create Template** dialog will open.

![Create template](https://cdn.joomlacontenteditor.net/images/docs/templatemanager/create-template.jpg "Create Template")

- Name - The name of the template
- Type - The type of 'template' to create, either a Template or a Snippet

A **Template** wraps your content in a div with a unique id, which allows it to be identified.  
 Templates can be replaced by other Templates or Snippets using the Template Manager.

Templates can have predefined variables in its content replaced by values defined in the Template Manager configuration - see [Template Manager Configuration](index.php?option=com_content&view=article&id=93:template-manager-configuration&catid=31:template-manager "Template Manager Configuration").

Unlike Snippets, which can only be inserted into the article content at the current cursor position, **_Templates can affect selected content_.** The selected article content will be altered by whatever html is contained in the Template that has a class included in the Content Classes' list in the [Template Manager Configuration](index.php?option=com_content&view=article&id=93:template-manager-configuration&catid=31:template-manager "Template Manager Configuration"). For example, selected content will be given a yellow background by the following html in the Template:

 ```
<pre class="uk-width-1-1">```
<p class="selcontent" style="background-color: yellow;">Selected Content</p>

```
```Templates can also trigger **Creation Date** and **Modified Date** parameters defined in their content. For example, if a Template contains a span tag with a class of 'cdate', 'creationdate', or any one of the classes specified in the [Template Manager Configuration](index.php?option=com_content&view=article&id=93:template-manager-configuration&catid=31:template-manager "Template Manager Configuration"), this span tag will have the current time and date inserted into it when the Template is inserted into the article content, eg:

 `<span class="cdate"></span> `will become

 `<pre class="uk-width-1-1">09/17/2007 09:05:54`The time and date format is editable in the [Template Manager Configuration](index.php?option=com_content&view=article&id=93:template-manager-configuration&catid=31:template-manager "Template Manager Configuration")[](index.php?option=com_content&view=article&id=93:configuration&catid=31:template-manager&Itemid=240 "Template Manager Configuration")

The creation date is only set once, when the Template is first inserted, but the Modified Date will change whenever the article is modified.

#### Example of Template html

 ```
<pre class="uk-width-1-1">```
<div class="mceTmpl">
<p class="selcontent" style="background-color: yellow;">Selected Content</p>
<p style="padding: 3px; color: #666; border: 1px solid #CCC;"><br /><strong>Editors Comment</strong> (<span class="cdate"> </span>)<br /><br />[Insert your comment here]</p>
</div>  

```
```The Template above applied to this text:

Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.

becomes:

 ```
<pre class="uk-width-1-1">```
<p class="selcontent mceTmplElm mceSelHTMLDone" style="background-color: yellow;">Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>
<p class="mceTmplElm" style="border: 1px solid #cccccc; padding: 3px; color: #666666;"><strong>Editors Comment</strong> (<span class="cdate mceTmplElm">09/17/2007 : 11:28:39 </span>)<br class="mceTmplElm" /> [Insert your comment here]</p>  

```
```A **Snippet** is a chunk of html code. It is not editable / replaceable as Templates are, but can have predefined variables in its content replaced by values defined in the Template Manager configuration - see [Template Manager Configuration](index.php?option=com_content&view=article&id=93:template-manager-configuration&catid=31:template-manager "Template Manager Configuration").

Snippets will replace selected content.

Example of Snippet html:

 `This is just some <strong>code</strong>`