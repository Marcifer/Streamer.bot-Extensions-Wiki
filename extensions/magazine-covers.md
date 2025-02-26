---
title: 3 Magazine Covers (by Lyfesaver74)
description: Screenshots and text input from chat for Magazines, Postcard, and Newspaper
published: true
date: 2023-03-10T04:42:09.703Z
tags: 
editor: markdown
dateCreated: 2023-03-10T04:42:09.703Z
---

# Magazine Covers [(by Lyfesaver74)](https://www.twitch.tv/lyfesaver74)
All three magazine covers that are adapted from a single Codepen, GQ Cover [(by Abbey McTaggart)](https://codepen.io/amctagg1)
Source: [Codepen](https://codepen.io/amctagg1/pen/PpoQGe)

## Video Examples

<video width="960" height="540" controls>
 <source src="/extensions/magazine-covers/magazine_covers_1080-30.mp4" type="video/mp4">
</video>

# Install
1. Download and unzip [Magazine_Covers](/extensions/magazine-covers/magazine_covers.zip) to a folder of your choice.
2.  Copy `Import Code` from below and import into Streamer.bot using the `Import` button in top left of the bot.
3. Add a Browser source in OBS. Give it a name of one of the covers (GQ Cover, Vogue Cover, etc) and in the Properties:
<span class="mdi mdi-arrow-right-bold-outline"></span> ***Do not tick "Local file"*** <span class="mdi mdi-arrow-left-bold-outline"></span> 
<span class="mdi mdi-arrow-right-bold-outline"></span> ***Do not worry that we are not giving it a URL*** <span class="mdi mdi-arrow-left-bold-outline"></span>
Tick `Shutdown source when not visible`.
Tick `Refresh browser source when scene becomes active`.

![obs-browser-prop.png](/extensions/magazine-covers/obs-browser-prop.png)
Click `OK`. 
4. Repeat `Step 3` two more times using the names of the other two magazine covers. You should now have 3 browser sources, one for each magazine cover.
5. Using Windows Explorer navigate to the folder you exported the contents of the zip to and then into a folder of one of the magazine covers. 
6. Open the index.html file into your broswer of choice & click inside the address bar of the browser window and copy the location (Should start with `file:///` and end with `\index.html`)
7. In Streamer.bot go to the actions you just imported and edit the one with the name that matches the same as the index.html address you just copied. Double-click the OBS Set Browser Source URL to edit it.

![vogueprop.png](/extensions/magazine-covers/vogueprop.png)

Chose your Scene, Source and paste the address you copied into the URL box as shown above. Next take this string and paste it to the end of the RUL you just added. `?title=%rawInput%` so that the end of the string looks like this:
`/index.html?title=%rawInput%`
8. Click `OK`
9. Edit the `Take Screenshot` sub-action by double clicking it
Set the ***Scene and Source where your webcam*** is and then clcik the three dots across from `File Path` and navigate to the main folder where the three folders are and select the `cam-shot.png` file.

![sub-camshot.png](/extensions/magazine-covers/sub-camshot.png)

10. Double click each of the 2 OBS Set Soruce Visibility and set the ***Scene and Source for the OBS Browser*** source you just created
11. Repeat steps 7-10 for the other two actions, matching the file URL to the right action
12. Trigger each action with a Channel Reward (or command, voice command, deck button, etc) 

# Import Code
```text
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
```

# Contributors
- [Lyfesaver](https://www.twitch.tv/Lyfesaver74){.twitch}

- <span class="mdi mdi-codepen"></span> [Abby McTaggert on Codepen](https://codepen.io/amctagg1){.codepen}
{.contributors}