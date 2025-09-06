# HTML-Injection-Projects-Demo
## Tools and Technologies used

## 🛠 Setup
- *OS:* Kali Linux on VMware  
- *Tool:* Burp Suite  
- *Target App:* OWASP BWA(Security level: Low)  

## project-1:HTML-Injection-on User-Agent-Field in mutillidae II
 This file explains the process of performing *HTML Injection User-Agent-Field in mutillidae II * in a vulnerable web app using Burp Suite. 

## 🔹 Steps:
1.Open Kali linux and OWASP BWA should be running at the same time.
2.then open Burpsuite and Firefox browser open.
3.go to the website of OWASP BWA and choose Mutillidae II then choose HTML injection on User-agent-Field.
## screenshot:Before Doing HTML-Injection on User-Sgent-Field
link:https://github.com/akshayapendem/HTML-Injection-Projects-Demo/blob/master/html%20User-agent%20-Field%20injection/before%20user-agent%20injection.png

4.search to inject HTML code if the website (which is Mutillidae II in home Lab ) is vulnerable it shows injected code.
5.Ex : <h1><u>TEST</u></h1>
6. if it shows TEST in underlined format then it is Vulnerable to html injection.
 ## Screenshot:After Successfully injecting HTML code into User-Agent-Field.
 link:https://github.com/akshayapendem/HTML-Injection-Projects-Demo/blob/master/html%20User-agent%20-Field%20injection/before%20user-agent%20injection.png

## project-2:HTML via Cookie injection mutillidae II
1..Open Kali linux and OWASP BWA should be running at the same time.
2.then open Burpsuite and Firefox browser open.
3.go to the website of OWASP BWA and choose Mutillidae II then choose HTML injection via Cookie injection.
## screenshot:Before Doing HTML-Injection via Cookie injection

4.pass the request through burpsuite by keeping the intercept ON.
5.edit the COOKIE value (ex:<meta http-equiv="refresh" content=10"; URL=http=https://WWW.google.com"/>)
6. then exactly after 10 sec the page redirects to google.com.
## screenshot:After Successfully Doing HTML-Injection via Cookie injection
## Conclusion : successfully done the html injection projects and used only tools that are provided for practice but not on real websites.
