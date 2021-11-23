Exploit Title: Active eCommerce Laravel CMS 5.5.2 - Cross Site request forgery (CSRF) to Cross-site Scripting (XSS) (Authenticated)</br>
Date: 25/11/2021</br>
Exploit Author: Keyvan Hardani</br>
Vendor Homepage: https://activeitzone.com/</br>
Google Dork: intext:|| WHOPPS!!!THIS IS PIRATED COPY OF ACTIVE ECOMMERCE CMS</br>
Software Link: https://codecanyon.net/item/active-ecommerce-cms/23471405</br>
Version: up to 5.5.2</br>
Tested on: Windows 10, Kali Linux, Burp Suite</br></br></br>

Steps to Reproduce:</br></br>

1. At first login as customer to the site</br>
2. then click the navigation bar and open "Support Ticket"</br>
3. search for Token ( _token ) on source code and copy the value</br>
4. Option 1: save the script as html and paste the _token into token field and hit submit</br>
5. Option 2: use XSS payload </textarea><script>alert(document.domain)</script> in Description or subject value on support ticket.</br>
5. Now Generate a CSRF POC</br></br></br>

[![Everything Is AWESOME](https://img.youtube.com/vi/9Gxr8JjQAUQ/0.jpg)](https://www.youtube.com/watch?v=9Gxr8JjQAUQ "Everything Is AWESOME")</br>


DISCLAIMER: This exploit is for testing and educational purposes only. Any other usage for this code is not allowed. Use at your own risk.
