## Extensions
My biggest recommendation is to avoid extensions as much as you can.

* [uBlockOrigin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - An open-source content blocker
* [Violentmonkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) - Useful for scripting
* [Redirector](https://chrome.google.com/webstore/detail/redirector/ocgpenflpmgnfapjedencafcfakcekcd) - Automatically redirects content based on user-defined rules

### Fingerprinting
Extensions do not/cannot guarantee 100% protection, due to revoked access to workers (which causes leakage). They may be vulnerable when `ToString()` is requested.

* [Jshelter](https://chrome.google.com/webstore/detail/jshelter/ammoloihpcbognfddfjcljgembpibcmb) - Defends against all types of Fingerprinting.
	* Do not use it in Brave Browser and Ungoogled Chromium
