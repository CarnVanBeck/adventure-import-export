# Adventure Import Export 

A module for Foundry VTT to package and/or install adventures.

Allows content creators to create content, export and package it into a single file that can be transfered to another.  

To export an adventure, install the module and go to the module settings.  Select `Export Adventure` and select which items you would like to export by selecting the associated checkbox.  Next enter an adventure name and/or description and click export.  This will export all selected items and download it to the client.  This file can then be transfered to another and imported.

To import a file, first install the module and go to the module settings to set an import path within the data location.  If you click `Adventure Import` this will create the folder location on the server where you can place the adventure file.  Place the adventure file in the folder and got back to the module settings (you may have to close the settings and reopen inorder for the module to populate the file selector dropdown).  Select the adventure file to import and click import.  The module will create all assets within the adventure (scenes, actors, items, rolltables, playlists, and compendiums), and all images/sounds included as well.

NOTE:  The game system is stored in the adventure file, and will display a warning if you try to import an adventure using an incompatible game system.

