# PySimpleGUI Base64 Image Encoder

## Convert An Entire Folder Of Images Into Python Code


### Convert a folder full of these

![image](https://user-images.githubusercontent.com/46163555/71944932-4ec97300-3193-11ea-94c7-819d13cdb2dd.png)

### Into a file full of these

![image](https://user-images.githubusercontent.com/46163555/71944990-846e5c00-3193-11ea-83e6-6f6f5124d8f7.png)


## Running

When you run the program you'll see this window.

![image](https://user-images.githubusercontent.com/46163555/71944794-e5e1fb00-3192-11ea-9d18-c997c9c7ae5b.png)

You can either paste in the path to the folder of images or use the Browse button to locate the folder.  Once entered, click OK and the images will be converted into Base64 strings which is written to a file named `output.py`

## Why Do It?

If you're developing a GUI program, sometimes it easier to include all of your assets in the file with the source code itself.  This will enable you to distribute your application by providing a single .py file instead of several files that may get separated.  Distributing applications is still a challenge with Python.  This technique makes the jobs a little bit easier.

It's particuarly good when creating PySimpleGUI programs.  You can pass base64 images when creating `Buttons` and `Images` as well as specifying the program's icon.


## Hungry for more PySimpleGUI applications?

If you want more examples like tthis one to help in creating your GUI, then be sure and check out the many programs found at http://Demos.PySimpleGUI.org. 

![logo500](https://user-images.githubusercontent.com/46163555/71866174-62150980-30d3-11ea-8a27-451849cd88ed.png)
