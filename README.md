## JCE Editor Help Files

This repository is a copy of JCE help articles used by the JCE Editor Help system. The original articles are hosted in the support section of the JCE site - https://www.joomlacontenteditor.net/support/documentation

### Help system keywords

The help system uses a dot-seperated keyword syntax to define the path for each help article. These keywords are defined in the plugin manifest file, and in the editor's global manifest files. The entry for the [Image Manager](https://github.com/widgetfactory/jce/blob/master/components/com_jce/editor/tiny_mce/plugins/imgmanager/imgmanager.xml#L219-L225), for example, is defined as

```xml
<help>
        <topic key="imgmanager.about" title="WF_IMGMANAGER_HELP_ABOUT" />
        <topic key="imgmanager.interface" title="WF_IMGMANAGER_HELP_INTERFACE" />
        <topic key="imgmanager.rollover" title="WF_IMGMANAGER_HELP_ROLLOVER" />
        <topic key="imgmanager.advanced" title="WF_IMGMANAGER_HELP_ADVANCED" />
        <topic key="imgmanager.insert" title="WF_IMGMANAGER_HELP_INSERT" />
        <topic file="libraries/xml/help/manager.xml" />
</help>
```
Using this syntax, the last keyword represents a specific article, and the preceeding keywords a category and sub-category, eg: *imgmanager.about*

### Repository structure

This repository is structured so that each folder represents a category or sub-category, and the contents of each article is located within an md file. You can use this structure as the basis for a custom help site.

### Key Reference

By default, the JCE Help dialog will search for an article using the Joomla Key Reference system, where the keyword is appended to the help url as the value of the *keyref* parameter, for example:

https://www.joomlacontenteditor.net/index.php?option=com_content&view=article&task=findkey&lang=en&keyref=imgmanager.about

To use this method of defining help articles, each keyword is added as a Key Reference for the article in the Publishing tab of the Joomla Article Manager, when the article is created.

![](https://cdn.joomlacontenteditor.net/images/github/docs/editor-about.png)

### Custom Help Site URL

**Please Note: The following is only supported in JCE 2.8.0 and later versions.**

When using a custom help site url, an alternative approach to finding help articles is to use a SEF URL for each article, where the help system will use your custom url with the keywords appended based on a pattern of your choosing, eg:

https://www.joomlacontenteditor.net/docs/editor/about or https://www.joomlacontenteditor.net/docs/editor-about

The pattern is specified in the configuarion using the syntax ```$1/$2/$3``` where each variable is replaced with the associated keyword. In this example the delimeter / is used, but this is optional and can be replaced with any [RFC 1738](http://www.faqs.or/rfcs/rfc1738.html) compliant character, eg: ```$1-$2-$3```


