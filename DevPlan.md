First version, the file upload and download feature will be added. In second, the file sharing feature will be added.

Steps:
1- Create the structure.
2- Install dependencies
3- Session authentication
4- Form to upload files
5- Folder feature 
6- File view and download
7- Upload files
8- Validate files
9- Share files

Step 1: Structure
    The home page should provide a login form, register form and a view shared link form

    Login form checks the user and redirects to the user's Current Storage Page

    Current storage page shows the list of folders and files user has already stored and two buttons to add a new file and a new folder, and a logout button. 
    Clicking on a file shows a details page that allows to share, download, rename and delete it. Clicking on a folder opens a popup that allows share, open, download, rename and delete it.

    Add new file brings a form to upload the file in the required path.

    Add new folder creates a new folder in the current folder.

    Register form creates a new user. And redirects to the current storage which will be empty.

    View shared link form checks the link and redirects to the file or folder that has been shared.(May have to use some kind of temporary session authentication logic)

    Create a delete confirmation form and an error form.
