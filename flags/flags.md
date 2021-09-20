
# Chrome Flags
In order to modify flags, you must access `chrome://flags`

## Privacy and Security

<details><summary>Enabled:</summary><p>




* #block-insecure-private-network-requests
* #clear-cross-site-cross-browsing-context-group-window-name
* #cross-origin-embedder-policy-credentialless
* #disallow-doc-written-script-loads
	* Enabling it breaks `--blink-settings="preferredColorScheme=1"`
	* If you use Brave Browser with Fingerprinting blocking Strict, just enable the flag
* #dns-httpssvc
	* Make sure you are using a secure DNS. If not, ignore it
* #enable-removing-all-third-party-cookies
* #enable-web-bluetooth-new-permissions-backend
	* Go to chrome://settings/content/bluetoothDevices and disable the permission
	* On Android, Go to Settings → Site Settings → Bluetooth → Disable the permission
* #force-effective-connection-type - **Slow 2G**
* #heavy-ad-privacy-mitigations
* #http-cache-partitioning
* #isolate-origins
* #isolation-by-default
	* Breaks captchas and DevTools
* #omnibox-default-typed-navigations-to-https
* #post-quantum-cecpq2
* #reduce-user-agent
* #restrict-gamepad-access
* #strict-extension-isolation
* #strict-origin-isolation
</p></details>

<details><summary>Disabled:</summary><p>

* #allow-sync-xhr-in-page-dismissal
* #cast-media-route-provider
* #enable-first-party-sets
* #enable-generic-sensor-extra-classes
* #enable-webrtc-remote-event-log
* #enable-winrt-geolocation-implementation
	* You might need to enable it for Maps
* #enterprise-realtime-extension-request
* #file-handling-api
* #font-access
* #font-access-persistent
* #happiness-tracking-surveys-for-desktop-demo
* #happiness-tracking-surveys-for-desktop-privacy-sandbox
* #happiness-tracking-surveys-for-desktop-settings
* #happiness-tracking-surveys-for-desktop-settings-privacy
* #hardware-media-key-handling
* #media-router-cast-allow-all-ips
* #raw-clipboard
* #safety-check-chrome-cleaner-child
* #sameparty-cookies-considered-first-party
* #show-autofill-type-predictions
* #trust-tokens
* #use-first-party-set
* #web-bundles
* #web-share
* #webid
</p></details>

## Usability

<details><summary>Enabled</summary><p>

* #content-settings-redesign
* #enable-force-dark
	* Personal preference
* #enable-reader-mode
* #global-media-controls-modern-ui
* #global-media-controls-overlay-controls
* #page-info-version-2-desktop
* #privacy-advisor
* #read-later
* #scrollable-tabstrip
* #tab-groups-auto-create
* #tab-groups-collapse
* #webui-branding-update
</p></details>

<details><summary>Disabled</summary><p>

* #detect-target-embedding-lookalikes
* #enable-translate-sub-frames
* #in-product-help-demo-mode-choice
* #smooth-scrolling
	* Personal preference
* #sms-receiver-cross-device
* #username-first-flow
* #username-first-flow-filling
</p></details>

## Performance

<details><summary>Enabled</summary><p>

* #back-forward-cache - **Enabled force caching all pages (experimntal)**
	* Make sure you are using `#http-cache-partitioning` and command line flags
* #calculate-native-win-occlusion
* #enable-lite-video
* #enable-parallel-downloading
* #enable-quic
* #enable-skia-renderer
* #enable-throttle-display-none-and-visibility-hidden-cross-origin-iframes
* #enable-vulkan - Disabled, due to causing completely black web pages and making browser laggy
	* This flag is enabled by default on some/most devices
	* If you don't experience same problem, keep this flag default
* #enable-webassembly-lazy-compilation
* #intensive-wake-up-throttling - **Enabled**
	* Enabled 10 seconds after a tab is hidden should improve battery life. However, you might have issues on some websites, like Mega.nz or Spotify (testing is required)
* #lite-video-force-override-decision
* #overlay-strategies - **Occluded and unoccluded buffers (single-fullscreen,single-on-top,underlay)**
	* Use this flag for Skylake or newer

**These flags are not intented for every device, but worth testing.**

Forcing them might be a bad idea. Therefore, before using them, please check out Problems section by typing `chrome://gpu` into the address bar (ignore WebGL errors)

* #enable-accelerated-video-decode
	* Enabled by default on Windows (probably on MacOS, too), yet not on Linux.
	* Use ``chrome://media-iternals`` to verify if you are actually getting hardware accelerated video decoding or not. [Read more](https://teddit.net/r/linux/comments/k5s4n5/google_chrome_v88_got_hardwareaccelerated/gehwpak/)
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
* #omnibox-most-visited-tiles - **Enabled**
* #page-info-discoverability - **Enabled**
</p></details>

<details><summary>Disabled</summary><p>

* #contextual-search-longpress-resolve - **Disabled**
* #related-searches - **Disabled**
* #xsurface-metrics-reporting - **Disabled**
</p></details>

## Special flags for Chromium forks

<details><summary>Brave Browser</summary><p>

* #brave-adblock-cname-uncloaking - **Enabled**
	* Keep it disabled on MacOS
* #brave-adblock-cosmetic-filtering - **Enabled**
* #brave-adblock-cosmetic-filtering-native - **Enabled**
* #brave-adblock-csp-rules - **Enabled**
* #brave-adblock-default-1p-blocking - **Enabled**
* #brave-dark-mode-block - **Enabled**
* #brave-domain-block - **Enabled**
* #brave-ephemeral-storage - **Enabled**
* #brave-ephemeral-storage-keep-alive - **Enabled**
* #brave-extension-network-blocking - **Enabled**
* #brave-speedreader - **Enabled**
* #brave-talk - **Enabled**
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
	* It should say "Enabled" to actually disable WebGL, but it's a typo.
* #num-raster-threads - 4
</p></details>

<details><summary>Edge Chromium</summary><p>

* #edge-automatic-https - **Enabled**
* #edge-autoplay-user-setting-block-option - **Enabled**
* #edge-enable-super-duper-secure-mode - **Enabled**
	* A new security feature by Microsoft. The flag disables JIT and WebAssembly (we also do it via command line flags) and enables ACG, CFG and CET mitigations
* #edge-experimental-tracking-prevention-features - **Enabled**
* #edge-log-textfield-lag - **Disabled**
* #edge-math-solver - **Disabled**
* #edge-media-autoplay-limit-default - **Enabled**
* #edge-on-demand-media-router - **Disabled**
	* Needed for Cast
* #edge-playready-drm-win10 - **Disabled**
	* Needed for Netflix, Spotify, etc.
* #edge-robin - **Enabled**
* #edge-show-feature-recommendations - **Disabled**
* #edge-toast-winrt - **Disabled**
* #edge-wdag-traffic-identification - **Disabled**
	* Enabled might improve security, yet it might be used for fingerprinting, due to sending the `X-MS-ApplicationGuard-Initiated` header
* #edge-widevine-drm - **Disabled**
	* Needed for Netflix, Spotify, etc.
</p></details>