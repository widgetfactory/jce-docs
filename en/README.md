## JCE Editor Help Files

This is a repository of JCE help articles used by the JCE Editor Help system via the JCE Editor site - https://www.joomlacontenteditor.net/support/documentation

The help system identifies each article on the site using the Joomla Article Manager Key Reference system, where each article is identified by a set of keywords seperated by a dot character, where the last keyword represents a specific article, and the preceeding keywords a category and sub-category, eg: editor.about

Each Key Reference is added to the article in the Publishing tab of the Joomla Article Manager, when the article is create.

![](https://cdn.joomlacontenteditor.net/images/github/docs/editor-about.png)

This would then produce a help url of https://www.joomlacontenteditor.net/index.php?option=com_content&view=article&task=findkey&lang=en&keyref=editor.about

When using a custom help site url, an alternative approach to finding help articles is to use a SEF URL for each article, where the help system will use your custom url with the keywords appended based on a pattern of your choosing, eg:

https://www.joomlacontenteditor.net/docs/editor/about or https://www.joomlacontenteditor.net/docs/editor-about

### Repository layout

This repository is organized by category, sub-category and article, and can therefore be used as a basis for a custom help site.
