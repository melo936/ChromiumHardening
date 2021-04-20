## Command Line

```
--block-new-web-contents --disable-background-networking --disable-breakpad --disable-crash-reporter --disable-default-apps --disable-domain-reliability --disable-notifications --disable-webgl --extension-content-verification=enforce_strict --extensions-install-verification=enforce --no-pings --site-per-process --use-fake-device-for-media-stream --enable-features=AppendFrameOriginToNetworkIsolationKey,BlockInsecurePrivateNetworkRequests,BlockInsecurePrivateNetworkRequestsForNavigations,ImprovedCookieControlsIsolateOrigins,LegacyTLSEnforced,OriginIsolationHeader,PartitionConnectionsByNetworkIsolationKey,PartitionDomainReliabilityByNetworkIsolationKey,PartitionExpectCTStateByNetworkIsolationKey,PartitionHttpServerPropertiesByNetworkIsolationKey,PartitionNelAndReportingByNetworkIsolationKey,PartitionSSLSessionsByNetworkIsolationKey,PrefetchPrivacyChanges,ReducedReferrerGranularity,SplitAuthCacheByNetworkIsolationKey,SplitCacheByNetworkIsolationKey,SplitHostCacheByNetworkIsolationKey,StrictOriginIsolation,UseRegistrableDomainInNetworkIsolationKey --disable-features=AppActivityReporting,AutofillEnableAccountWalletStorage,AutofillServerCommunication,AutoupgradeMixedContent,CrashReporting,CrossOriginOpenerPolicyAccessReporting,CrossOriginOpenerPolicyReporting,CrossOriginOpenerPolicyReportingOriginTrial,CrostiniAdditionalEnterpriseReporting,DirectSockets,EnableSignedExchangePrefetchCacheForNavigations,EnableSignedExchangeSubresourcePrefetch,EnableSubresourceWebBundles,EnterpriseRealtimeExtensionRequest,EventBasedStatusReporting,ExpectCTReporting,FederatedLearningOfCohorts,FlocIdComputedEventLogging,IdleDetection,InterestCohortAPIOriginTrial,InterestCohortFeaturePolicy,LangClientHintHeader,MediaDrmPreprovisioning,NetworkTimeServiceQuerying,NotificationTriggers,PasswordCheck,Reporting,SafeBrowsingEnhancedProtection,SignedExchangeReportingForDistributors,SubresourceWebBundles,TextFragmentAnchor,UserAgentClientHint,WebNFC,WebUSB,WebXR,WinrtGeolocationImplementation,WinrtSensorsImplementation --connectivity-check-url=0.0.0.0 --crash-server-url=0.0.0.0 --gaia-url=0.0.0.0 --gcm-checkin-url=0.0.0.0 --gcm-mcs-endpoint=0.0.0.0 --gcm-registration-url=0.0.0.0 --google-apis-url=0.0.0.0 --google-base-url=0.0.0.0 --google-doodle-url=0.0.0.0 --lso-url=0.0.0.0 --oauth-account-manager-url=0.0.0.0 --override-metrics-upload-url=0.0.0.0 --realtime-reporting-url=0.0.0.0 --sync-url=0.0.0.0 --variations-server-url=0.0.0.0 --cipher-suite-blacklist=0xc013,0xc014,0x009c,0x009d,0x002f,0x0035 --enable-strict-mixed-content-checking --js-flags=--noexpose_wasm
```

Triple click to select the entire line.
 
<details><summary><b>Worth to mention</b></summary><p>

| Name | Description |
| :--- | :---------- |
| --disable-frame-rate-limit | Disables frame rate limiting |
| --enable-low-end-device-mode | Forces low-end device mode <br> It reduces memory usage a lot and also quaility of videos or images |
| --user-agent="useragent" | A string used to override the default user agent with a custom one |
| --use-mobile-user-agent | Forces mobile user agent |
</p></details>

## Documentation
<details><summary>Flags</summary><p>

