## Command Line

```
--block-new-web-contents --disable-background-networking --disable-breakpad --disable-composited-antialiasing --disable-crash-reporter --disable-default-apps --disable-domain-reliability --disable-external-intent-requests --disable-notifications --disable-webgl --extension-content-verification=enforce_strict --extensions-install-verification=enforce --gpu-rasterization-msaa-sample-count=0 --no-pings --num-raster-threads=4 --process-per-site --site-per-process --use-fake-device-for-media-stream --enable-features="AudioWorkletThreadRealtimePriority,BlockInsecurePrivateNetworkRequests,BlockInsecurePrivateNetworkRequestsForNavigations,BrowserDynamicCodeDisabled,EnableCsrssLockdown,EncryptedClientHello,GpuAppContainer,ImprovedCookieControlsIsolateOrigins,LegacyTLSEnforced,MinimizeAudioProcessingForUnusedOutput,NetworkServiceCodeIntegrity,NetworkServiceSandbox,OriginIsolationHeader,PartitionConnectionsByNetworkIsolationKey,PartitionDomainReliabilityByNetworkIsolationKey,PartitionExpectCTStateByNetworkIsolationKey,PartitionHttpServerPropertiesByNetworkIsolationKey,PartitionNelAndReportingByNetworkIsolationKey,PartitionSSLSessionsByNetworkIsolationKey,PartitionedCookies,PrefetchPrivacyChanges,ReduceUserAgent,ReducedReferrerGranularity,SandboxExternalProtocolBlocked,SplitAuthCacheByNetworkIsolationKey,SplitCacheByIncludeCredentials,SplitCacheByNetworkIsolationKey,SplitHostCacheByNetworkIsolationKey,StrictOriginIsolation,ThirdPartyStoragePartitioning,UseRegistrableDomainInNetworkIsolationKey,WebAppEnableIsolatedStorage,WinSboxDisableExtensionPoint,WinSboxDisableKtmComponent" --disable-features="AppActivityReporting,AutofillEnableAccountWalletStorage,AutofillServerCommunication,AutoupgradeMixedContent,ClearCrossSiteCrossBrowsingContextGroupWindowName,ComputePressure,ConversionMeasurement,CopyLinkToText,CrashReporting,CriticalClientHint,CrossOriginOpenerPolicyAccessReporting,CrossOriginOpenerPolicyReporting,CrossOriginOpenerPolicyReportingOriginTrial,CrostiniAdditionalEnterpriseReporting,DirectSockets,DocumentReporting,EnableSignedExchangePrefetchCacheForNavigations,EnableSignedExchangeSubresourcePrefetch,EnableStructuredMetrics,EnableSubresourceWebBundles,EnterpriseRealtimeExtensionRequest,EventBasedStatusReporting,ExpectCTReporting,ExperimentalJSProfiler,FederatedLearningOfCohorts,FlocIdComputedEventLogging,GreaseUACH,HandwritingRecognitionWebPlatformApiFinch,IdleDetection,InterestCohortAPIOriginTrial,InterestCohortFeaturePolicy,LangClientHintHeader,MediaDrmPreprovisioning,NetworkTimeServiceQuerying,NotificationTriggers,PasswordCheck,PrefersColorSchemeClientHintHeader,ReportAllJavaScriptFrameworks,Reporting,SafeBrowsingEnhancedProtection,SignedExchangeReportingForDistributors,SubresourceWebBundles,TabMetricsLogging,TextFragmentAnchor,UserAgentClientHint,ViewportHeightClientHintHeader,WebNFC,WebXR,WinrtGeolocationImplementation,WinrtSensorsImplementation" --connectivity-check-url="0.0.0.0" --crash-server-url="0.0.0.0" --gaia-url="0.0.0.0" --gcm-checkin-url="0.0.0.0" --gcm-mcs-endpoint="0.0.0.0" --gcm-registration-url="0.0.0.0" --google-apis-url="0.0.0.0" --google-base-url="0.0.0.0" --google-doodle-url="0.0.0.0" --lso-url="0.0.0.0" --oauth-account-manager-url="0.0.0.0" --override-metrics-upload-url="0.0.0.0" --realtime-reporting-url="0.0.0.0" --sync-url="0.0.0.0" --url="0.0.0.0" --variations-server-url="0.0.0.0" --cipher-suite-blacklist="0xc013,0xc014,0x009c,0x009d,0x002f,0x0035" --enable-strict-mixed-content-checking --js-flags="--jitless --noexpose_wasm" --blink-settings="dnsPrefetchingEnabled=false,preferredColorScheme=1,strictMixedContentChecking=true,strictMixedContentCheckingForPlugin=true,strictlyBlockBlockableMixedContent=true" --disable-blink-features="PrefersContrast,GravitySensor" --isolation-by-default
```

Triple click to select the entire line.
 
<details><summary><b>Worth to mention</b></summary><p>

