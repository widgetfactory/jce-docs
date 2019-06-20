The **Thumbnail Editor** is used to create thumbnails (a reduced-size version of an image) using an interactive interface for setting the dimensions (width and height) and area (portion of the image) of the thumbnail.

![Thumbnail editor](https://cdn.joomlacontenteditor.net/images/docs/imgmanager_ext/ime-thumbnail-editor.jpg)

To open the Thumbnail Editor, select an image, then click on the Create Thumbnail button.

![Thumbnail Editor button](https://cdn.joomlacontenteditor.net/images/docs/imgmanager_ext/ime-thumbnail-editor-button.jpg)

### **Properties**

The **Width** and **Height** of the thumbnail can be set in the Properties section of the dialog. Changing the existing values will be reflected in the image in the **Preview** section (to a maximum of 200px x 150px, the limit of the Preview area)

By default the width and height values are constrained, ie: changing one value will calculate and set the proportional value of the other. Click on the chain icon to toggle the constrain option.

The **Quality** value can be set by dragging the slider, or entering a new value in factors of 10, eg: 20, 30, 40 etc. This sets the level of JPEG compression used when saving the thumbnail.

### **Thumbnail Area**

The thumbnail area is shown in the box on the left of the dialog. This shows the area of the original image that will be used in the thumbnail and by default includes the whole image if the proportions of the original image match those of the default width and height, otherwise it will show sized to the ratio of the width and height.

You can resize the box by dragging any one of the corners. The **Preview** image will update with the new selection. The resized box can also be moved by dragging it around.

![ime thumbnail editor crop](https://s3-eu-west-1.amazonaws.com/jce-cdn/images/docs/imgmanager_ext/ime-thumbnail-editor-crop.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIONK4EWS4YLLB2IA%2F20181229%2Feu-west-1%2Fs3%2Faws4_request&X-Amz-Date=20181229T110655Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=28b983867df34c557f874e45fb0039ac60e243522c1c7e2463171014229ecff2)

### **Saving the thumbnail**

Once you are happy with your thumbnail dimensions and selection, click the **Save** button. The thumbnail image will be created in the thumbnails folder (as set in the Image Manager Extended parameters, or "thumbnails" by default)