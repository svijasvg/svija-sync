[Version en français](https://github.com/svijasvg/svija-sync/blob/master/readme-fr.md)

Svija Sync is a **script**: a tiny app that just does one thing.

As long as it's running, it will **keep your website synchronized with your computer**.

You can also use it to download all the files needed for working on your website.

# Download the App

1. Click the green button **Clone or download** at the top right of this page then choose **Download ZIP**.

2. **Open the downloaded ZIP file** (if it didn't happen automatically).

2. **Drag the appropriate TXT document** (English or French) into a new working folder where all your website files will be kept.

*Put the other files in the Trash.*

# Add Your Credentials

1. **Click twice on the TXT document** to open it in TextEdit.

2. **Replace the "**x**"** on the fourth line with the **three lines of red text** in the email you've received from Svija:  

```
site='example.com'  
user='example'  
pass='#r4nd0m#'  
```
*Save the changes and quit TextEdit.*

# Start the App

Rename the TXT file to **Svija Sync.commmand**. This tells the Mac that it's no longer a text document but an app.

**Click twice** on the app to run it. You may see a warning:

>"Svija Sync.command" can't be opened because it is from an unidentified developer.

To continue, open **System Preferences** › **Security and Privacy** › **General**.

At the bottom you'll see a similar message:

>"Svija Sync.command" was blocked from opening because it is not from an identified developer.

Click the button **[Open Anyway]**

# Once the App is Running

Choose **Download** to create the **sync folder** containing your website files.

The first time that you connect, **your computer will ask you to accept the authenticity of your web site**.

You will see the following message:

>The authenticitiy of host _____ can't be established.  
>ECDSA key fingerprint is SHA256:lkjdqmlfkjqsdf098sdflkj.  
>Are you sure you want to continue connecting (yes/no)?

Type "yes" then enter (not "y").

The app will then download the files into a new folder "sync", in the same folder as the Svija Sync app.

# What's Inside?

Everything you need to update your website in this folder:

* Illustrator source files
* SVG files exported from Illustrator, that you'll never touch
* linked images, in a subfolder called "links"
* web fonts and a "source" subfolder with Mac fonts
* assorted images like the favicon, the icon for an iPhone shortcut, and a capture of the homepage that will be shown when the web site is posted to social media

# General Usage

Whenever you want to work on your website, **double-click "Svija Sync.comand" to start syncronizing** your website.

As long as the app is running, your files will be synchronized every five seconds (a new red bar appears).

# What Next?

If you will be using Svija regularly, the [Svjia Illustrator scripts](https://github.com/svijasvg/illustrator-scripts) will make your life much easier.

You can download them [here](https://github.com/svijasvg/illustrator-scripts).