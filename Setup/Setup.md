## FireFox Setup With FoxyProxy Extension For BURP:

    FireFoxSettings → General → Network Settings
        Click ‘Manual Proxy Configuration’

            HTTP Proxy: 127.0.0.1		Port: 8080
            Check ‘Also use this proxy for HTTPS’

![Firefox](https://github.com/iakil/Codepath_Cybersecurity/blob/main/FirefoxSettings.png?raw=true)

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

![FoxyProxy ADDON](https://github.com/iakil/Codepath_Cybersecurity/blob/main/FoxyProxyAddons.png?raw=true)

---

    Open: BURP Suite → Target → Scope → Load

Load [Scope.txt](Setup/src/scope.txt)

Click Yes for - 'Proxy History logging'