# Web-Attacks-and-Defenses
In this project,first find the vulnerabilities of a web app called BitCoin through several attacks, and then update the web app to defend these attack. 

## BitCoin
BitCoin is a Node.js web app that lets users manage Bitbars, a new ultra-safe cryptocurrency. It is built using Express.js, SQLite database and ESJ. 
<img width="1428" alt="security" src="https://user-images.githubusercontent.com/55666152/126855391-e0488c87-795b-4b46-9e34-8aad3b453ee6.png">


## Attacks 
* Cookie theft: steals the logged in user’s Bitbar session cookie and send it to an attacker controlled URL
* Cross-Site Request Forgery: constructs a Cross Site Request Forgery (CSRF) attack that steals Bitbar from another user.
* Session Hijacking with Cookies: tricks the Bitbar application into thinking you’re logged in as a different user by hijacking the victim’s session cookie
* Cooking the Books with Cookies: forges 1 million new Bitbar rather than stealing them from other users
* SQL Injection: develops a malicious username that executes malicious SQL against the backend database that powers the Bitbar application.
* Profile Worm: develops a Worm, similar to the Samy Worm, which steals Bitbar and spreads to other accounts.
* Password Extraction via Timing Attack: develops an attack that determines the password of another user by exploiting such a timing side-channel.

## Defenses
Updated web app to defned attacks based on Input Sanitation, Secret Token Validation, Signature and CSP policies
