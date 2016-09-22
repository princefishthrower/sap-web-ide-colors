# sapwebidecolors
Custom Color Tampermonkey / Greasmonkey Scripts for Editor Colors in SAP Web IDE

Short Story: I was sad when SAP took the Monokai color scheme from their Web IDE, so I wrote a short userscript to get it back.

# Installation Directions

1. For Chrome users, you will need to install the Tampermonkey extension:        
[https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)    
For Firefox users, you will need to install the Tampermonkey extension:         
[https://addons.mozilla.org/de/firefox/addon/tampermonkey/](https://addons.mozilla.org/de/firefox/addon/tampermonkey/)

2. Once you've install Tampermonkey, simply copy the raw code from `sapwebidecolors.js` into a Tampermonkey.

3. FINALLY, AND MOST IMPORTANT: In the script, make sure to put your "s" username in the url!    
(I'm not sure if there are other types of user names for the Web IDE, but if there are, put it there. You just want the @match line to be the same as your personal webide URL.)

4. You are done. Enjoy and happy coding!

# Issues/Changes/Updates
As far as I've tested, and I've been using it in full productive scenarios, the script affects only color and no functionality of the IDE. Make an issue if you find one!

Sometimes the editor color is not changed quickly, and sometimes only half the colors are implemented, this could have something to do with the `waitForKeyElements()` function that I use...

Coming soon: more color schemes in addition to Monokai.
