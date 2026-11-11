# SAGE-WEB-ENDEC
SAGE WEB ENDEC is a SAGE DIGITAL ENDEC Simulator for those who don't have an SAGE DIGITAL ENDEC.

is a single self-contained file (no dependencies) that opens in any modern browser. I tested it headless in Chrome: the menu, RWT send, decoder, log and MSG screen all worked with no script errors. I did not listen to the audio, so check the tones and voice on your own speakers.

Front panel (from your photo)

Blue unit with the “SAGE DIGITAL ENDEC” logo, a green 24×2 LCD, and four buttons: Enter, a blank second button, △ and ▽.
The main screen shows the live date and time (11/10/26 19:30:12) with MENU WEEK … MSG underneath, as in your photo.
Enter opens MENU, the second button opens WEEK (or goes back inside menus), and ▽ opens MSG. Keyboard shortcuts are Enter, Esc/Backspace and the arrow keys.
The menu covers Originate EAS, Send RWT, Send RMT, Alert Log, Set Clock, Monitor Status, LCD Backlight and System Info.
The MSG label blinks when an unread received alert is waiting.

Web control panel

Alert Generator:
Presets for RWT, RMT, TOR, SVR, FFW and CEM.
Full event and originator lists, up to 31 location codes, a duration selector, an 8-character station ID, and an 8–25 second attention tone.
A live header preview in the ZCZC-ORG-EEE-PSSCCC+TTTT-JJJHHMM-LLLLLLLL- format.
Sources are ENDEC (originate), MON 1, and a simulated IPAWS. MON 1 and IPAWS alerts are logged as received.
Audio: three header bursts (1562.5/2083.3 Hz FSK at 520.83 baud), the 853+960 Hz attention tone, a spoken message, then three NNNN end-of-message bursts. Audio can be switched off.
Voice: the browser’s text-to-speech reads a plain-English description of the alert, or your own text. Loquendo Dave can’t be bundled, so “Auto” picks Microsoft David or Zira if your OS has them, otherwise an English voice.
SAME Decoder: paste any header to get the originator, event, locations, duration, issue and expiry times, and station ID. You can also play its bursts.
Event Log and Settings:
The log and your settings are saved in the browser.
You can set station ID, default locations, volume, TTS voice and speed, auto-forward of received alerts, and backlight.
The clock can be adjusted a minute at a time.

Known limits

County codes decode as “County 089, Indiana”, not county names, because there is no FIPS name table.
IPAWS is a simulation only; it does not connect to any real feed.
The footer notes that the audio is for mock drills and must not be played into live broadcast or phone paths.

SAGE WEB ENDEC is a SAGE DIGITAL ENDEC Simulator Full Version 1.00 on HTML File (main.html). The Sage Digital ENDEC (Model 3644) is an Emergency Alert System encoder/decoder made by Sage Alerting Systems (formerly Harris) in 2008, but not implemented until 2011. The Sage Digital ENDEC is used by many broadcasters, mostly AM/FM radio stations.
The Sage Digital has IPAWS capability as well, with its built-in TTS voice for IPAWS alerts being Loquendo Dave (unless the IPAWS alert has a live voice or another voice such as Microsoft David or Microsoft Zira). https://eas.tools (GitHub: wagwan-piffting-blud/EAS-Tools), EASyWEB for EASyPLUS Simulator https://easyweb-project.github.io/easyweb/main.html, and GitHub EASyWEB from EASyPLUS https://github.com/easyweb-project/easyweb. https://eas.tools - a suite of EAS tools for your next EAS mock, you can even generate SAME headers is to listen the burts of ZCZC Headers of the EAS Events with SAGE WEB or DIGITAL ENDEC HTML File Web Interface.
