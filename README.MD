STEPS FOR RUNNING THE SCRIPT : 

1. Install Python:
Download and install the latest version of python from the official website: https://www.python.org/downloads/windows/
During installation, make sure to check the option that adds Python to the system PATH.

2.Install a VSCODE:
This is the text editor that we will use to edit and run the script
Download from : https://code.visualstudio.com/download

3. Install Chrome Browser:
Download and install the latest version of Chrome from the official website since our script uses chrome: 
Chrome : https://www.google.com/chrome/?brand=CHBD&brand=YTUH&gclid=CjwKCAiApuCrBhAuEiwA8VJ6JsWRQZ1zr9OxsR-MMiZe-N27lU6LRHSQy_VTu2j683PYcXyeVPD0LxoCpsQQAvD_BwE&gclsrc=aw.ds

4. Download ChromeDriver:
Go to https://googlechromelabs.github.io/chrome-for-testing/ scroll to stable and download the chromedriver win64 zip file / win32 based on your system.
Extract the zip file into a folder that you know the location of.
Then on windows search "edit the system environment variables" and click on it.
You should get a menu like this : 

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.imatest.com%2Fsupport%2Fdocs%2F23-2%2Fediting-system-environment-variables%2F&psig=AOvVaw1mgNn-8_7_dfWLBbnDtF8_&ust=1702474717582000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCJDxg9mCioMDFQAAAAAdAAAAABAD)

Then click the Environment Variables button at the bottom.

Under "System Variables" click on "path" and press "edit".

Then click on "new" , "browse" and select the folder that contains the chromedriver.exe file.

Open a command prompt (cmd) or PowerShell.

Navigate to the directory where you have your script using the cd command.

5. Installations
Open VisualStudio Code
pip install selenium
Run the Script:

Use your preferred text editor or IDE to open the Python script file (spotify.py in this case).

Update any necessary configurations in the script, such as the file paths or URLs.

Save the changes.

In the command prompt or PowerShell, navigate to the directory containing your script and the virtual environment.

Run the script using the command:

bash
Copy code
python spotify.py
The script should start executing, and you should see the output in the console.

Observe Execution:

Keep an eye on the command prompt or PowerShell to observe any errors or output messages from the script.
