# issue_20190606
Exploit Title : RedGreenBD IT Solutions XSS Reflected Cross Site Scripting

Impact - Reflected XSS Cross Site Scripting (or Non-Persistent) :
*********************************************************
The server reads data directly from the HTTP request and reflects it back in the 
HTTP response. Reflected XSS exploits occur when an attacker causes a victim to supply 
dangerous content to a vulnerable web application, which is then reflected back to the victim
 and executed by the web browser. The most common mechanism for delivering malicious 
content is to include it as a parameter in a URL that is posted publicly or e-mailed directly 
to the victim. URLs constructed in this manner constitute the core of many phishing 
schemes, whereby an attacker convinces a victim to visit a URL that refers to a vulnerable site. 
After the site reflects the attacker's content back to the victim,the content is 
executed by the victim's browser. A successful exploit could allow the attacker
to execute arbitrary script code in the context of the affected site
and allow the attacker to access sensitive browser-based information.
An attacker, for example,can exploit this vulnerability to steal cookies from
the attacked user in order to hijack a session and gain access to the device.
