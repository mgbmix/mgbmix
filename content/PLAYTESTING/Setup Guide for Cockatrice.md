
# HOW TO SET UP [[COCKATRICE]]

1. Go to the Cockatrice website [https://cockatrice.github.io/](https://cockatrice.github.io/ "https://cockatrice.github.io/") and download the program and install it.

> [!note] Note for Linux users 
> The website's installer might give you an outdated dependency error (it did for me). Instead, use the flatpak installer. I accessed the flatpak via my distro's Software Manager link with flathub.

2. Download the [[Latest Files]] linked in the site's ⁠repository. There are currently three choices for download.

- The xml file will be posted uncompressed
- The Images needed to be placed in Cockatrice will be linked to a Google Drive. You can view them and download a compressed folder containing them. 
- The custom theme that improves Cockatrice's coloring and includes the Mondo cardback and mini-hand assets.

Extract the files if needed.

3. Launch Cockatrice and you'll get a welcome screen like this. Dismiss the pop-up.
![[cockatrice-first-boot.png]]

4. Cockatrice will next try to autobuild a card database for [[MtG|Magic: the Gathering]]. We don't need to run this tool because we will be adding a pre-built database for Mondo Megabits. Click Cancel to close the importer tool.

![[cockatrice-oracle-importer.png]]

5. Cockatrice will give a warning pop-up after closing the importer. Click No to close this window and continue with the Mondo Megabits setup.

![[cockatrice-database-dialog.png]]

6. In Cockatrice's top navigation bar, click Cockatrice, then ⚙️Settings. The Settings window will open on the General tab. This is where you need to find the location on your PC that Cockatrice checks for database files.

7. Under the Paths section, look at the row called "Card Database:" and make a note of its folder path (you might as well open that location in a file explorer now). Also, you can see (on your screen, not in the screenshot) that the "Card Database:" row ends not in a folder name but with the 'cards.xml' file. This is fine and keep everything as is; just make sure you know its location.

For reference, a Windows user's file path might look like:  
`PLACEHOLDER until I know what this structure is`   

For reference, an Apple user's file path might look like:   
`PLACEHOLDER until I know what this structure is`  

For reference, a Linux user who installed the flatpak's file path might look like:   `/home/yourusername/.var/app/io.github.Cockatrice.cockatrice/data/Cockatrice/Cockatrice/cards.xml`   
NB: to navigate in a file explorer to folders that start with a period, set your view options to show hidden files 

> [!note]
> After verifying the location of the card database and clicking ✔️OK to dismiss the Settings window, you will likely get the Error message as shown in the screenshot. This is still fine, click ✖️No to dismiss.  
>  We want to keep the same database location and put the Mondo database there.

![[Screenshot_2023-09-09_13-00-07.jpg]]


8. If you didn't already, open a file explorer to the card database location that was shown in your General Settings: Paths window. Here's an example of the data folder (with the Mondo file already added).

![[cockatrice-data-folder.png]]

9. Copy the 'cards.xml' file from the mgbmix archive into Cockatrice's "base data directory" as you see in the screenshot. It should be the exact same location as in the Settings Window.


#### Section for Adding Card Art

10. Additionally, you can add the Mondo Megabits card images if you downloaded the archive containing them. From that "base data directory" where you put the 'cards.xml' file, open the pics folder, then the CUSTOM folder, and copy into that directory the entire folder named "D01" from the Google Drive. This screenshot shows an example of where the "D01" folder containing all the images should be located.

> [!warning] NB: Don't change the name of the "D01" folder.

![[cockatrice-mondo-pics-location.png]]


#### Section for Adding Custom Theme (Colours, Cardback)

11. Add the extracted theme folder into the Themes folder of Cockatrice's "base data directory." Like this:

![[Screenshot at 2023-10-19 01-26-47.png]]


12. That's it! The next time you open Cockatrice, it might notify you about detecting a new database and show you the sets included, but all the cards will be browsable in the deck editor. Some of the sorting columns work and some don't, just a limitation of using a program aimed at M:tG. From here you can look over the cards, build decks, playtest offline, or log into the public server and play against other people who have the mondo cardsets installed. 

![[Screenshot at 2023-10-19 01-30-10.png]]
An example of what Cockatrice's deck editor looks like with -mgbmix- cards and custom theme loaded.

Have fun!




