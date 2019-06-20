### Deleting Files and Folders

Multiple files or single folders can be selected and deleted.

A folder must be empty before it can be deleted. If it isn't, you must delete all files and folders in it before attempting to delete it otherwise an error message will be generated.

To delete files and folders:

1. Select the folders and/or files to delete by checking the items checkbox
2. Click the 'Delete' button <span class="uk-icon uk-icon-trash"></span>
3. An alert dialog will be displayed requesting confirmation of the action. This is to prevent accidental deletion of an item. Click the **Delete** button to confirm or **No** to cancel.  
  ![Confirm Delete](https://cdn.joomlacontenteditor.net/images/docs/main/delete-confirm.jpg)
4. The request is sent to the server and the dialog is closed.

If the file or folder cannot be deleted, one of the following error messages will be shown:

- **Invalid Directory -** The folder does not exist. It may have been deleted by another user just before your attempt.
- **Unable to Delete Folder!** - The folder's permissions may prevent it from being deleted or the server was unable to complete the request.
- **Please delete all files/folders inside the folder you wish to delete first. -** The folder is not empty. Only empty folders can be deleted.
- **File Not Found! -** The file does not exist. It may have been deleted by another user just before your attempt.
- **Unable to Delete File(s)!** - The file(s) permissions may prevent it from being deleted or the server was unable to complete the request.