# Installation 

## Git

To complete this tutorial, you will need to install Git on your computer.

Git is free and open source, it is available for Windows, Mac, and Linux.

### Installing Git

To install Git, follow the instructions on the official Git website for your operating system:

!!! Failure ""
    === ":simple-windows:"
        Following the installation [guide for Windows](https://git-scm.com/download/win), we have a few options.

        From these options, the simplest and most popular option is to download the [Git for Windows](https://gitforwindows.org/) installer.

        The step-by-step instructions for installing Git for Windows are (copied from the Git for Windows website):
        
        1. Navigate to the latest [Git for Windows installer](https://gitforwindows.org/) and download the latest version.
        2. Once the installer has started, follow the instructions as provided in the Git Setup wizard screen until the installation is complete.

        !!! tip "Git Bash"
            During the installation, you will be given the option to install Git Bash. Git Bash is a terminal emulator that provides a Bash shell for Git on Windows. 
            
            **This is the recommended option.**

            You can open Git Bash from the start menu, just as we did with the Windows Command Prompt.

            **^^From this point on, we will assume that you have selected this option whenever we use the 'git' command in the terminal.^^**

        3. Open the windows command prompt (or Git Bash if you selected not to use the standard Git Windows Command Prompt during the Git installation).

    === ":simple-apple:"
        Following the installation [guide for Mac](https://git-scm.com/download/mac), we have a few options.

        From these options, the simplest two options are:
        
        * [Xcode Command Line Tools](https://developer.apple.com/xcode/features/)
        * [Homebrew](https://brew.sh/)
        
        <h2> XCode </h2>

        You can install Xcode through the [App Store](https://apps.apple.com/us/app/xcode/id497799835?mt=12) (recommended) or by running the following command in your terminal:
        
        ```bash
        xcode-select --install
        ```

        Installing Xcode Command Line Tools will also install Git.

        <h2> Homebrew </h2>

        Alternatively, you can install Homebrew. Homebrew is a package manager for macOS that makes it easy to install and update Git, as well as a myriad of other software packages. If you develop software on a Mac, you should consider installing Homebrew.

        **Note:** Xcode is a prerequisite for Homebrew, so you will need to install Xcode before installing Homebrew.

        Installation instructions for Homebrew can be found on the [Homebrew website](https://brew.sh/).

        You can install Homebrew by running the following command in your terminal (copied from the Homebrew website):
        
        ```bash
        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
        ```

        Once Homebrew is installed, you can install Git by running the following command in your terminal:
        
        ```bash
        brew install git
        ```
    === ":simple-linux:"
        Following the installation [guide for Linux](https://git-scm.com/download/linux), we see that different linux distributions have different installation methods depending on the package manager used. 

        For Ubuntu, you can install Git by running the following command in your terminal:
        
        ```bash
        sudo apt-get install git-all
        ```

        (See link for other Linux distributions.)

[Git Guides](https://github.com/git-guides/install-git) is also a good resource for installing Git on Windows, Mac, and Linux.

### Checking the Installation

You can check that Git is installed by running the following command in your terminal (depending on how you installed Git on Windows, this may be Git Bash terminal):

!!! warning ""
    ```bash
    git version
    ```

Which should return something like this:

!!! warning ""

    ```
    git version 2.39.1
    ```

### Configuring Git

Git is a command-line tool, so you will need to open a terminal window to use it. If you are using Windows, you can open a terminal window by pressing the Windows key and typing "terminal" in the search box. Then, click on the "Terminal" application.

If you are using Mac, you can open a terminal window by pressing the Command key and the space bar at the same time. Then, type "terminal" in the search box and press the Enter key.

If you are using Linux, you can open a terminal window by pressing the Ctrl key and the Alt key at the same time. Then, type "terminal" in the search box and press the Enter key.

Once you have opened a terminal window, you can use the following commands to configure Git:

!!! warning ""

    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "example@email.com"
    ```

Replace "*Your Name*" with your name and "*example@email.com*" with your email address.


<center>
## You Have Successfully Installed Git! :tada:

[You can now move to the next session](stage_2.md)
</center>