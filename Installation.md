# Steps for Windows

## Installing Anaconda launcher:-

* Go to the following website:- [Anaconda Distribution](https://www.anaconda.com/distribution/#windows)

* Click on the download button. Install the Python 3.7 version for Windows Operating System.

* Double click the installer to launch.

* Click Next.

* Read the licensing terms and click “I Agree”.

* Select an install for “Just Me” unless you’re installing for all users (which requires Windows Administrator privileges) and click Next.

* Select a destination folder to install Anaconda and click the Next button. 

  *Note: Install Anaconda to a directory path that does not contain spaces or unicode characters.*

* Choose whether to add Anaconda to your PATH environment variable. **I recommend not adding Anaconda to the PATH environment variable, since this can interfere with other software. Instead, use Anaconda software by opening Anaconda Navigator or the Anaconda Prompt from the Start Menu.**

* Choose whether to register Anaconda as your default Python. Unless you plan on installing and running multiple versions of Anaconda, or multiple versions of Python, accept the default and leave this box checked

* Click the Install button.

* Click the Next button. 

* An option for **Installing VSCode** might appear. You can use Jupyter notebooks (which comes with Anaconda launcher) or VSCode to run the codes. So, it is upto you whether to install VSCode or not.

* After a successful installation you will see the “Thanks for installing Anaconda” dialog box

* After your install is complete, verify it by opening Anaconda Navigator, a program that is included with Anaconda: from your Windows Start menu, select the shortcut Anaconda Navigator. If Navigator opens, you have successfully installed Anaconda. If not, check that you completed each step above, then see the Help page.

## Installing OpenCV

* Open the Start Menu.

* Type "Anaconda" in the search area. You will an option that appears like "Anaconda Prompt".

![alt text](https://chrisconlan.com/wp-content/uploads/2017/05/anaconda_prompt.png)

* Open it. Let the command line show something like 
  
  `(base) C:\Users\Arnab Sinha>` 
  
 * Type one of the following commands: 
 
    1. conda install -c conda-forge opencv 
    2. conda install -c conda-forge/label/gcc7 opencv 
    3. conda install -c conda-forge/label/broken opencv 
    4. conda install -c conda-forge/label/cf201901 opencv 
  
  * Let OpenCV install. 
  
  * Type the following command:  `jupyter notebook`
  
  * Jupyter Notebook will open and you can then copy the python code given in this repository and run it in the notebook.
    
