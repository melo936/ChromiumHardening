
# Chrome Flags
In order to modify flags, you must access `chrome://flags`

## Privacy and Security

<details><summary>Enabled:</summary><p>

* #block-insecure-private-network-requests
* #disable-process-reuse
	* When enabled, out-of-process iframes will not try to reuse compatible processes from unrelated tabs, which might decrease performance. 
	* The flag is force-enabled in command-line flags, due to it is hidden in MS Edge(://flags)
* #disallow-doc-written-script-loads
	* Enabling it breaks `--blink-settings="preferredColorScheme=1"`
	* If you use Brave Browser with Fingerprinting blocking Strict, just enable the flag
* #enable-isolated-sandboxed-iframes
* #enable-web-bluetooth-new-permissions-backend
	* Go to `chrome://settings/content/bluetoothDevices` and disable the permission
	* On Android, Go to Settings → Site Settings → Bluetooth → disable the permission
* #enable-webrtc-hide-local-ips-with-mdns
* #force-effective-connection-type - **Slow 2G**
* #isolate-origins
* #partitioned-cookies
* #reduce-user-agent
* #strict-origin-isolation
</p></details>

<details><summary>Disabled:</summary><p>

* #enable-fenced-frames
* #enable-first-party-sets
* #enable-generic-sensor-extra-classes
* #enable-prerender2
* #enable-webrtc-remote-event-log
* #enable-webusb-device-detection
* #enable-winrt-geolocation-implementation
	* You might need to enable it for Maps
* #file-handling-api
* #font-access
* #full-user-agent
* #media-router-cast-allow-all-ips
* #sameparty-cookies-considered-first-party
* #show-autofill-type-predictions
* #system-keyboard-lock
* #trust-tokens
* #use-first-party-set
* #web-bundles
* #web-share
* #web-sql-access
</p></details>

## Usability

<details><summary>Enabled</summary><p>

* #download-bubble
	* If you prefer MS Edge's download bubble style, then enable it, yet it might not be stable
* #enable-force-dark
	* Personal preference
* #enable-tab-audio-muting
* #extensions-menu-access-control
* #global-media-controls-modern-ui
* #scrollable-tabstrip
* #sharing-desktop-screenshots
* #sharing-desktop-screenshots-edit
* #side-panel
* #side-panel-drag-and-drop
* #side-panel-improved-clobbering
* #unified-side-panel
</p></details>

<details><summary>Disabled</summary><p>

* #in-product-help-demo-mode-choice
* #in-product-help-snooze
* #smooth-scrolling
	* Personal preference
* #username-first-flow
* #username-first-flow-fallback-crowdsourcing
* #username-first-flow-filling
</p></details>

## Performance

<details><summary>Enabled</summary><p>

* #back-forward-cache - **Enabled force caching all pages (experimntal)**
	* Make sure you are using command line flags
* #enable-parallel-downloading
* #enable-quic
* #enable-throttle-display-none-and-visibility-hidden-cross-origin-iframes
* #enable-vulkan - Disabled, due to causing completely black web pages and making browsers laggy
	* This flag is enabled by default on some/most devices
	* If you don't experience the same problem, keep this flag default
* #enable-webassembly-lazy-compilation
	* This flag is placebo when JITLess mode and Strict Security mode in MS Edge are activated
* #overlay-strategies - **Occluded and unoccluded buffers (single-fullscreen,single-on-top,underlay)**
	* Use this flag for Skylake or newer
* #subframe-shutdown-delay
* #throttle-foreground-timers
* #unthrottled-nested-timeout

**These flags are not intented for every device, but worth testing.**

Forcing them might be a bad idea. Therefore, before using them, please check out the Problems section by typing `chrome://gpu` into the address bar (ignore WebGL errors)

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

* #enable-instant-start - **Enabled**
* #enable-site-isolation-for-password-sites - **Enabled**
* #enable-site-per-process - **Enabled**
* #omnibox-most-visited-tiles - **Enabled**
</p></details>

<details><summary>Disabled</summary><p>

* #contextual-search-longpress-resolve - **Disabled**
* #related-searches - **Disabled**
</p></details>

## Special flags for Chromium forks

<details><summary>Brave Browser</summary><p>

These flags are from Nightly builds, some of them might not be available in other builds.

* #brave-adblock-cname-uncloaking - **Enabled**
	* If you notice DNS leak, disable it
* #brave-adblock-cosmetic-filtering - **Enabled**
* #brave-adblock-csp-rules - **Enabled**
* #brave-adblock-default-1p-blocking - **Enabled**
* #brave-dark-mode-block - **Enabled**
* #brave-de-amp - **Enabled**
* #brave-debounce - **Enabled**
* #brave-domain-block - **Enabled**
* #brave-domain-block-1pes - **Enabled**
* #brave-ephemeral-storage - **Enabled**
* #brave-ephemeral-storage-keep-alive - **Enabled**
* #brave-extension-network-blocking - **Enabled**
* #brave-first-party-ephemeral-storage - **Enabled**
* #brave-reduce-language - **Enabled**
* #brave-speedreader - **Enabled**
* #restrict-websockets-pool - **Enabled**
</p></details>

<details><summary>Ungoogled Chromium</summary><p>

* #extension-mime-request-handling - **Always prompt for install**
* #fingerprinting-canvas-image-data-noise - **Enabled**
* #fingerprinting-canvas-measuretext-noise - **Enabled**
* #fingerprinting-client-rects-noise - **Enabled**
</p></details>

<details><summary>Bromite</summary><p>

* #disable-webgl - Disabled
	* It should be "Enabled" to actually disable WebGL, but it's a typo.
* #num-raster-threads - 4
</p></details>

<details><summary>Edge Chromium</summary><p>

* #edge-automatic-https - **Enabled**
	* Go to `edge://settings/privacy`, enable `Automatically switch to more secure connections with Automatic HTTPS` and choose `Always switch from HTTP to HTTPS (connection errors might occur more often)`
* #edge-autoplay-user-setting-block-option - **Enabled**
	* Go to `edge://settings/content/mediaAutoplay` and set `Control if audio and video play automatically on sites` to `Block` 
* #edge-enable-bfcache-features - **Enabled**
* #edge-global-media-controls - **Enabled**
* #edge-haptics-api - **Disabled**
* #edge-log-textfield-lag - **Disabled**
* #edge-msb-all-dse - **Disabled**
* #edge-msb-keyword-mode - **Disabled**
* #edge-playready-drm-win10 - **Disabled**
	* Needed for Netflix, Spotify, etc.
* #edge-robin - **Enabled**
* #edge-sdsm-emulate-acg - **Enabled**
* #edge-show-feature-recommendations - **Disabled**
* #edge-toast-winrt - **Disabled**
* #edge-wdag-optional-network-isolation - **Enabled**
* #edge-widevine-drm - **Disabled**
	* Needed for Netflix, Spotify, etc.
</p></details>
