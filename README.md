# ppShow
show most used emotes of twitch chat

Special credits to twitch.tv/omeiaum for the idea, i just coded it
<br>
<i>'dvd mode' may now work properly in Firefox, please prefer chromium based browsers (like Chrome)</i>
<br> TY <3


## BASIC USAGE:

* Dowload both tmi.js and ppShow.html (or clone the repo) to a folder, open ppShow.html with your browser

* Connect: <br>
	- Type the twitch channel name in the top-right input field and click connect.


* Emotes not changing/appearing or it's too slow/fast? <br>
	- Click on options and change 'minimal aount os mentions' and 'Zero the count...' to lower/higher numbers


* 'DVD Mode'? <br>
	- Bounce the image on screen sides, just like the dvd logo, but with emotes
	- Click on options and mark the "DVD Stant-by bouncing" to enable
	- Mark "Don't clear canvas" to keep the path as the image moves


## IMPORTANT NOTICE:
Both options 'zero after messages' and 'min. mentions' affect how often they will appear on screen keeping low values (ex: -1 and 5) in both will make it change faster.
This will depend on chat speed, the ammount of messages
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

