## Command Line

For any Chromium browser, except MS Edge:
```
--block-new-web-contents --disable-background-networking --disable-breakpad --disable-composited-antialiasing --disable-crash-reporter --disable-default-apps --disable-domain-reliability --disable-external-intent-requests --disable-file-system --disable-webgl --extension-content-verification=enforce_strict --extensions-install-verification=enforce --gpu-rasterization-msaa-sample-count=0 --lite-video-force-override-decision --no-pings --num-raster-threads=4 --process-per-site --site-per-process --time-zone-for-testing=UTC --use-fake-device-for-media-stream --enable-features="BlockInsecurePrivateNetworkRequests,BlockInsecurePrivateNetworkRequestsForNavigations,BrowserDynamicCodeDisabled,DesktopScreenshots,DisableProcessReuse,EnableCsrssLockdown,EncryptedClientHello,ForceIsolationInfoFrameOriginToTopLevelFrame,GpuAppContainer,ImprovedCookieControls,IsolateOrigins,IsolatePrerenders,IsolateSandboxedIframes,MinimizeAudioProcessingForUnusedOutput,NetworkServiceSandbox,NetworkServiceCodeIntegrity,OpaqueResponseBlockingV01,OriginIsolationHeader,PartitionConnectionsByNetworkIsolationKey,PartitionDomainReliabilityByNetworkIsolationKey,PartitionExpectCTStateByNetworkIsolationKey,PartitionHttpServerPropertiesByNetworkIsolationKey,PartitionNelAndReportingByNetworkIsolationKey,PartitionSSLSessionsByNetworkIsolationKey,PartitionedCookies,PrefetchPrivacyChanges,ReduceUserAgent,ReducedReferrerGranularity,RendererAppContainer,RestrictGamepadAccess,SandboxExternalProtocolBlocked,SandboxHttpCache,SplitAuthCacheByNetworkIsolationKey,SplitCacheByIncludeCredentials,SplitCacheByNetworkIsolationKey,SplitHostCacheByNetworkIsolationKey,StrictOriginIsolation,SuppressDifferentOriginSubframeJSDialogs,ThirdPartyStoragePartitioning,TurnOffStreamingMediaCachingAlways,TurnOffStreamingMediaCachingOnBattery,UseRegistrableDomainInNetworkIsolationKey,WinSboxDisableExtensionPoint,WinSboxDisableKtmComponent" --disable-features="AcceptCHFrame,AdInterestGroupAPI,AllowClientHintsToThirdParty,AllowURNsInIframes,AppActivityReporting,AppDiscoveryRemoteUrlSearch,AutofillEnableAccountWalletStorage,AutofillServerCommunication,AutoupgradeMixedContent,ClearCrossSiteCrossBrowsingContextGroupWindowName,ClientHintThirdPartyDelegation,ClientHintsDPR,ClientHintsDPR_DEPRECATED,ClientHintsDeviceMemory,ClientHintsDeviceMemory_DEPRECATED,ClientHintsMetaHTTPEquivAcceptCH,ClientHintsMetaNameAcceptCH,ClientHintsResourceWidth,ClientHintsResourceWidth_DEPRECATED,ClientHintsViewportWidth,ClientHintsViewportWidth_DEPRECATED,ComputePressure,ContextMenuPerformanceInfoAndRemoteHintFetching,ConversionMeasurement,CopyLinkToText,CrashReporting,CriticalClientHint,CrossOriginOpenerPolicyAccessReporting,CrossOriginOpenerPolicyReporting,CrossOriginOpenerPolicyReportingOriginTrial,CrostiniAdditionalEnterpriseReporting,CssSelectorFragmentAnchor,DirectSockets,DocumentReporting,EnableSignedExchangePrefetchCacheForNavigations,EnableSignedExchangeSubresourcePrefetch,EnableStructuredMetrics,EnableSubresourceWebBundles,EnterpriseRealtimeExtensionRequest,EventBasedStatusReporting,ExpectCTReporting,ExperimentalJSProfiler,FedCm,Fledge,FontAccess,FontAccessPersistent,GreaseUACH,HandwritingRecognitionWebPlatformApiFinch,IdleDetection,InterestGroupStorage,LensStandalone,MediaDrmPreprovisioning,MediaEngagementBypassAutoplayPolicies,NTPArticleSuggestions,NetworkTimeServiceQuerying,NotificationTriggers,OmniboxTriggerForNoStatePrefetch,OptimizationHints,OptimizationHintsFetching,OptimizationHintsFetchingAnonymousDataConsent,OptimizationHintsFieldTrials,Parakeet,Prerender2,PrefersColorSchemeClientHintHeader,PreloadMediaEngagementData,ReportAllJavaScriptFrameworks,Reporting,SegmentationPlatform,SignedExchangeReportingForDistributors,SpeculationRulesPrefetchProxy,SubresourceWebBundles,TabMetricsLogging,TFLiteLanguageDetectionEnabled,TextFragmentAnchor,SafeBrowsingBetterTelemetryAcrossReports,UACHPlatformEnabledByDefault,UserAgentClientHint,UserAgentClientHintFullVersionList,ViewportHeightClientHintHeader,WebNFC,WebOTP,WebSQLInThirdPartyContextEnabled,WebXR,WinrtGeolocationImplementation,WinrtSensorsImplementation" --connectivity-check-url=0.0.0.0 --crash-server-url=0.0.0.0 --gaia-url=0.0.0.0 --gcm-checkin-url=0.0.0.0 --gcm-mcs-endpoint=0.0.0.0 --gcm-registration-url=0.0.0.0 --google-apis-url=0.0.0.0 --google-base-url=0.0.0.0 --google-doodle-url=0.0.0.0 --lso-url=0.0.0.0 --oauth-account-manager-url=0.0.0.0 --override-metrics-upload-url=0.0.0.0 --realtime-reporting-url=0.0.0.0 --reporting-connector-url=0.0.0.0 --sync-url=0.0.0.0 --url=0.0.0.0 --variations-server-url=0.0.0.0 --variations-insecure-server-url=0.0.0.0 --cipher-suite-blacklist="0xc013,0xc014,0x009c,0x009d,0x002f,0x0035" --enable-strict-mixed-content-checking --js-flags=--jitless --blink-settings="dnsPrefetchingEnabled=false,preferredColorScheme=1,strictMixedContentChecking=true,strictMixedContentCheckingForPlugin=true,strictlyBlockBlockableMixedContent=true" --disable-blink-features="PrefersContrast,GravitySensor" --isolation-by-default
```

