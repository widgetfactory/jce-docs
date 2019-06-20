## JCE Editor Help Files

This is a repository of JCE help articles used by the JCE Editor Help system via the JCE Editor site - https://www.joomlacontenteditor.net/support/documentation

The help system identifies each article on the site using the Joomla Article Manager Key Reference system, where each article is identified by a set of keywords seperated by a dot character, where the last keyword represents a specific article, and the preceeding keywords a category and sub-category, eg: editor.about

Each Key Reference is added to the article in the Publishing tab of the Joomla Article Manager, when the article is create.

![](https://cdn.joomlacontenteditor.net/images/github/docs/editor-about.png)

This would then produce a help url of https://www.joomlacontenteditor.net/index.php?option=com_content&view=article&task=findkey&lang=en&keyref=editor.about

### Custom Help Site URL

When using a custom help site url, an alternative approach to finding help articles is to use a SEF URL for each article, where the help system will use your custom url with the keywords appended based on a pattern of your choosing, eg:

https://www.joomlacontenteditor.net/docs/editor/about or https://www.joomlacontenteditor.net/docs/editor-about

The pattern is specified in the configuarion using the syntax ```$1/$2/$3``` where each variable is replaced with the associated keyword. In this example the delimeter / is used, but this is optional and can be replaced with any [RFC 1738](http://www.faqs.or/rfcs/rfc1738.html) compliant character, eg: ```$1-$2-$3```

### Repository layout

This repository is organized by category, sub-category and article, and can therefore be used as a basis for a custom help site.
