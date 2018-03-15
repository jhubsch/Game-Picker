# Game-Picker
A simple tool to help suggest a game from your backlog

In order to create your own version of this, please follow these steps:

1) Download the Game Picker HTML file.

2) Open the downloaded file in a text editor. I recommend Notepad++

3) Find a list of games you wish to modify. They are grouped by platform, as noted by comments. The first list is an "Overall" list that groups everything in one.

4) Each game is given its own line for the sake of clarity. The title is surrounded by an apostrophe on each side, followed by a comma AFTERWARDS (example: 'Grand Theft Auto V',)

5) Add your backlogged games you wish to play to the appropriate list (specific console) and/or to the Overall list. Erase the current content that is already there as well.
NOTE: Games with an apostrophe in them need a backslash before the apostrophe in the game title (example: 'Assassin\'s Creed Chronicles',)

6) When ready, save the Game Picker page and open it in a web browser. You should now be able to click on the button for a specific game system (or the Overall button if added there, too) and have your next game to play suggested for you!

----

**Advanced: Adding your own (new) system section(s)**

1) At the very bottom of the Game Picker.html file, you will see a commented out section which can be modified and subsequently used to create a new section, if you wish.

2) I would recommend copying it, then pasting it above itself so you still have a copy of the original commented out template section for later. I recommend this for any subsquent new sections you additionally add as well.

3) In the line that contains
&lt;div id="psvshell" class="shell half"&gt;
change 'psvshell' to '(somethingelse)shell' instead. For example, if making a SNES section, I'd change it to 'snesshell' which differentiates it from other systems' code blocks.
Where it says 'class="shell half"' you can change 'half' to 'full' if you want this system to stretch the width of the page (like the Overall section does). If it will go alongside another system you intend to add, then keep it as 'half'

4) In the next line, you can change 'PlayStation Vita' to the appropriate system name (ie 'Super Nintendo')

5) For the rest of the lines of this code block, using the template, you want to find both 'psv' and 'PSV' (since it's what is used in the template) and change it to your system abbreviation, keeping the same case. So, where you see 'id="psv"' you would change it to 'id="snes"' and where you see 'var myPSVGames' you would change it to 'var mySNESGames' as well. Replace lowercase iterations with lowercase and uppercase iterations with uppercase. This is part of the functionality used within the systems' code block for the Game Picker.

6) One the above is complete, feel free to edit/change the listed games, following the above Instructions (games written as 'Game Title',). You should now have your own new system Game Picker!


If anyone is aware of how to set up any of the above in a GUI, please contact me.
