### Renaming a File or Folder

To rename a file or folder:

1. Select the file or folder to rename by checking the items checkbox. Only one item can be renamed at a time.
2. Click the Rename icon <span class="uk-icon uk-icon-pencil-square-o"></span>
3. The Rename dialog will open showing the existing item name.   
  ![Rename dialog](https://cdn.joomlacontenteditor.net/images/docs/main/rename-dialog.jpg)
4. Type in a new name for the item.  
  <div class="uk-alert">The name can contain any character that is allowed in a URL, including the letters A-Z, the numbers 0-9, spaces, and any UTF-8 character, but excluding the characters +\\/?#%&<>"'=\[\]{},;@^()£€$</div>
5. Click the **Rename** button. An alert dialog will be displayed requesting a confirmation of the action as renaming a file or folder can break an existing link in a content item that uses the file / folder being edited.  
  ![Rename confirm](https://cdn.joomlacontenteditor.net/images/docs/main/rename-confirm.jpg "rename_dialog_alert.gif")
6. The request is sent to the server and the dialog is closed.
7. If the file or folder cannot be renamed, one of the following error messages is displayed:

- **A file of the same name already exists!** - The new file or folder cannot have a name of a file or folder that already exists on the server. The new name must be unique.
- **Unable to rename file!** or **Unable to rename folder! -** This is a general error displayed when the the server is unable to rename the file or folder. Most commonly generated due to a permissions problem with the target item, ie: not writable.
- **Invalid folder name, please choose another folder name. -** The new name is the same as a reserved folder name.