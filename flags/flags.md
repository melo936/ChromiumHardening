
# Chrome Flags
In order to modify flags, you must access `chrome://flags`

## Privacy and Security

<details><summary>Enabled:</summary><p>

* #block-insecure-private-network-requests
* #clear-cross-browsing-context-group-main-frame-name
* #disallow-doc-written-script-loads
* #dns-httpssvc
* #enable-browsing-data-lifetime-manager
* #enable-web-bluetooth-new-permissions-backend
	* Go to chrome://settings/content/bluetoothDevices and disable the permission
	* On Android, Go to Settings → Site Settings → Bluetooth → Disable the permission
* #force-effective-connection-type - **Slow 2G**
* #freeze-user-agent
* #heavy-ad-privacy-mitigations
* #http-cache-partitioning
* #isolate-origins
* #isolation-by-default
	* Breaks captchas and DevTools
* #legacy-tls-enforced
* #mixed-forms-disable-autofill
* #mixed-forms-interstitial
* #omnibox-default-typed-navigations-to-https
* #post-quantum-cecpq2
* #schemeful-same-site
* #strict-origin-isolation
</p></details>

<details><summary>Disabled:</summary><p>

* #allow-sync-xhr-in-page-dismissal
* #cast-media-route-provider
* #compute-pressure
* #enable-first-party-sets
* #enable-generic-sensor-extra-classes
* #enable-quic
	* QUIC: See here why you should keep it disabled:
		> https://www.ghacks.net/2020/07/01/how-to-enable-http-3-support-in-firefox/#comment-4467237
		> https://www.reddit.com/r/uBlockOrigin/comments/66k0eh/psa_disable_quic_in_your_chromiumbased_browser/
		> https://brave.com/quic-in-the-wild/
		> https://www.fastvue.co/fastvue/blog/googles-quic-protocols-security-and-reporting-implications/
	* If you really have a slow internet and you prefer speed over security, keep it Enabled.
* #enable-sxg-prefetch-cache-for-navigations
* #enable-sxg-subresource-prefetching
* #enable-webrtc-remote-event-log
* #enable-winrt-geolocation-implementation
	* You might need to enable it for Maps
* #enterprise-realtime-extension-request
* #file-handling-api
* #font-access
* #font-access-persistent
* #form-controls-dark-mode
* #happiness-tracking-surveys-for-desktop-demo
* #happiness-tracking-surveys-for-desktop-privacy-sandbox
* #happiness-tracking-surveys-for-desktop-settings
* #happiness-tracking-surveys-for-desktop-settings-privacy
* #hardware-media-key-handling
* #load-media-router-component-extension
* #privacy-sandbox-settings
* #safe-browsing-real-time-url-lookup-enterprise-ga-endpoint
* #safety-check-chrome-cleaner-child
* #show-autofill-type-predictions
* #trust-tokens
* #use-first-party-set
* #use-multilogin-endpoint
* #web-bundles
* #web-share
* #webid
</p></details>

## Usability

<details><summary>Enabled</summary><p>

* #content-settings-redesign
* #enable-force-dark
	* Personal preference
* #enable-new-profile-picker
* #enable-reader-mode
* #global-media-controls-cast-start-stop
* #global-media-controls-modern-ui
* #global-media-controls-overlay-controls
* #global-media-controls-picture-in-picture
* #global-media-controls-seamless-transfer
* #privacy-advisor
* #read-later
* #scrollable-tabstrip
* #tab-groups-auto-create
* #tab-groups-collapse
</p></details>

<details><summary>Disabled</summary><p>

* #in-product-help-demo-mode-choice
* #media-router-cast-allow-all-ips
* #ntp-cache-one-google-bar
* #passwords-account-storage
* #passwords-account-storage-iph
* #raw-clipboard
* #smooth-scrolling
	* Personal preference
* #sms-receiver-cross-device
* #username-first-flow
</p></details>

## Performance

