# ppShow
show most used emotes of twitch chat

Special credits to twitch.tv/omeiaum for the idea, i just coded it
<br>
<i>'dvd mode' may now work properly in Firefox, please prefer chromium based browsers (like Chrome)</i>
<br> TY <3


## BASIC USAGE:

1. Dowload both tmi.js and ppShow.html
	* OR clone the repo (click on code -> download zip)
	* OR go to [Releases](https://github.com/Gnitoon/ppShow/releases) and download the latest

2. Open the ppShow.html with your browser
3. type the channel name in the input and click "connect"

* You may wanto to click on settings to change:
	- theme (dark/light)
	- minimal amount of mentions to show an emote
	- zero the emote count after a certain amount of messages
	- enable 'dvd mode' to make image bounce on your screen sides
		- change speed, speed random multiplier and leave or not the trace
	- enable debug to print messages on devTools console (inspect/ctrl+shift+i/F12 key -> console)
	- change emote size
	- 
_these options are available to change directly in the code, look at the object ```data: { options: {...}}``` (line 655 on ppShow.html)_



* Emotes not changing/appearing or it's too slow/fast? <br>
	- Click on options and change 'minimal aount os mentions' and 'Zero the count...' to lower/higher numbers


* 'DVD Mode'? <br>
	- Bounce the image on screen sides, just like the dvd logo, but with emotes
	- Click on options and mark the "DVD Stant-by bouncing" to enable
	- Mark "Don't clear canvas" to keep the path as the image moves



## DEMO video
https://user-images.githubusercontent.com/80431627/110715426-fbfaa980-81e3-11eb-951f-cb03c3c89904.mp4
![](https://user-images.githubusercontent.com/80431627/110715426-fbfaa980-81e3-11eb-951f-cb03c3c89904.mp4)



## IMPORTANT NOTICE:
Both options 'zero after messages' and 'min. mentions' affect how often they will appear on screen keeping low values (ex: -1 and 5) in both will make it change faster.
This will depend on chat speed,

 the ammount of messages
<br> 

For most cases 5~ and 20~ will be good for 'emote bursts'
<br>
That is, zero the count every 20 messages and if have more than 5 mentions show it

## Credits:
* <a href="https://twitch.tv/omeiaum" target="_blank" class="link">oMeiaUm</a>
* <a href="https://vuejs.org/" target="_blank" class="link">Vue.js</a> framework
* <a href="https://tmijs.com/" target="_blank" class="link">tmijs package</a> (to connect with twitch chat)
* <a href="https://betterttv.com/" target="_blank" class="link">BetterTTV</a> (emotes and APIs)
* <a href="https://www.frankerfacez.com/developers" target="_blank" class="link">FrankerFaceZ</a> (channel info)
* <a href="http://developpaper.com/using-canvas-to-make-a-dvd-standby-animation-implementation-code/" target="_blank" class="link">developpaper.com</a>('dvd mode' code base)
* <i>Icon (favicon) by me, based on a random emote from "ppS" bttv search, made with random pixelArt online tool</i>


## LICENSE: <a href="https://opensource.org/licenses/MIT" target="_blank" class="link">MIT</a>