| Name | Description |
| :--- | :---------- |
| --block-new-web-contents | Blocks all pop-ups |
| --cipher-suite-blacklist | Blocks lists of insecure cipher suites |
| --disable-background-networking | Blocks background networking, like Safe browsing |
| --disable-breakpad | Disables the crash reporting. |
| --disable-crash-reporter | 	Disables the crash reporting. |
| --disable-default-apps | Disables installation of default apps |
| --disable-domain-reliability | Disables Domain Reliability Monitoring |
| --disable-notifications | Disables notifications |
| --disable-webgl | Disables WebGL |
| --enable-strict-mixed-content-checking | Blocks passive and active mixed content <br> (AutoupgradeMixedContent must be disabled) |
| --extension-content-verification | Extensions verification |
| --extensions-install-verification | Extensions verification |
| --js-flags=--noexpose_wasm | Disables WebAssembly |
| --no-pings | Blocks hyperlink auditing pings |
| --site-per-process | Enforces a one-site-per-process security policy |
| --use-fake-device-for-media-stream | Spoofs microphone and camera IDs |
</p></details>

<details><summary>Enabled Features</summary><p>

Isolation:
* AppendFrameOriginToNetworkIsolationKey
* IsolateOrigins
* OriginIsolationHeader
* PartitionConnectionsByNetworkIsolationKey
* PartitionDomainReliabilityByNetworkIsolationKey
* PartitionExpectCTStateByNetworkIsolationKey
* PartitionHttpServerPropertiesByNetworkIsolationKey
* PartitionNelAndReportingByNetworkIsolationKey
* PartitionSSLSessionsByNetworkIsolationKey
* SplitAuthCacheByNetworkIsolationKey
* SplitCacheByNetworkIsolationKey
* SplitHostCacheByNetworkIsolationKey
* StrictOriginIsolation
* UseRegistrableDomainInNetworkIsolationKey

Privacy & Security:
* PrefetchPrivacyChanges 
	* Prefetch requests will not follow redirects, not send a Referer header, not send credentials for cross-origin requests, and do not pass through service workers
* ReducedReferrerGranularity
	* Enables strict-origin-when-cross-origin
* ImprovedCookieControls
	* Improved third-party cookie blocking/control
* LegacyTLSEnforced
	* Enforce deprecation of legacy TLS versions
* BlockInsecurePrivateNetworkRequests, BlockInsecurePrivateNetworkRequestsForNavigations
	* Blocks insecure private network requests
</p></details>

<details><summary>Disabled Features</summary><p>

Reporting:
* AppActivityReporting
* CrashReporting
* CrossOriginOpenerPolicyAccessReporting
* CrossOriginOpenerPolicyReporting
* CrossOriginOpenerPolicyReportingOriginTrial
* CrostiniAdditionalEnterpriseReporting
* EnterpriseRealtimeExtensionRequest
* EventBasedStatusReporting
* ExpectCTReporting
* Reporting
* SignedExchangeReportingForDistributors

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

WebBundles:
* EnableSubresourceWebBundles
* SubresourceWebBundles

Others:
* AutoupgradeMixedContent
	* Disabling it and forcing --enable-strict-mixed-content-checking will block all mixed content
* DirectSockets
	* Blocks Direct Sockets API
* IdleDetection
	* Blocks Idle Detection
* LangClientHintHeader
	* Blocks handling of accept-language via client hints
* MediaDrmPreprovisioning
	* Blocks DRM (Might break Netflix and Spotify)
* NetworkTimeServiceQuerying
	* Disables network time queries in order to prevent Chromium connecting to `clients2.google.com`
* NotificationTriggers
* PasswordCheck
	* We don't need Google checking our passwords
* SafeBrowsingEnhancedProtection
	* Blocks Safe Browsing
* TextFragmentAnchor
	* Disables text snippets in URL fragments
* UserAgentClientHint
	* Blocks Sec-CH-UA headers
* WebNFC, WebUSB, WebXR
	* Blocks NFC, USB and XR APIs
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
| --variations-server-url | Reports variation data |
</p></details>

## Workaround

Remove these lines to fix extensions issues on Ungoogled Chromium
> --extension-content-verification=enforce_strict
> --extensions-install-verification=enforce

#### WebGL

If WebGL is necessary, you can disable WebGL2 instead of disabling the whole "WebGL system" 
> --disable-webgl2

#### WebAssembly

Some websites may require WebAssembly to work (Figma, for example). In order to fix it remove this line: 
> --js-flags=--noexpose_wasm

## Not recommended

> --component-updater=url-source=0.0.0.0

I do not recommend to use it, because it is needed for up-to-date components (chrome://components). However, browser still can be usable if your goal is to reduce internet traffics.
