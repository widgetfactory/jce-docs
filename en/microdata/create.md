### Creating Microdata

Microdata can only be applied to an existing text selection or element.

1. Select the text or element to apply the microdata on.
2. Click on the Insert / Edit Microdata button ![Microdata button](https://cdn.joomlacontenteditor.net/images/docs/microdata/microdata-button.jpg)
3. After a short delay while the Microdata schema is retrieved from [http://schema.rdfs.org](http://schema.rdfs.org/) the Types list will be populated with the available Microdata Types, and enabled.
4. Select the required **Type** from the list, eg: Article. This relates to the **itemtype** attribute - "_A valid URL of a vocabulary that describes the item and its properties context_<span style="font-family: sans-serif; font-size: 13px; line-height: 19.1875px;">"[<sup>1</sup>](#itemtype) - </span>and will be applied to the selections parent element (eg: paragraph)  
  ![microdata type](https://cdn.joomlacontenteditor.net/images/docs/microdata/microdata-type.jpg)
5. Select the required **Property** from the list. This relates to the **itemprop** attribute - "_Indicates that its containing tag holds the value of the specified item property. The properties name and value context are described by the items vocabulary. Properties values usually consist of string values, but can also use [URLs](http://en.wikipedia.org/wiki/URL "URL") using the `a` element and its `href` attribute, the `img` element and its `src` attribute, or other elements that link to or embed external resources_"[<sup>2</sup>](#itemprop) - and is applied to the selected element or text.  
  ![Microdata property](https://cdn.joomlacontenteditor.net/images/docs/microdata/microdata-property.jpg)
6. Add the _optional_ **itemid** if required by entering the value into the **Id** field.
7. Click the **Insert** button.

### Editing Microdata

Existing Microdata can be edited or new nested Microdata added to the selection by following the same steps as above. When editing Microdata, select **Replace / Update** to change Microdata on the selection, or **New** to add nested Microdata to the selection.

![Update microdata](https://cdn.joomlacontenteditor.net/images/docs/microdata/microdata-update.jpg)

### Removing Microdata

1. Select the element or text that has microdata applied to it.
2. Click the Insert / Edit Microdata button.
3. After a short delay while the Microdata schema is retrieved from [http://schema.rdfs.org](http://schema.rdfs.org/) the Types list will be populated with the available Microdata Types, enabled, and the active Microdata Type selected.
4. Select -- Select Type -- (the first item) from the Type list.
5. Click **Update**.

**References**

1. <a name="itemtype"></a> [http://en.wikipedia.org/wiki/Microdata\_(HTML)](http://en.wikipedia.org/wiki/Microdata_(HTML))[](http://en.wikipedia.org/wiki/Microdata_(HTML) "Wikipedia - Microdata")
2. <a name="itemprop"></a> [http://en.wikipedia.org/wiki/Microdata\_(HTML)](http://en.wikipedia.org/wiki/Microdata_(HTML))