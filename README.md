# Chromium Hardening
The goal of this guide is to set up Chromium based browsers for better privacy, security, usability and performance.

## Disclaimer
I am not responsible for any direct or indirect consequences/damage resulting from their use!

## Features
* No/reduced home calling
* Privacy improvments
	* Network-State partitioning system
	* User-Agent, Color Scheme (to light), Media Devices native spoofing methods
	* Client Hints, Sensors, Idle Detection, FLoC, Reporting and many other privacy harming features blocked
	* Encrypted Client Hello enabled, previously known as Encrypted SNI
* Security improvments (mostly for Windows)
	* JITLess mode
	* GPU, Renderer and Network services in AppContainers
	* ACG and CIG mitigations in the renderer and network processes
	* Csrss lockdown
* Better performance & resource saving
	* Ameliorated caching and throttling system
	* Parallel downloading
* Better browsing usability without sacrificing privacy

## Let's start
* [Flags](./flags/flags.md)
* [Command Lines](./flags/chrome-command-line.md)
* [Extensions](./recommendations/extensions.md)

## Credits
* [NRK](https://github.com/N-R-K)
* [Brave](https://github.com/brave/)
* [Bromite](https://github.com/bromite/)
* Λdam#3185
* CHEF KOCH

## Donation
Monero: `46FQDwvrc3uNAEGrptoMSwY3oAdmFNVnjc8jzkCTw9MG9XTstDU2JwjTADyphKhqDw9mKBjU8eaUacLErHmDqvvWFpCQW3N`

## License
Licensed under GNU General Public License v3.0