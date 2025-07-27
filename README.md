# WI SNIPER by ATHEX H4CK3R


"WI SNIPER is the Future of MITM WPA Attacks" It is made by athex with less bugs and more functionality. It's compatible with the latest release of Kali (rolling). The attack is mostly manual, but experimental versions will automatically handle most functionality from the stable releases.

## How It Works :

* Scan the networks.
* Capture a handshake (can't be used without a valid handshake, it's necessary to verify the password)
* Use WEB Interface
* Launch a FakeAP instance to imitate the original access point
* Spawns a MDK3 process, which deauthenticates all users connected to the target network, so they can be lured to connect to the FakeAP and enter the WPA password.
* A fake DNS server is launched in order to capture all DNS requests and redirect them to the host running the script
* A captive portal is launched in order to serve a page, which prompts the user to enter their WPA password
* Each submitted password is verified by the handshake captured earlier
* The attack will automatically terminate, as soon as a correct password is submitted..

## Changelog :
WI SNIPER gets weekly updates with new features, improvements and bugfixes.


## Requirements :
A Linux-based operating system. We recommend Kali Linux 2 or Kali 2016.1 rolling. Kali 2 & 2016 support the latest aircrack-ng versions. An external wifi card is recommended.

## Disclaimer :

WI SNIPER is intended to be used for legal security purposes only, and you should only use it to protect networks/hosts you own or have permission to test. Any other use is not the responsibility of the developer(s).  Be sure that you understand and are complying with the  licenses and laws in your area.  In other words, don't be stupid, don't be an asshole, and use this tool responsibly and legally.



Thats It... If You Like This Repo. Please Share This With Your Friends..

 Don't Forget To SUBSCRIBE My [YouTube](https://www.youtube.com/@inziXploit444)) Channel..!!!

***Thankyou.***
***Keep Visiting..***
***Enjoy.!!! :)***
