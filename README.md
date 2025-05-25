# countdown
Simple Javascript Countdown Clock.

To use, just download the countdown.html file to your desktop and double-click on the file to open. 

This page was written with AI and modified to accept some parameters and work with local (non UTC) time.

Optional query string params:
1. end: Where end=YYYY-MM-DDTHH:MM:SSZ or end=NNNNNNNNNNNNN (in miliseconds since January 01, 1970 UTC).
Sets the countdown clock end time. Example: ?end=2025-12-31T23:59:59Z or ?end=1735689599000
2. p: [Optional] Where p=[Some string to be displayed] Sets the display for the purpose of this countdown. Example: ?p=Ice%20Cream! would show "Countdown to Ice Cream!" in the page.
3. bg: [Optional] Where bg=#RRGGBB for background color in hex. Example: ?bg=%23eef2f7. %23 is URL encoding for #.
4. fc: [Optional] Where fc=#RRGGBB for foreground color in hex. Example: ?fc=%23222222
5. bgimageurl: [Optional] Where bgimageurl=http://someurl. URL to an image to show in the background of the page.
6. usebdays: [Optional] Where usebdays=[0|1] for whether to show the countdown in business days.

Here's the configuration page hosted on a Github's web-server, so you don't have to download the page:
https://codewrought.github.io/countdown/
