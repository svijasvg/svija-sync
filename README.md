[En français](https://github.com/svijasvg/svija-sync/blob/master/lisez-moi.md) · [Source Document](https://docs.svija.com/en/quick-start/1-1-svija-sync)
![Svija: SVG-based websites built in Adobe Illustrator](http://files.svija.com/github/readme-logo.png "Svija: SVG-based websites built in Adobe Illustrator")

Svija Sync 1.1.4
-------------------------------------

**Svija** Sync is a **script**: a small application that only does one thing.

As long as it's running, **it synchronizes your website with your computer.**

You can also use it to download the complete set of files needed to work on your website.

Short Version
-------------

*For experienced users; see below for a more complete description.
*An asterisk indicates that you may see a security alert for this step.*

**Download Svija Sync** via [this link](https://github.com/svijasvg/svija-sync/archive/master.zip).

Create a work folder and put **Svija Sync.command 0.0.0.txt** in it.

Open the file and **replace the single "x"** with the three lines of red text in the email you got from Svija :

    site='example.com'
    user='example'
    pass='eY-v354strs'

Then rename the script:* 

    sync.command 0.0.0-fr.txt becomes
    sync.command

**Click twice** on Svija Sync.command to start the script.*

The first time you run it, choose **Download.***

The script will download all the files for you site into **a new folder called "sync"**, in the same place as Svija Sync.

Complete Version
----------------

#### Download Svija Sync

Download [this .zip file](https://github.com/svijasvg/svija-sync/archive/master.zip), or:

1.  visit [github.com/svijasvg/svija-sync](https://github.com/svijasvg/svija-sync)
2.  click on  **Code** (green button)
3.  choose **Download ZIP**

**Open the downloaded ZIP file** (if it didn't happen automatically).

* * * * *

#### Move Svija Sync

1.  Create a **work folder** for your new website
2.  **Drag Svija Sync.command 0.0.0.txt** into the folder
3.  Put the other files **in the trash**.

* * * * *

#### Configure Svija Sync

On your computer:

**Double click Svija Sync.comand 0.0.0.txt **to open it in TextEdit.

**Look for the single "x"** on the fourth line of text:

![sync-te-en-x](https://docs.svija.com/wp-content/uploads/elementor/thumbs/sync-te-en-x-1-ot4im2e1tuzkez0psre5kwijus9elm2egg35gmx9rs.jpg "sync-te-en-x")

**Replace the single "x"** with the three lines of red text in the email you received from Svija:

    site='example.com'
    user='example'
    pass='lYtr384Ytrs'

![sync-te-en-coords](https://docs.svija.com/wp-content/uploads/2020/07/sync-te-en-coords.jpg "sync-te-en-coords")

**Close** the file, then **rename it** to remove the part after .command:

    Svija Sync.command 0.0.0.txt becomes
    Svija Sync.command

You may see the following warning:

![finder-extension-change](https://docs.svija.com/wp-content/uploads/elementor/thumbs/finder-extension-change-onwwosepuqtvpw8jx7nf86l79qukvnq1zyin4gjxuk.jpg "finder-extension-change")

**Click "Use .command".**

Changing the filename extension means that the next time the file is opened, it will be launched as an application rather than opened as a text file.

* * * * *

#### Launch Svija Sync

**Double click** **Svija Sync.command** to launch it.

If you do not see the following warning, you can skip the next step:

![can't-be-opened](https://docs.svija.com/wp-content/uploads/elementor/thumbs/cant-be-opened-onwworgvnwt2l0ubilqgmgiy76vjjb2x1k2xqv9wtg.jpg "can't-be-opened")

To continue, go in to **System Preferences › Security & Privacy › General**:

![security-preferences](https://docs.svija.com/wp-content/uploads/elementor/thumbs/security-preferences-onwwosepuqymrt7ld70dqsk3aaowqhgciauxnzx490.jpg "security-preferences")

**Click "Open Anyway"**

The script should launch normally, and you will be asked for your name:

![sync-en-what-is](https://docs.svija.com/wp-content/uploads/elementor/thumbs/sync-en-what-is-ot4i8ry776syjeq905siy0qxpyu3j7hqirbpekjn68.jpg "sync-en-what-is")

**Enter Your First Name**

The name is used to show your collaborators who last worked on your site:

![sync-en-name](https://docs.svija.com/wp-content/uploads/2020/07/sync-en-name.jpg "sync-en-name")

**The Instruction Screen**

You will then be presented with the instructions:

![sync-en-instructions](https://docs.svija.com/wp-content/uploads/elementor/thumbs/sync-en-instructions-ot4i8r0d0cro7srm5ndwdizh4kyqbie06mo7xal1cg.jpg "sync-en-instructions")

**Press D for Download**

The first time you connect to your website, your computer will ask you to accept its authenticity.

You'll see the following message:

    The authenticitiy of host name & IP of your site can't be established...
    ECDSA key fingerprint is SHA256:lkjdqmlfkjqsdf098sdflkj...
    Are you sure you want to continue connecting (yes/no)?

**You must type "yes" **then return (not just y).

The application will then download your site files in **a new folder called "sync"** in the same folder as Svija Sync:

-   **admin**: logo and colors for Svija Admin
-   **desktop**: site content, desktop version
-   **fonts**: necessary fonts
-   **images**: favicon, Apple touch icon & homepage capture
-   **mobile**: site content, mobile versionmobile
-   **scripts**: scripts used for animations and special effects