| Name | Description |
| :--- | :---------- |
| --disable-frame-rate-limit | Disables frame rate limiting |
| --enable-low-end-device-mode | Forces low-end device mode <br> Reduces memory usage a lot and also quaility of videos and images |
| --user-agent="useragent" | A string used to override the default user agent with a custom one |
| --use-mobile-user-agent | Forces mobile user agent |
</p></details>

## Documentation
<details><summary>Flags</summary><p>

| Name | Description |
| :--- | :---------- |
| --block-new-web-contents | Blocks all pop-ups |
| --cipher-suite-blacklist | Blocks lists of cipher suites |
| --disable-background-networking | Blocks background networking, like Safe browsing |
| --disable-breakpad | Disables the crash reporting |
| --disable-composited-antialiasing | Disables layer-edge anti-aliasing in the compositor |
| --disable-crash-reporter | Disables the crash reporting |
| --disable-default-apps | Disables installation of default apps |
| --disable-domain-reliability | Disables Domain Reliability Monitoring |
| --disable-external-intent-requests | Never forward URL requests to external intents |
| --disable-notifications | Disables notifications |
| --disable-webgl | Disables WebGL |
| --enable-strict-mixed-content-checking | Blocks passive and active mixed content <br> (AutoupgradeMixedContent must be disabled) |
| --extension-content-verification | Extensions verification |
| --extensions-install-verification | Extensions verification |
| --gpu-rasterization-msaa-sample-count | Numbers of multisample antialiasing samples for GPU rasterization <br> are based on DPI for desktops <br> For Android it's 4. 0 disables MSAA which helps to improve performance |
| --isolation-by-default | Change several web APIs that make it difficult to isolate origins into distinct processes |
| --js-flags=--jitless | Enables running V8 in JITless mode. [More Information](https://v8.dev/blog/jitless) |
| --js-flags=--noexpose_wasm | Disables WebAssembly |
| --no-pings | Blocks hyperlink auditing pings |
| --num-raster-threads | Enforces number of worker threads used to rasterize content |
| --process-per-site | Consolidates same-site pages to share a single process |
| --site-per-process | Enforces a one-site-per-process security policy |
| --use-fake-device-for-media-stream | Spoofs microphone and camera IDs |
</p></details>

<details><summary>Enabled Features</summary><p>

Isolation:
* IsolateOrigins
* OriginIsolationHeader
* PartitionConnectionsByNetworkIsolationKey
* PartitionDomainReliabilityByNetworkIsolationKey
* PartitionExpectCTStateByNetworkIsolationKey
* PartitionHttpServerPropertiesByNetworkIsolationKey
* PartitionNelAndReportingByNetworkIsolationKey
* PartitionSSLSessionsByNetworkIsolationKey
* PartitionedCookies
* SplitAuthCacheByNetworkIsolationKey
* SplitCacheByIncludeCredentials
* SplitCacheByNetworkIsolationKey
* SplitHostCacheByNetworkIsolationKey
* StrictOriginIsolation
* UseRegistrableDomainInNetworkIsolationKey
* WebAppEnableIsolatedStorage
	* Enables web apps to request isolated storage
	
Sandboxing:
* BrowserDynamicCodeDisabled
	* Disables dynamic code using ACG. Prevents the browser process from generating dynamic code or modifying executable code.
* EnableCsrssLockdown
* GpuAppContainer
* NetworkServiceCodeIntegrity
	* Enables CIG in the network process
* NetworkServiceSandbox
* SandboxExternalProtocolBlocked
* WinSboxDisableExtensionPoint
* WinSboxDisableKtmComponent

Privacy & Security:
* AutoupgradeMixedContent
	* Disabling it and forcing `--enable-strict-mixed-content-checking` will block all mixed content
* BlockInsecurePrivateNetworkRequests, BlockInsecurePrivateNetworkRequestsForNavigations
	* Blocks insecure private network requests
* ClearCrossSiteCrossBrowsingContextGroupWindowName
* CriticalClientHint
* ComputePressure
	*  We should keep it disabled, because giving websites access to device compute performance data might increase the risk of harming the user's privacy
* EncryptedClientHello
* GreaseUACH, UserAgentClientHint
	* Blocks Sec-CH-UA headers
* ImprovedCookieControls
	* Improved third-party cookie blocking/control
* LangClientHintHeader
	* Blocks handling of accept-language via client hints
* LegacyTLSEnforced
	* Enforce deprecation of legacy TLS versions
* PrefersColorSchemeClientHintHeader
	* Disabled blocks Dark mode detection via client hints
* ReduceUserAgent
	* The (edge://)flag version isn't available on Edge
* PrefetchPrivacyChanges
	* Prefetch requests will not follow redirects, not send a Referer header, not send credentials for cross-origin requests, and do not pass through service workers
* ReducedReferrerGranularity
	* Enables strict-origin-when-cross-origin
* ViewportHeightClientHintHeader

Performance:
* AudioWorkletThreadRealtimePriority
* MinimizeAudioProcessingForUnusedOutput
	* Reduces CPU load when all audio tracks are disabled
</p></details>

<details><summary>Disabled Features</summary><p>

Reporting:
* AppActivityReporting
* ConversionMeasurement
* CrashReporting
* CrossOriginOpenerPolicyAccessReporting
* CrossOriginOpenerPolicyReporting
* CrossOriginOpenerPolicyReportingOriginTrial
* CrostiniAdditionalEnterpriseReporting
* DocumentReporting
* EnableStructuredMetrics
* EnterpriseRealtimeExtensionRequest
* EventBasedStatusReporting
* ExpectCTReporting
* ReportAllJavaScriptFrameworks
* Reporting
* TabMetricsLogging

Autofill:
* AutofillEnableAccountWalletStorage
* AutofillServerCommunication

FloC:
* FederatedLearningOfCohorts
* FlocIdComputedEventLogging
* InterestCohortAPIOriginTrial
* InterestCohortFeaturePolicy

SXG:
* EnableSignedExchangePrefetchCacheForNavigations
* EnableSignedExchangeSubresourcePrefetch
* SignedExchangeReportingForDistributors

WebBundles:
* EnableSubresourceWebBundles
* SubresourceWebBundles

Others:
* DirectSockets
	* Blocks Direct Sockets API
* ExperimentalJSProfiler
* HandwritingRecognitionWebPlatformApiFinch
	* HandwritingRecognition API
* IdleDetection
	* Blocks Idle Detection
* MediaDrmPreprovisioning
	* Blocks DRM (Might break Netflix and Spotify)
* NetworkTimeServiceQuerying
	* Disables network time queries in order to prevent Chromium connecting to `clients2.google.com`
* NotificationTriggers
* PasswordCheck
	* We don't need Google checking our passwords
* SafeBrowsingEnhancedProtection
	* Blocks Safe Browsing
* TextFragmentAnchor, CopyLinkToText
	* Disables text snippets in URL fragments
* WebNFC, WebXR
	* Blocks NFC and XR APIs
* WinrtGeolocationImplementation
	* Blocks Geolocation, you might need to enable it if you are going to use Maps
* WinrtSensorsImplementation
	* Blocks Sensors implementation
</p></details>

<details><summary>URL</summary><p>

| Name | Description |
| :--- | :---------- |
| --connectivity-check-url | Used for Network connectivity checking |
| --crash-server-url| Crash server |
| --gaia-url | GAIA related |
| --gcm-checkin-url | Used for Cloud Messaging |
| --gcm-mcs-endpoint | Used for Cloud Messaging |
| --gcm-registration-url | Used for Cloud Messaging |
| --google-apis-url | GAIA related |
| --google-base-url | GAIA related |
| --google-doodle-url | GAIA related |
| --lso-url | GAIA related |
| --oauth-account-manager-url | GAIA related |
| --override-metrics-upload-url | Metrics upload |
| --realtime-reporting-url | Realtime reporting |
| --sync-url | Used for sync |
| --url | Used for crash reports |
| --variations-server-url | Reports variation data |
</p></details>

<details><summary>Blink</summary><p>

| Name | Description |
| :--- | :---------- |
| --blink-settings | Sets Blink settings |
| --disable-blink-features | Disables selected Blink features |

blink-settings:
* dnsPrefetchingEnabled = false
	* Disables DNS prefetching
* preferredColorScheme = 1
	* Prevents Dark Mode detection if `#disallow-doc-written-script-loads` is disabled/default
* strictMixedContentChecking, strictMixedContentCheckingForPlugin, strictlyBlockBlockableMixedContent = true
	* Strictly blocks mixed contents

disable-blink-features:
* PrefersContrast
* GravitySensor
</p></details>


## Workaround

Remove these lines to fix extensions issues on Ungoogled Chromium
> --extension-content-verification=enforce_strict
> --extensions-install-verification=enforce

#### WebGL

If WebGL is necessary, you can disable WebGL2 instead of disabling the whole "WebGL system" 
> --disable-webgl2

#### WebAssembly

Some websites may require WebAssembly to work (Figma, for example)

Remove `--noexpose_wasm` from `--js-flags`

#### Cannot access any website on Linux

Remove `NetworkServiceSandbox` from `--enable-featues`

#### Slower JavaScript performance

Using JITless mode improves security, but might reduce V8’s performance [More Information](https://v8.dev/blog/jitless).

For some reason, ProtonMail doesn't work in JTLess mode

Remove `--jitless` from `--js-flags`

#### Devtools, captchas and third-party frames not working

Remove `--isolation-by-default`

### Mega.nz

Remove `0x002f` from `--cipher-suite-blacklist`

## Not recommended

> --component-updater=url-source="0.0.0.0"

I do not recommend to use it, because it is needed for up-to-date components (chrome://components), like native adblocker rules. However, browser still can be usable if your goal is to reduce internet traffics.