For MS Edge:
```
--block-new-web-contents --disable-background-networking --disable-breakpad --disable-composited-antialiasing --disable-crash-reporter --disable-default-apps --disable-domain-reliability --disable-external-intent-requests --disable-file-system --disable-webgl --extension-content-verification=enforce_strict --extensions-install-verification=enforce --gpu-rasterization-msaa-sample-count=0 --lite-video-force-override-decision --no-pings --num-raster-threads=4 --process-per-site --site-per-process --time-zone-for-testing=UTC --use-fake-device-for-media-stream --enable-features="msDataProtection,msDataWithUrlsForceOff,msDiagnosticDataForceOff,msEndpointDlp,msIrm,msIrmv2,msMdatpWebSiteDlp,msMdatpWebSiteDlpMac,msMdatpWebSiteDlpv2,msPerformanceModeToggle,BlockInsecurePrivateNetworkRequests,BlockInsecurePrivateNetworkRequestsForNavigations,BrowserDynamicCodeDisabled,DesktopScreenshots,DisableProcessReuse,EnableCsrssLockdown,EncryptedClientHello,ForceIsolationInfoFrameOriginToTopLevelFrame,GpuAppContainer,ImprovedCookieControls,IsolateOrigins,IsolatePrerenders,IsolateSandboxedIframes,MinimizeAudioProcessingForUnusedOutput,NetworkServiceSandbox,NetworkServiceCodeIntegrity,OpaqueResponseBlockingV01,OriginIsolationHeader,PartitionConnectionsByNetworkIsolationKey,PartitionDomainReliabilityByNetworkIsolationKey,PartitionExpectCTStateByNetworkIsolationKey,PartitionHttpServerPropertiesByNetworkIsolationKey,PartitionNelAndReportingByNetworkIsolationKey,PartitionSSLSessionsByNetworkIsolationKey,PartitionedCookies,PrefetchPrivacyChanges,ReduceUserAgent,ReducedReferrerGranularity,RendererAppContainer,RestrictGamepadAccess,SandboxExternalProtocolBlocked,SandboxHttpCache,SplitAuthCacheByNetworkIsolationKey,SplitCacheByIncludeCredentials,SplitCacheByNetworkIsolationKey,SplitHostCacheByNetworkIsolationKey,StrictOriginIsolation,SuppressDifferentOriginSubframeJSDialogs,ThirdPartyStoragePartitioning,TurnOffStreamingMediaCachingAlways,TurnOffStreamingMediaCachingOnBattery,UseRegistrableDomainInNetworkIsolationKey,WinSboxDisableExtensionPoint,WinSboxDisableKtmComponent" --disable-features="SendBingSERPTelemetry,SendBingTelemetry,msEdge3PTelemetry,msEdgeCitations,msEdgeFeedbackSupport,msEdgeHJSendBeaconTelemetry,msEdgeHJTelemetry,msEdgeMathHelper,msEdgeQBox,msEdgeSanTelemetry,msEnableMATSTelemetry,msEnableWAMMATSTelemetry,msODSPTelemetry,msOfficeTelemetryBase,msReadAloud,msSendDataDiagnosticTelemetry,msUseSETTelemetryService,AcceptCHFrame,AdInterestGroupAPI,AllowClientHintsToThirdParty,AllowURNsInIframes,AppActivityReporting,AppDiscoveryRemoteUrlSearch,AutofillEnableAccountWalletStorage,AutofillServerCommunication,AutoupgradeMixedContent,ClearCrossSiteCrossBrowsingContextGroupWindowName,ClientHintThirdPartyDelegation,ClientHintsDPR,ClientHintsDPR_DEPRECATED,ClientHintsDeviceMemory,ClientHintsDeviceMemory_DEPRECATED,ClientHintsMetaHTTPEquivAcceptCH,ClientHintsMetaNameAcceptCH,ClientHintsResourceWidth,ClientHintsResourceWidth_DEPRECATED,ClientHintsViewportWidth,ClientHintsViewportWidth_DEPRECATED,ComputePressure,ContextMenuPerformanceInfoAndRemoteHintFetching,ConversionMeasurement,CopyLinkToText,CrashReporting,CriticalClientHint,CrossOriginOpenerPolicyAccessReporting,CrossOriginOpenerPolicyReporting,CrossOriginOpenerPolicyReportingOriginTrial,CrostiniAdditionalEnterpriseReporting,CssSelectorFragmentAnchor,DirectSockets,DocumentReporting,EnableSignedExchangePrefetchCacheForNavigations,EnableSignedExchangeSubresourcePrefetch,EnableStructuredMetrics,EnableSubresourceWebBundles,EnterpriseRealtimeExtensionRequest,EventBasedStatusReporting,ExpectCTReporting,ExperimentalJSProfiler,FedCm,Fledge,FontAccess,FontAccessPersistent,GreaseUACH,HandwritingRecognitionWebPlatformApiFinch,IdleDetection,InterestGroupStorage,LensStandalone,MediaDrmPreprovisioning,MediaEngagementBypassAutoplayPolicies,NTPArticleSuggestions,NetworkTimeServiceQuerying,NotificationTriggers,OmniboxTriggerForNoStatePrefetch,OptimizationHints,OptimizationHintsFetching,OptimizationHintsFetchingAnonymousDataConsent,OptimizationHintsFieldTrials,Parakeet,Prerender2,PrefersColorSchemeClientHintHeader,PreloadMediaEngagementData,ReportAllJavaScriptFrameworks,Reporting,SegmentationPlatform,SignedExchangeReportingForDistributors,SpeculationRulesPrefetchProxy,SubresourceWebBundles,TabMetricsLogging,TFLiteLanguageDetectionEnabled,TextFragmentAnchor,SafeBrowsingBetterTelemetryAcrossReports,UACHPlatformEnabledByDefault,UserAgentClientHint,UserAgentClientHintFullVersionList,ViewportHeightClientHintHeader,WebNFC,WebOTP,WebSQLInThirdPartyContextEnabled,WebXR,WinrtGeolocationImplementation,WinrtSensorsImplementation" --connectivity-check-url=0.0.0.0 --crash-server-url=0.0.0.0 --gaia-url=0.0.0.0 --gcm-checkin-url=0.0.0.0 --gcm-mcs-endpoint=0.0.0.0 --gcm-registration-url=0.0.0.0 --google-apis-url=0.0.0.0 --google-base-url=0.0.0.0 --google-doodle-url=0.0.0.0 --lso-url=0.0.0.0 --oauth-account-manager-url=0.0.0.0 --override-metrics-upload-url=0.0.0.0 --realtime-reporting-url=0.0.0.0 --reporting-connector-url=0.0.0.0 --sync-url=0.0.0.0 --url=0.0.0.0 --variations-server-url=0.0.0.0 --variations-insecure-server-url=0.0.0.0 --bing-base-url=0.0.0.0 --edge-mobile-upsell-service-url=0.0.0.0 --edge-wns-push-server-url=0.0.0.0 --state-label-predictor-model-url=0.0.0.0 --cipher-suite-blacklist="0xc013,0xc014,0x009c,0x009d,0x002f,0x0035" --enable-strict-mixed-content-checking --js-flags=--jitless --blink-settings="dnsPrefetchingEnabled=false,preferredColorScheme=1,strictMixedContentChecking=true,strictMixedContentCheckingForPlugin=true,strictlyBlockBlockableMixedContent=true" --disable-blink-features="PrefersContrast,GravitySensor" --isolation-by-default
```

