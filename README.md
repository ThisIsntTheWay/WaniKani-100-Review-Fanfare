A tampermonkey userscript written by me.

Inspired by @PabloM from https://community.wanikani.com/t/victory-sound-for-100-review-result/45632

# Wanikani 100% Review Fanfare

🎉 A 100% review score is hard! Congratulate yourself with a wonderful fanfare!
- Plays a jingle upon achieving 100%.
- Smothers the screen with confetti.
- GreaseMonkey menu to make easy changes to this userscript.

---

**Latest version:**  v0.5.1

**Download** **:** [https://greasyfork.org/en/scripts/410114-wanikani-100-review-fanfare ](https://greasyfork.org/en/scripts/410114-wanikani-100-review-fanfare)

**Known issues:**

* Firefox and Chrome can sometimes block autoplay audio
* Wanikani must have been given permission to play audio before the script will work

**Credits:**

* Original script: me
* Update to fix autoplay, additional changes: [ThisIsntTheWay](https://github.com/ThisIsntTheWay)
* js-confetti by: [loonywizard](https://github.com/loonywizard/js-confetti)
* Idea by: [@PabloM](https://community.wanikani.com/u/pablom/summary)
* Audio by: Nintendo

If you encounter any problems, please let me know below!

---

To change the fanfare being played, use the "Set jingle" menu in GreaseMonkey.  
You can either set an URL to a valid MP3 file, or provide b64 encoded audio data.  
*b64 encoded data MUST begin with `data:audio/type;base64`.

To encode b64 data, use [this tool](https://base64.guru/converter/encode/audio) and select `Data URI` as the output format.

*By default the Zelda BotW "Key Item" fanfare is played.  