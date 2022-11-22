# Cross-Site Scripting (XSS)
"Cross-site scripting is a web security vulnerability that allows an attacker to comporomise the interactions that users have with a vulnerable application." Attackers can get around the "same origin policy" which is sesigned to keep websites separated from each other. Attackers can act like a victem and carry out different actions, usually in the hopes of accessing a user's data. This works by finding a vulnerable website and manipulating it so that it returns malicious JavaScript to the attacker. 

It's been a long practice to use the "alert()" function to confirm the vulnerability.  When using Chrome, there is a bit of a difference.  Since Chrome 92 and on, cross-origin iframes are not allowed to call "alert()", and instead "print()" is used.  

There are 3 main types of XSS attacks:
- Reflected XSS - where the malicious script comes from the current HTTP request
- Stored XSS - where the malicious script comes from the website database
- DOM-based XSS - where the vulnerablility exists in client-side code rather than server-side