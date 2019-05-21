# TODO

These items relate to improving the experience of customizing Jingles
 for the Steam Controller:

* Add executables for SCJingleConverter to directory
    * Mac, Linux, Windows
    * External library issues a concern or all statically linked and built into exe?
* Revisit this md
    * Start byte targeting user who just wants to add Jingle Data to their SC
    * Mention why musicXML
    * Walkthrough ways to get music 
        * (i.e. use musescore, convert midi to musicxml)
        * Look into other options like AnthemScore to try https://www.lunaverus.com/?
            * Or not since this maybe isn't free?
    * Keep technical info, but maybe link to separate .md for those who are interested?
    * Make section on SCJingleConverter
        * What is purpose?
        * How to use 
        * How to build
    * Add steps on loading (and restoring) firmware to steam controller
        * Make a separate .md and link here and in Firmware section
            * This way we do not miss updates and improvements
        * What if you didn't backup your fw?
            * Test to make sure that updating to ble fw via Steam then updating LPC FW to 2016 fw manually will not cause issues
            * Steps on how to download from the web... Link to Steam help forum source
* Comments, comments, comments for SCJingleConverter
    * Mostly just needed in mainwindow at this point

* The immediate path to being done
    * Review and see if there are any major TODOs left for GUI functionality
    * Move onto documentation/presentation for this and the remainder of the project
    * Use tools to add Mario Theme to Faux Pro Controller

* Something off with Channels lining up sometimes...
    * Mario Maker 2 with Measure 2 - 6 and Part 1 Voice 1 and Part 1 Voice 5

* Testing
    * Start using musicxml files that have not been trimmed
    * Try to find musicxml configuration we are not prepared for
        * Could backup be used to designate more than two "parts" within an official part token?
* Make child SCSerial class for case of not having controller connected?
    * Allows user to select method that writes commands out to file for manual input later??
* GUI
    * Accept compressed musicXML (.mxl)
        * Can use https://musescore.com/sheetmusic to get new tunes directly?
    * Add window to show serial communications?
        * Gives user idea of what we are doing when Jingles are being updated on controller