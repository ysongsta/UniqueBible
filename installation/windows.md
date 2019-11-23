# Installation on Windows - An Example

There are different ways to install python library and dependencies.  Below is an example using Anaconda python distribution.

# 1. Download a Python distribution

Go to https://www.anaconda.com/distribution/ and download a windows version of python distribution version 3.x

<img src="screenshots/download_anaconda.png">

# 2. Run Anaconda installer

To avoid writting permission, it is easier to select option "just for me"

<img src="screenshots/install_just_for_me.png">

To make running the app easier, it is suggested to select "add path ..." option, as indicated below.

<img src="screenshots/add_path.png">

# 3. Download UniqueBible

Go to https://github.com/eliranwong/UniqueBible, use the download button to download a zip copy.

<img src="screenshots/downloadButton.png">

# 4. Unzip

Unzip it and place in a location you like.  In this example, we put it on desktop.  You can find the full path of the folder with file explorer, like this screenshot.

<img src="screenshots/uba_path.png">

# 5. Open Command Prompt & ENTER commands:

> cd C:\Users\elira\OneDrive\Desktop\UniqueBible

[<b>IMPORTANT!</b> In our example, we put in C:\Users\elira\OneDrive\Desktop\UniqueBible.  You need to modify the path according to the actual path of the folder in YOUR device.]

> python -m venv venv

<img src="screenshots/command_prompt1.png">

> .\venv\Scripts\activate

> pip install PySide2 PyPDF2 gdown python-docx

<img src="screenshots/command_prompt3.png">

# 6. Run

Double the file "shortcut_uba_Windows.bat" in the UniqueBible folder.

<img src="screenshots/shortcut.png">

# 7. Create a Desktop Shortcut

Right-click the file "shortcut_uba_Windows.bat", select "Send to > Desktop (create shortcut)"

<img src="screenshots/desktop_shortcut.png">