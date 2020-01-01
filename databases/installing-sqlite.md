# Installing SQLite

### Installing on a Mac
Many times `sqlite` comes installed already on a Mac. You're going to want the latest versio as well which is `sqlite3`. So open up a terminal and type:
```bash
sqlite3
```
If it's installed, something like this will come up:
```
SQLite version 3.30.0 2019-10-04 15:03:17
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite> 
```
Otherwise, there's a number of ways to install it. One of the more common ways on a Mac is iva Homebrew.
```bash
brew install sqlite3
```

### Installing on Linux
My guess if you're installing on a Linux distro you probably have a really good idea what you're doing already. But just to go with the tutorial, installing on one of the most popular Linux Distros, Ubuntu, you would enter the following in the terminal:
```bash
sudo apt-get install sqlite3
```

### Installing on Windows
Go to the [downloads page](https://www.sqlite.org/download.html) and download the "bundle" (format: sqlite-tools-win32-x86-XXXXXXX.zip; currently the 3rd choice) which has the command-line shell as well. It's not a hard requirement, BUT, if you want quick and easy ways to load data and do some other stuff outside of using a programming language or a SQL GUI you will want the command-line shell:
1. Once you down your file, e.g. `sqlite-tools-win32-x86-3300100.zip`. Unzip it and place it in your `C:\` home directory. You will want to extract the contents to a folder and name that folder `sqlite3`.
2. Next you're going to want to add that directory to your PATH so you can invoke the database `exe` on the CMD prompt from any location on your computer. Enter `control panel` in your search bar. From there the path to what you need is `System and Security` > `System` > `Advanced System Settings` > `Environment Variables`. From the bottom section, titled `System variables`, click on the `PATH` to highlight that row and select `edit`. Hit `New` and enter the path to the `sqlite3` folder you created, which should just be `C:\sqlite3`. Click `OK` until you exit out of those menus.
3. Test to see if your PATH setup is correct by opening up a `CMD` prompt and typing:
```
sqlite3
```
If installed and set up correctly you should see something like this:
```
SQLite version 3.30.0 2019-10-04 15:03:17
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite> 
```
You can type your first `dot command`
```
.exit
```
to exit.

### Installing a SQL Client (or GUI)
There's A TON to choose from. So you can try out as many as you'd like. But for our use case we're going to use `DBeaver`. You can download it [here](https://dbeaver.io/download/).

We will want the free version, which is the `Community Edition` (left column).

If you don't already have Java (the JRE part) installed, you should download a version with that. So pick your appropriate link depending on your operating system.


For Windows users, if still having problems, can find videos on [YouTube](https://www.youtube.com/watch?v=m07aJy2foNw) or Google around for installing dbeaver.







