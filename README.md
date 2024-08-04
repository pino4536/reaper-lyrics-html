# reaper-lyrics-html
Lyrics for reaper - suitable for stage use when blocks of lyric are in reaper, especially for only few midi lyrics holder item with lines of lyrics


# Installation
1. Open Reaper Perference (Ctrl-P by default)
2. Category: Control/OSC/web >> Add a new web browser interface >> mode: Web browser interface
3. Below the drop down menu, click the button "User pages..." to open the user html folder
4. Put this project .html file into the folder
5. Re-open the control surface adding window to reload the drop down menu, the html file should be listed.

** note: it is recommended to use other port number as port 8080 is usually used by other process running web services. You can pick any port from 1-65535 in theory. for instance I use 12345 / 23456 / etc.


# Usage
- LAN usage (same Wi-Fi network): Copy the URL (e.g. http://192.168.x.x:8080) and open with Chrome web browser.
- WAN usage (over internet): Check the checkbox "Use rc.reaper.fm" and input some random letter to form your unique id for your website host. This would run a web service on your computer and connect to internet, which allows your friends to connect to your reaper DAW.


 # Q&A

 For more questions and tutorial please refer to office reaper documentation or just google: 'reaper control surface web'
