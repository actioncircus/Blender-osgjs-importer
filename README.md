# Blender-osgjs-importer
Import OSGJS files into Blender
# How to use?
1. Install Python 2.6.6 https://www.python.org/downloads/release/python-266/

2. Download Blender 2.49 and extract the zip into a folder. https://download.blender.org/release/Blender2.49/

3. Set the PythonPath Environment Variable to the install location of Python 2.6.6 (on Windows, this is C:\Python26 by default)
3. Search for "Environment Variables" in Windows, or "edit environment variables for your account" without quotes.
3. Click: New...
3. For Variable name, input: PythonPath
3. For Variable value, input: C:\Python26; C:\Python26\DLLs; C:\Python26\Lib; C:\Python26\Lib\lib-tk

4. Copy everything from the "scripts" folder into the "scripts" folder located in the ".blender" folder.

5. Drag "Blender249.blend" on top of "blender.exe". (You can also keep this file in the folder you created for Blender to save space). This will open the script in blender. When blender opens, there is a command prompt window and the Blender program. Ensure that the command prompt window says "Checking for installed Python... got it!" If it doesn't find Python, your PythonPath Windows Environment Variable is not set correctly.

6. Right-click on the Python script and click "Execute Script" or press Alt+P if you prefer. In the file chooser, navigate to the folder where the .osgjs.gz file is located and click "import".

7. Don't touch anything, just wait; it may take up to a couple minutes for anything to appear. Export the file as OBJ or STL or whatever you prefer and import it into the latest version of Blender or CAD software of your choice!

	Disclaimer: this is not my code. I found this script here: https://nulledbb.com/thread-Guide-Ripping-models-from-Sketchfab