<details><summary>Enabled</summary><p>

* #back-forward-cache - **Enabled force caching all pages (experimntal)**
* #calculate-native-win-occlusion
* #enable-lite-video
* #enable-parallel-downloading
* #enable-skia-renderer
* #enable-webassembly-lazy-compilation
* #intensive-wake-up-throttling - **Enabled** (10 sec can be used, as well)
* #lite-video-force-override-decision
* #overlay-strategies - **Occluded and unoccluded buffers (single-fullscreen,single-on-top,underlay)**
* #turn-off-streaming-media-caching-always
* #turn-off-streaming-media-caching-on-battery

**These flags are not intented for every device, but worth testing**
* #enable-accelerated-video-decode
	* Enabled by default on Windows (probably on MacOS, too), yet not on Linux.
	* Use ``chrome://media-iternals`` to verify if you are actually getting hardware accelerated video decoding or not. [Read more](https://old.reddit.com/r/linux/comments/k5s4n5/google_chrome_v88_got_hardwareaccelerated/gehwpak/)
* #enable-gpu-rasterization
* #enable-zero-copy
* #ignore-gpu-blocklist
* #use-angle
	* According to the flag's description, using the OpenGL driver as the graphics backend may result in higher performance
	* D3D11 is used by default; D3D12 may improve performance if you are using Windows 10 1709 or newer.
</p></details>

## Android
**Note:** These are "special flags" for Android. of course, above mentioned flags work too.

<details><summary>Enabled</summary><p>

* #actionable-content-settings - **Enabled**
* #download-auto-resumption-native - **Enabled**
* #enable-instant-start - **Enabled**
* #enable-site-isolation-for-password-sites - **Enabled**
* #enable-site-per-process - **Enabled**
* #enable-tab-groups-ui-improvments - **Enabled**
* #omnibox-most-visited-tiles - **Enabled**
* #page-info-discoverability - **Enabled**
* #page-info-version-2 - **Enabled**
* #privacy-reordered-android - **Enabled**
* #tabbed-app-overflow-menu-icons - **Enabled**
	* If you don't like new icons in menu, you can keep this flag disabled. `#tabbed-app-overflow-menu-regroup` and `#tabbed-app-overflow-menu-three-button-actionbar` won't have any effect.
* #tabbed-app-overflow-menu-regroup - **Enabled**
* #tabbed-app-overflow-menu-three-button-actionbar - **Enabled (three button with action chip view)**
* #omnibox-native-voice-suggestions-provider - **Disabled**
</p></details>

<details><summary>Disabled</summary><p>

* #contextual-search-longpress-resolve - **Disabled**
* #related-searches - **Disabled**
* #toolbar-iph-android - **Disabled**
* #xsurface-metrics-reporting - **Disabled**
</p></details>

## Special flags for Chromium forks

<details><summary>Brave Browser</summary><p>

* #brave-adblock-cosmetic-filtering - **Enabled**
* #brave-adblock-cosmetic-filtering-native - **Enabled**
* #brave-adblock-csp-rules - **Enabled**
* #brave-domain-block - **Enabled**
* #brave-ephemeral-storage - **Enabled**
* #brave-ephemeral-storage-keep-alive - **Enabled**
* #brave-extension-network-blocking - **Enabled**
* #brave-permission-lifetime - **Enabled**
* #brave-speedreader - **Enabled**
* #sidebar - **Enabled**
</p></details>

<details><summary>Ungoogled Chromium</summary><p>

* #extension-mime-request-handling - **Always prompt for install**
* #fingerprinting-canvas-image-data-noise - **Enabled**
* #fingerprinting-canvas-measuretext-noise - **Enabled**
* #fingerprinting-client-rects-noise - **Enabled**
</p></details>

<details><summary>Bromite</summary><p>

* #disable-webgl - Disabled
	* It should be enabled to actually disable WebGL, but it's a bug in Bromite.
* #num-raster-threads - 4
</p></details>
