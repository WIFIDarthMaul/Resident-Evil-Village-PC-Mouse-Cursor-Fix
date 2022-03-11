# Resident Evil Village PC Mouse Cursor Fix
Resident Evil Village on PC shows a visible mouse cursor, that moves around while you move the player's camera, when certain resolutions are selected, such as ultrawide resolutions or lower 5:4 resolutions, such as my monitor's 1280x1024.



It is a very annoying and pressing issue, that is quite distracting and detrimental to the games playability. This is a simple Python Script to fix that issue. It works by utilizing Ducky Script converted to Python, to open the mouse settings and automatically change the cursor to an invisible one, the resorting back to the default cursor once the game is closed, all within a few seconds.

How To Install:
1. Install Python, if you have not done so already
2. Open CMD and type "pip install pyautogui", without quotation marks of course. (If you get a pip error, follow this [guide](https://www.activestate.com/resources/quick-reads/how-to-install-pip-on-windows/#:~:text=One%20of%20the%20most%20common,the%20command%20to%20launch%20it.) and add "pip" to Windows Environment Variables)
3. Once finished, extract "RE8 Hide Mouse Cursor.py" in your Resident Evil 8 Village game folder,
   and extract "HiddenCursor.cur" to C:\Windows\Cursors\
4. Right-Click on "RE8 Hide Mouse Cursor.py" and click "Send To", then select "Desktop (create shortcut)"
5. Then open the shortcut on your Desktop. It will type and do some processes, but DO NOT TOUCH YOUR KEYBOARD WHILE IT DOES THIS.
6. Once it finishes, it will open the game. It will leave a window open, DO NOT CLOSE IT.
7. Once you close the game, then press Enter on the window that was open. It will revert your mouse cursor to default. AGAIN, DO NOT TOUCH YOUR KEYBOARD WHILE IT RUNS.

OPTIONAL:
You can change the Shortcut's icon to the Game's icon if you Right-Click on it, then click "Change Icon",
and navigate to your Resident Evil Village game folder and then select "re8.exe"

[Download](https://github.com/WIFIDarthMaul/Resident-Evil-Village-PC-Mouse-Cursor-Fix/raw/main/RE8%20Village%20Mouse%20Cursor%20Fix.zip)
