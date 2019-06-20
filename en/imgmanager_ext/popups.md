The Image Manager Extended can be used to effortlessly create "lightbox" popup images for your site by creating the code necessary to support [JCE MediaBox](http://www.joomlacontenteditor.net/component/zoo/item/jce-mediabox), [RokBox](http://www.rockettheme.com/extensions-joomla/rokbox "RokBox") or [WidgetKit Lightbox](http://www.yootheme.com/widgetkit/examples/lightbox "WidgetKit Lightbox") style popups, in just a few clicks!

_<span class="note">It is assumed that you either have the JCE MediaBox plugin installed and published, or some other plugin, extension or template that has Rokbox or WidgetKit Lightbox support.</span>_

There are 3 methods for creating a popup :

- **Creating a popup for an image that has an associated thumbnail -** This method assumes that the image to be used as the main popup image already has a thumbnailed version present in the thumbnail folder, either created during the upload process or using the [Thumbnail Editor](index.php?option=com_content&view=article&id=362:thumbnail-editor&catid=12:image-manager-extended&Itemid=93 "Thumbnail Editor").
- **Creating a popup for an image that does not have an asscociated thumbnail** - No thumbnail is present and one needs to be created using the [Thumbnail Editor](index.php?option=com_content&view=article&id=362:thumbnail-editor&catid=12:image-manager-extended&Itemid=93 "Thumbnail Editor").
- **Creating a popup for an image using an alternate thumbnail image** - No thumbnail is present and you wish to used a different image as the thumbnail (this can be any image at all, located in any folder).

### Creating a popup for an image that has an associated thumbnail

As stated above, this method assumes that a thumbnail already exists. You can check this by selecting the image (click to the right of its name), and checking to see if the thumbnail icon is a **Create Thumbnail** icon or a **Delete Thumbnail** icon. If it is the latter, a thumbnail exists, and should be located in the 'thumbnails' folder in the same directory as the image. Proceed by following these steps:

1. Click the **Popup** Tab.
2. Select a Popup Type, eg: **JCE MediaBox  
  ![ime tab popup select](https://cdn.joomlacontenteditor.net/images/docs/imgmanager_ext/ime_tab_popup_select.jpg)** 
  - **JCE Mediabox -**<span style="line-height: 1.3em;"> the default choice. This requires that the JCE MediaBox plugin is installed and published.</span>
  - **Window Popup -**<span style="line-height: 1.3em;"> Not recommended, but a backwards compatability option to create browser window popups.</span>
3. Select the image that is to be used as the popup image by clicking on its name in the **File Browser**. A dialog will appear asking whether you would like to use the image's associated thumbnail. Click **Yes**.  
  ![ime popup assoc](https://cdn.joomlacontenteditor.net/images/docs/imgmanager_ext/ime_popup_assoc.jpg)
4. The URL field in the Popup tab will be filled with the popup image's url, and the relevant fields in the Image tab will be filled with the thumbnail image's values.
5. To add a title and/or caption to the popup, enter text in the Title and Caption fields.![link popup title](http://www.joomlacontenteditor.net/https://cdn.joomlacontenteditor.net/images/tutorials/jcemediabox/link_popup_title.png)
6. <span style="line-height: 1.3em;">To create a gallery of images in the popup, assign each popup link to the same 'group' by giving each popup the same group value.  
  ![link popup group](http://www.joomlacontenteditor.net/https://cdn.joomlacontenteditor.net/images/tutorials/jcemediabox/link_popup_group.png)</span><span style="line-height: 1.3em;">  
  </span>

_The **Group** or **Album** field is used to associate image popups, thus creating a popup gallery, where the visitor can naviagte from one image to the next from within a single popup. To use this feature, all the images must be on the same page (or end up on the same page within the various Joomla! content items) and have the same Group or Album name._

_<span class="star">**Example:** I have created 3 popup images in my content item, and assigned them all the Group name of 'gallery'. When the visitor views any of the popups by clicking on any one of the images, navigation items are included in the popup allowing the viewer to move to the other images in the Group.</span>_

### Creating a popup for an image that does not have an asscociated thumbnail

1. Select the image to be used in the popup blicking to the right of the image's name.
2. Click the **Create Thumbnail** button to open the [Thumbnail Editor](index.php?option=com_content&view=article&id=362:thumbnail-editor&catid=12:image-manager-extended&Itemid=93 "Thumbnail Editor"). Select the desired values in the dialog that appears. The default values are usually adequate. Click Save.  
  ![ime popup thumbnail](https://cdn.joomlacontenteditor.net/images/docs/imgmanager_ext/ime_popup_thumbnail.jpg)
3. <span style="line-height: 1.3em;">Follow steps 1 to 6 above.</span>

### Creating a popup for an image using an alternate thumbnail image

The procedure for this method is quite different to the above two in that we must manually specify which is the popup image and which is the thumbnail image. It is however, relatively straight forward and only takes a few more clicks than the above methods!

1. With the **Image** tab selected, click on the image name of the _image that is to be the thumbnail**,**_ ie: the image that will be clicked to launch the popup.
2. Click the **Popup** tab.
3. Select a Popup Type, eg: **JCE MediaBox**
4. Click on the name of the image that is to be the popup image in the **File Browser**, ie: the image that will be disaplayed in the popup.
5. As above, if this image has an associated thumbnail, you will be asked whether you would like to use this thumbnail - Click **No**.

**The final steps are the same for each one of these methods.**  
  
 Assign values to the Image if necessary (Align, Margin, Border etc.)  
  
 Click **Insert** To remove an existing Popup, set teh Popup Type to **-- Not Set --**, then click the **Update** button.