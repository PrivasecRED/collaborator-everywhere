# Collaborator Everywhere

This is an updated version of Collaborator Everywhere which aims to:
- support Custom Collaborator servers
- support external listeners such as https://app.interactsh.com/  (simply for pingbacks)
- support the picking and choosing of headers during extension runtime
- provide a graphical interface for the options listed above

## Build Instructions

```shell
gradle fatJar
```  

Further setup and build information can be found here:  
https://portswigger.net/research/adapting-burp-extensions-for-tailored-pentesting

## Archive Text

This is a Burp Suite Pro extension which augments your in-scope proxy traffic by injecting non-invasive headers designed to reveal backend systems by causing pingbacks to Burp Collaborator.
 
To use it, simply install it and browse the target website. Findings will be presented in the 'Issues' tab. You can easily customise injected payloads by editing /resources/injections

For further information, please refer to the whitepaper at [https://portswigger.net/research/cracking-the-lens-targeting-https-hidden-attack-surface](https://portswigger.net/research/cracking-the-lens-targeting-https-hidden-attack-surface)
