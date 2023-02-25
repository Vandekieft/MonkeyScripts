# MonkeyScripts
A spot for my UserScripts that I have for Violent Monkey

# Copy YouTube Channel ID

This is a userscript that adds a "Copy Channel ID" button to the top of YouTube channels. When clicked, this button copies the channel ID to the clipboard. Additionally, this script also provides two menu commands: "Copy Channel URL" and "Go to Channel URL". "Copy Channel URL" copies the URL of the current channel to the clipboard, while "Go to Channel URL" redirects the page to the URL of the current channel.

## Usage

To use this userscript, you will need a userscript manager extension installed in your browser. This script has been tested on the Violentmonkeyv2.13.11 extension for Firefox.

> Prerequisites: Install a userscript manager extension in your browser (if you don't have one already). I prefer [Violent Monkey](https://violentmonkey.github.io/) | [FireFox](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) or [Chormium](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)

Method 1:
* Head over to [The Greasy Fork script page](https://greasyfork.org/en/scripts/460715-copy-youtube-channel-id), and click install

Method 2:
* Open the userscript manager dashboard and create a new userscript.
* Copy and paste the script into the userscript editor, or paste the RAW url in "Install from URL". 
   - RAW url ->[Copy YouTube Channel ID](https://raw.githubusercontent.com/Vandekieft/MonkeyScripts/main/CopyYouTubeChannelID.txt)
* Save the userscript and refresh the YouTube page.

Once the script is installed and running, you should see a "Copy Channel ID" button at the top of YouTube channels. Clicking this button will copy the channel ID to your clipboard. You can also access the "Copy Channel URL" and "Go to Channel URL" menu commands by right-clicking on the YouTube page.

### > Note:  
* I have not actually been able to get the button to work, so just the options in the menu are known to work. Check the image for reference. 
* If you are loading a @CHANNEL-NAME from the main page, you may have to refresh the page for the script to pull the Channel ID

![image](https://user-images.githubusercontent.com/834985/221347981-7e9299ce-bef0-403b-b780-23b5759fed82.png)

* Copy Channel URL 
  - Like: http://www.youtube.com/channel/UCBJycsmduvYEL83R_U4JriQ
* Go to Channel URL
  - Takes you from current Channel URL to Channel ID Url, Like: https://www.youtube.com/@mkbhd to http://www.youtube.com/channel/UCBJycsmduvYEL83R_U4JriQ


[MIT License](https://opensource.org/license/mit/)  You can use this script however you want for free.