Triple click to select the entire line.
 
<details><summary><b>Worth to mention</b></summary><p>

| Name | Description |
| :--- | :---------- |
| --disable-frame-rate-limit | Disables frame rate limiting |
| --enable-low-end-device-mode | Clears MemoryCache when a tab becomes inactive and uses 16-bit color format for images. Not recommended on Android if strict isolation is enabled and it may not work if hardware acceleration is disabled |
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
| --disable-file-system | Disables FileSystem API |
| --disable-webgl | Disables WebGL |
| --enable-strict-mixed-content-checking | Blocks passive and active mixed content <br> (AutoupgradeMixedContent must be disabled) |
| --extension-content-verification | Extensions verification |
| --extensions-install-verification | Extensions verification |
| --gpu-rasterization-msaa-sample-count | Numbers of multisample antialiasing samples for GPU rasterization <br> are based on DPI for desktops <br> Android uses 4 by default. Using 0 disables MSAA and improves performance |
| --isolation-by-default | Change several web APIs that make it difficult to isolate origins into distinct processes |
| --js-flags=--jitless | Running V8 in JITless mode enables ACG and CET mitigations in the renderer process, disables WebAssembly and [more](https://v8.dev/blog/jitless). |
| --no-pings | Blocks hyperlink auditing pings |
| --num-raster-threads | Enforces number of worker threads used to rasterize content |
| --process-per-site | Consolidates same-site pages to share a single process |
| --site-per-process | Enforces a one-site-per-process security policy |
| --time-zone-for-testing | Spoofs timzeone |
| --use-fake-device-for-media-stream | Spoofs microphone and camera IDs |
</p></details>

<details><summary>Enabled Features</summary><p>

Partitioning:
* ForceIsolationInfoFrameOriginToTopLevelFrame
* IsolateOrigins
* IsolatePrerenders
* IsolateSandboxedIframes
* OriginIsolationHeader
* PartitionConnectionsByNetworkIsolationKey
* PartitionDomainReliabilityByNetworkIsolationKey
* PartitionExpectCTStateByNetworkIsolationKey
* PartitionHttpServerPropertiesByNetworkIsolationKey
* PartitionNelAndReportingByNetworkIsolationKey
* PartitionSSLSessionsByNetworkIsolationKey
* PartitionedCookies
* SandboxHttpCache
* SplitAuthCacheByNetworkIsolationKey
* SplitCacheByIncludeCredentials
* SplitCacheByNetworkIsolationKey
* SplitHostCacheByNetworkIsolationKey
* StrictOriginIsolation
* UseRegistrableDomainInNetworkIsolationKey

	
Sandboxing:
* BrowserDynamicCodeDisabled
	* Prevents the browser process from generating dynamic code or modifying executable code using ACG
* EnableCsrssLockdown
* GpuAppContainer
* NetworkServiceCodeIntegrity
	* Enables CIG mitigation in the network process
* NetworkServiceSandbox
	* Enables ACG mitigation in the network process
* RendererAppContainer
* SandboxExternalProtocolBlocked
* WinSboxDisableExtensionPoint
* WinSboxDisableKtmComponent

Privacy & Security:
* AutoupgradeMixedContent
	* Disabling it and forcing `--enable-strict-mixed-content-checking` will block all mixed content
* BlockInsecurePrivateNetworkRequests, BlockInsecurePrivateNetworkRequestsForNavigations
	* Blocks insecure private network requests
* ClearCrossSiteCrossBrowsingContextGroupWindowName
* DisableProcessReuse, ReduceUserAgent
	* The (edge://)flags version are not available on Edge
* EncryptedClientHello
* ImprovedCookieControls
	* Improved third-party cookie blocking/control
* OpaqueResponseBlockingV01
	* [Documentation](https://docs.google.com/document/d/1qUbE2ySi6av3arUEw5DNdFJIKKBbWGRGsXz_ew3S7HQ)
* PrefetchPrivacyChanges
	* Prefetch requests will not follow redirects, not send a Referer header, not send credentials for cross-origin requests, and do not pass through service workers
* ReducedReferrerGranularity
	* Enables strict-origin-when-cross-origin

Others:
* DesktopScreenshots
* RestrictGamepadAccess
* SuppressDifferentOriginSubframeJSDialogs
	* Disallows window.{alert, prompt, confirm} if triggered inside a subframe that is not same origin with the main frame
* TurnOffStreamingMediaCachingAlways, TurnOffStreamingMediaCachingOnBattery
</p></details>

<details><summary>Disabled Features</summary><p>

Reporting:
* AppActivityReporting
* AppDiscoveryRemoteUrlSearch
* ComputePressure
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
* SafeBrowsingBetterTelemetryAcrossReports
* TabMetricsLogging

Autofill:
* AutofillEnableAccountWalletStorage
* AutofillServerCommunication

PrivacySandbox/FloC Related:
* AdInterestGroupAPI
* AllowURNsInIframes
* FedCm
* Fledge
* InterestGroupStorage
* Parakeet

SXG:
* EnableSignedExchangePrefetchCacheForNavigations
* EnableSignedExchangeSubresourcePrefetch
* SignedExchangeReportingForDistributors

WebBundles:
* EnableSubresourceWebBundles
* SubresourceWebBundles

ClientHints:
* AcceptCHFrame
* AllowClientHintsToThirdParty
* ClientHintThirdPartyDelegation
* ClientHintsDPR
* ClientHintsDPR_DEPRECATED
* ClientHintsDeviceMemory
* ClientHintsDeviceMemory_DEPRECATED
* ClientHintsMetaHTTPEquivAcceptCH
* ClientHintsMetaNameAcceptCH
* ClientHintsResourceWidth
* ClientHintsResourceWidth_DEPRECATED
* ClientHintsViewportWidth
* ClientHintsViewportWidth_DEPRECATED
* CriticalClientHint
* GreaseUACH
* PrefersColorSchemeClientHintHeader
	* Disabled blocks Dark mode detection via client hints
* UACHPlatformEnabledByDefault
* UserAgentClientHint
* UserAgentClientHintFullVersionList
* ViewportHeightClientHintHeader

Optimization Hints:
* OptimizationHints
* OptimizationHintsFieldTrials
* OptimizationHintsFetching
* OptimizationHintsFetchingAnonymousDataConsent
* ContextMenuPerformanceInfoAndRemoteHintFetching
* NavigationPredictor

Others:
* CssSelectorFragmentAnchor
* DirectSockets
	* Blocks Direct Sockets API
* ExperimentalJSProfiler
* FontAccess, FontAccessPersistent
* HandwritingRecognitionWebPlatformApiFinch
	* HandwritingRecognition API
* IdleDetection
	* Blocks Idle Detection
* LensStandalone
* MediaDrmPreprovisioning
	* Blocks DRM (Might break Netflix and Spotify)
* NTPArticleSuggestions
* NetworkTimeServiceQuerying
	* Disables network time queries in order to prevent Chromium connecting to `clients2.google.com`
* NotificationTriggers
* OmniboxTriggerForNoStatePrefetch
* PreloadMediaEngagementData, MediaEngagementBypassAutoplayPolicies
* Prerender2
* SegmentationPlatform
* SpeculationRulesPrefetchProxy
* TFLiteLanguageDetectionEnabled
* TextFragmentAnchor, CopyLinkToText
	* Disables text snippets in URL fragments
* WebNFC, WebOTP, WebXR
	* Blocks NFC, OTP and XR APIs
* WebSQLInThirdPartyContextEnabled
* WinrtGeolocationImplementation
	* Blocks Geolocation, you might need to enable it if you are going to use Maps
* WinrtSensorsImplementation
	* Blocks Sensors implementation
</p></details>

<details><summary>MS Edge specific feature flags</summary><p>

As Microsoft Edge isn't an open-source browser, there is no way to look up for `blink::features` or other types of flags. Fortunetaly, we can search memory strings, which exposes lots of undocumented flags, but using them might be dangerous and at the same time beneficial.

Enabled:
* msDataProtection, msEndpointDlp, msMdatpWebSiteDlp, msMdatpWebSiteDlpv2, msMdatpWebSiteDlpMac, msIrm, msIrmv2
	* Feature Flags for Data Loss Prevention `edge://edge-dlp-internals/`
* msDataWithUrlsForceOff, msDiagnosticDataForceOff
	* Enabling them forces Edge to not send diagnostic data
* msPerformanceModeToggle
	* Exposes [`Turn on efficiency mode`](https://techcommunity.microsoft.com/t5/discussions/introducing-performance-mode-in-microsoft-edge-new-feature/td-p/2270856) in `edge://settings/system` and don't forget to enable it

Disabled:
* SendBingSERPTelemetry, SendBingTelemetry, msEdge3PTelemetry, msEdgeHJSendBeaconTelemetry, msEdgeHJTelemetry, msEdgeSanTelemetry, msEnableMATSTelemetry, msEnableWAMMATSTelemetry, msODSPTelemetry, msOfficeTelemetryBase, msSendDataDiagnosticTelemetry, msUseSETTelemetryService
	* Undocumented telemetry features
* msEdgeCitations
	* Disables Citations
* msEdgeFeedbackSupport
* msEdgeMathHelper
	* Disables Math Helper
* msEdgeQBox
	* Bing Related
* msReadAloud
	* Disables Read aloud
</p></details>

<details><summary>URL</summary><p>

| Name | Description |
| :--- | :---------- |
| --component-updater=url-source | Downloads additional components |
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
| --reporting-connector-url | Used for Reporting service |
| --sync-url | Used for sync |
| --url | Used for crash reports |
| --variations-insecure-server-url | Reports variation data |
| --variations-server-url | Reports variation data |

MS Edge specific URLs:
| Name | Description |
| :--- | :---------- |
| --bing-base-url | Bing related, similar to `google-base-url` |
| --edge-mobile-upsell-service-url | Unknown |
| --edge-wns-push-server-url | Windows Push Notification service |
| --state-label-predictor-model-url | Autofill |
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

#### Cannot access any website on Linux & Vivaldi doesn't run & localhost is unreachable

Remove `NetworkServiceSandbox` from `--enable-featues`

#### Slower JavaScript performance & WebAssembly not working

Using JITless mode improves security but might reduce V8’s performance [More Information](https://v8.dev/blog/jitless).

ProtonMail doesn't work in JTLess mode

Remove `--js-flags=--jitless`

#### DevTools, captchas and other third-party frames not working

Remove `--isolation-by-default`

#### Mega.nz

Remove `0x002f` from `--cipher-suite-blacklist`

#### Microphone and camera do not work

Remove `--use-fake-device-for-media-stream`

#### RESULT_CODE_MISSING_DATA

This problem usually appears on older Windows builds

Remove `RendererAppContainer` from `--enable-features`

## Not recommended

> --component-updater=url-source="0.0.0.0"

Not recommend to use it, because it completely disables components updating (chrome://components), like CRLSets, SafetyTips, native adblocker rules (it does not affect regular extensions), etc. However, the browser still can be usable if your goal is to reduce internet traffics.
