## FireFox Setup With FoxyProxy Extension For BURP:

    FireFoxSettings → General → Network Settings
        Click ‘Manual Proxy Configuration’

            HTTP Proxy: 127.0.0.1		Port: 8080
            Check ‘Also use this proxy for HTTPS’

![Firefox](https://github.com/iakil/CodePath_Cybersecurity/blob/main/Setup/src/FirefoxSettings.png)

---

### If you Download [FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) Extention in FireFox: 
       
    * FireFoxSettings → General → Network Settings
            Click ‘Use System Proxy Settings’

    * Click On FoxyProxy Extention → Option → Add
        Title: Burp
        Proxy Type: HTTP
        Proxy IP or DNS: 127.0.0.1
        Port: 8080
        Click ‘Save’

![FoxyProxy ADDON](https://github.com/iakil/CodePath_Cybersecurity/blob/main/Setup/src/FoxyProxyAddons.png)

---

    Open: BURP Suite → Target → Scope → Load

Load [Scope.txt](https://github.com/iakil/CodePath_Cybersecurity/blob/main/Setup/src/scope.txt)

Click Yes for - 'Proxy History logging'