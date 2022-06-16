# uploadfile

This is a very simple Ajax file uploader using vanilla JS and a simple server-side PHP script.

**Caution**
There is no security of any kind implemented in this i.e.

 - No file type check
 - No file size check - **So be careful!!!**
 - No user log in or password required

As is, the file uploads to  the \upload directory.

Please note: There is no server side php allowed on github pages and thus this utility cannot be tested on this platform.
You need an Apache server with PHP to run the utility.

**upload.php** needs to be in the root directory of your site: **htdocs** if you run your own Apache server or **public** for example if you use a free hosting service such as **000.webhost.com**
