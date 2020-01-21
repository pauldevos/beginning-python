### Getting Your Development Environment Setup

For this course we're going to do all things in a Linux environment. You're welcome to try to do many of the things on your Mac OS or Windows environment, however, there's going to be some extra hoops involved, and especially so for Windows. The idea is we want to spend as little time as possible on "administration" of software, from setup to configuring to provisioning. Those things are good to know in part for when you need to troubleshoot but at most companies you will have decidated teams to help set up your environments and management software systems. As a entry level Data Analyst (or similar role) your main "work" will be using SQL, SQL databases, Python, a command line language like Bash, and possibly Excel and/or Tableau. You will use various dialects of SQL to extract data from large database systems (both SQL and NoSQL). You will use SQL and Python to clean data from string/text manipulation to building formulas for complex calculations. You will use Python in Jupyter Notebooks, Tableau, and/or possibly Excel to visualize and present data to end users. Much of your work will be cleaning data and that's not much different than what a Sr Data Scientist would do. You will clean data and try to make it repeatable. That is, the process you develop should be able to work on future data sets to clean it for data analysis and your code should be readable and able to be taken by someone else and run on their machine to produce the same results.

### Setting up our Environment
We are going to use free open source tools for our environment, namely VirtualBox and Mint Linux. VirtualBox is a "VM" (Virtual Machine) tool that allows us to "spin up" another operating system on our computer, namely a type of Linux called Mint, which is a fork of Ubuntu. Ubunto being a fork of Debian. But that's just for historical purposes, don't worry about memorizing those details. Bottom line, we're going to use VirtualBox to provision a Linux machine. We're using Linux because it's the unquestioned "de facto" environment in which software is provisioned in the world. It's also the easiest to install software on. So most used and easiest to use make it a no brainer for our purposes.

=> Setting up VirtualBox with Mint (Linux)
=> Installing Python


### Installing Python
There's tons and tons and more tons of tutorials and blogs on installing Python on your machine (regardless of OS). I will likely paste a few popular ones here.
- Mac
    - brew install python3
    - download [Miniconda3](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh) and install it
        ```bash
        bash Miniconda3-latest-MacOSX-x86_64.sh
        ```
- Windows
    - Official Python website
    - Anaconda3 Installer (Yes, the big ugly package)
    - Miniconda3
- Linux
    - Minconda3
    - sudo apt-get install python3 (altho, I think most distros today have it)


### Virtual Environments and Package Managers
- venv and pip
- [conda](https://docs.conda.io/en/latest/) and pip
- [poetry](https://python-poetry.org/)
    - 

### CI/CD
- CircleCI
- PyTest
- Articles
    - [RealPython: Continuous Integration With Python: An Introduction](https://realpython.com/python-continuous-integration/)

