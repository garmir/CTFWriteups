**Completed**

# Prerequisites

* Description:

Some underground hackers are developing a new command and control server. Can you break in and see what they are up to?

# Solution:

Tried bruteforcing login to web page, but had no luck. The next option would be to try sql injection, which got me through the login page.

I was taken to a default error page, "http://docker.hackthebox.eu:31912/panel.php?info=home", and wasn't too sure what to look for beyond this point, due to not knowing the suitable string for "info=".

This turned out to be fairly straightforward, and a dictionary attack revealed the string to be "flag", which I really should have thought of beforehand.

This new page had the flag in plaintext.

٩(^ᴗ^)۶ We found the flag!
