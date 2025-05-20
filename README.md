# countdown
Simple Javascript Countdown Clock.

To use, just download the countdown.html file to your desktop and double-click on the file to open. 

This page was written with AI and modified slightly to accept some parameters and work with local (non UTC) time.

Optional query string params:
1. end
Where end=YYYY-MM-DDTHH:MM:SSZ or end=NNNNNNNNNNNNN (in miliseconds since January 01, 1970 UTC).
Sets the countdown clock end time.
Example: ?end=2025-12-31T23:59:59Z or ?end=1735689599000

3. p
Where p=[Some string to be displayed]
Sets the display for the purpose of this countdown.
Example: ?p=Ice%20Cream! would show "Countdown to Ice Cream!" in the page.
