**Setting privacy in the browser FireFox and IceCat for [PC](https://www.gnu.org/software/gnuzilla/) / [android](https://f-droid.org/en/packages/org.gnu.icecat/)**
---
<br />

- **These settings may cause problems on some sites**  :warning:
<br />


Type in the address bar (and agree to the terms):
<pre><code>about:config</code></pre>
Search for parameters and set the following values:

- [x] Disable telemetry 

Params | Value
--------- | ------------
<code>toolkit.telemetry.archive.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.unified</code> | <code>**false**</code>
<code>toolkit.telemetry.server</code> | <code> empty value </code>
<code>toolkit.telemetry.server_owner</code> | <code> empty value </code>
<code>toolkit.telemetry.bhrPing.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.debugSlowSql</code> | <code>**false**</code>
<code>toolkit.telemetry.ecosystemtelemetry.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.firstShutdownPing.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.cachedClientID</code> | <code> empty value </code>
<code>toolkit.telemetry.hybridContent.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.newProfilePing.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.shutdownPingSender.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.shutdownPingSender.enabledFirstSession</code> | <code>**false**</code>
<code>toolkit.telemetry.shutdownPingSender.enabledFirstSes</code> | <code>**false**</code>
<code>toolkit.telemetry.updatePing.enabled</code> | <code>**false**</code>
<code>toolkit.telemetry.updatePing.enable</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.feeds.telemetry</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.fxaccounts.endpoint</code> | <code> empty value </code>
<code>browser.newtabpage.activity-stream.telemetry</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.telemetry.ping.endpoint</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.telemetry.structuredIngestion</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.telemetry.structuredIngestion.endpoint</code> | <code> empty value </code>
<code>browser.newtabpage.activity-stream.telemetry.ut.events</code> | <code>**false**</code>
<code>browser.ping-centre.telemetry</code> | <code>**false**</code>
<code>browser.urlbar.eventTelemetry.enabled</code> | <code>**false**</code>
<code>media.wmf.deblacklisting-for-telemetry-in-gpu-process</code> | <code>**false**</code>
<code>permissions.eventTelemetry.enabled</code> | <code>**false**</code>
<code>security.certerrors.recordEventTelemetry</code> | <code>**false**</code>
<code>security.identitypopup.recordEventTelemetry</code> | <code>**false**</code>
<code>security.ssl.errorReporting.url</code> | <code> empty value </code>
<code>services.sync.telemetry.maxPayloadCount</code> | <code> -1 </code>
<code>services.sync.telemetry.submissionInterval</code> | <code> -1 </code>
<code>telemetry.origin_telemetry_test_mode.enabled</code> | <code>**false**</code>
<code>gecko.handlerService.schemes.mailto.1.uriTemplate</code> | <code> empty value </code>
<code>gecko.handlerService.schemes.mailto.2.uriTemplate</code> | <code> empty value </code>
<code>gecko.handlerService.schemes.mailto.0.uriTemplate</code> | <code> empty value </code>
<code>gecko.handlerService.schemes.mailto.0.name</code> | <code> empty value </code>
<code>gecko.handlerService.schemes.mailto.1.name</code> | <code> empty value </code>
<code>datareporting.healthreport.infoURL</code> | <code> empty value </code>
<code>datareporting.healthreport.uploadEnabled</code> | <code>**false**</code>
<code>datareporting.healthreport</code> | <code>**false**</code>
<code>toolkit.telemetry.cachedClientID</code> | <code> empty value </code>
<code>services.sync.prefs.sync.media.eme.enabled</code> | <code>**false**</code>
<code>browser.search.suggest.enabled</code> | <code>**false**</code>
<code>browser.search.suggest.enabled.private</code> | <code>**false**</code>
<code>browser.search.suggest</code> | <code>**false**</code>
<code>device.camera.enabled</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.asrouter.userprefs.cfr.addons</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.asrouter.userprefs.cfr.features</code> | <code>**false**</code>
<code>dom.event.clipboardevents.enabled</code> | <code>**false**</code>
<code>dom.event.clipboardevents</code> | <code>**false**</code>
<code>dom.battery.enabled</code> | <code>**false**</code>
<code>gecko.handlerService.schemes.irc.0.uriTemplate</code> | <code> empty value </code>
<code>gecko.handlerService.schemes.ircs.0.uriTemplate</code> | <code> empty value </code>
<code>browser.contentHandlers.types.1.uri</code> | <code>**false**</code>
<code>app.feedback.baseURL</code> | <code> empty value </code>
<code>breakpad.reportURL</code> | <code> empty value </code>
<code>browser.chrome.errorReporter.infoURL</code> | <code> empty value </code>
<code>toolkit.crashreporter.infoURL </code> | <code> empty value </code>
<code>distribution.id</code> | <code> empty value </code>
<code>extensions.abuseReport.amoDetailsURL</code> | <code> empty value </code>
<code>extensions.abuseReport.url</code> | <code> empty value </code>
<code>geo.provider.network.url</code> | <code> empty value </code>
<code>toolkit.datacollection.infoURL</code> | <code> empty value </code>
<code>browser.contentblocking.report.cookie.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.endpoint_url</code> | <code> empty value </code>
<code>browser.contentblocking.report.fingerprinter.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.lockwise.how_it_works.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.lockwise.mobile-android.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.lockwise.mobile-ios.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.manage_devices.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.mobile-android.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.mobile-ios.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.monitor.enabled</code> | <code>**false**</code>
<code>browser.contentblocking.report.monitor.home_page_url</code> | <code> empty value </code>
<code>browser.contentblocking.report.monitor.how_it_works.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.monitor.preferences_url</code> | <code> empty value </code>
<code>browser.contentblocking.report.monitor.sign_in_url</code> | <code> empty value </code>
<code>browser.contentblocking.report.monitor.url</code> | <code> empty value </code>
<code>browser.contentblocking.report.proxy_extension.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.show_mobile_app</code> | <code>**false**</code>
<code>browser.contentblocking.report.social.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.tracker.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.vpn-android.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.vpn-ios.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.vpn-promo.url</code> | <code>empty value</code>
<code>browser.contentblocking.report.vpn.enabled</code> | <code>**false**</code>
<code>browser.contentblocking.report.vpn.url</code> | <code>empty value</code>
<code>browser.contentblocking.reportBreakage.url</code> | <code>empty value</code>
<code>browser.newtabpage.activity-stream.discoverystream.endpointSpocsClear</code> | <code>empty value</code>
<code>browser.newtabpage.activity-stream.discoverystream.endpoints</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.advisoryURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.gethashURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.reportMalwareMistakeURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.reportPhishMistakeURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.reportURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google.updateURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.advisoryName</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.advisoryURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.dataSharingURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.gethashURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.reportMalwareMistakeURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.reportPhishMistakeURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.reportURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.google4.updateURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.mozilla.gethashURL</code> | <code>empty value</code>
<code>browser.safebrowsing.provider.mozilla.updateURL</code> | <code>empty value</code>
<code>browser.safebrowsing.reportPhishURL</code> | <code>empty value</code>
<code>datareporting.policy.firstRunURL</code> | <code>empty value</code>
<code>identity.fxaccounts.auth.uri</code> | <code>empty value</code>
<code>identity.fxaccounts.commands.enabled</code> | <code>**false**</code>
<code>identity.fxaccounts.enabled</code> | <code>**false**</code>
<code>identity.fxaccounts.pairing.enabled</code> | <code>**false**</code>
<code>identity.fxaccounts.remote.oauth.uri</code> | <code> empty value </code>
<code>identity.fxaccounts.remote.pairing.uri</code> | <code> empty value </code>
<code>identity.fxaccounts.remote.profile.uri</code> | <code> empty value </code>
<code>identity.fxaccounts.remote.root</code> | <code> empty value </code>
<code>identity.fxaccounts.service.monitorLoginUrl</code> | <code> empty value </code>
<code>identity.mobilepromo.android</code> | <code> empty value </code>
<code>identity.fxaccounts.toolbar.enabled</code> | <code>**false**</code>
<code>identity.fxaccounts.useSessionTokensForOAuth</code> | <code>**false**</code>
<code>identity.mobilepromo.ios</code> | <code> empty value </code>
<code>identity.sendtabpromo.url</code> | <code> empty value </code>
<code>identity.sync.tokenserver.uri</code> | <code> empty value </code>
<code>identity.sync.useOAuthForSyncToken</code> | <code> empty value </code>


- [x] Disable WebRTC

Params | Value
--------- | ---------
<code>media.peerconnection.enabled</code> | <code>**false**</code>
<code>media.navigator.enabled</code> | <code>**false**</code>
<code>media.peerconnection.enabled</code> | <code>**false**</code>

- [x] Disable WebGL

Params | Value
--------- | ---------
<code>webgl.disabled</code> | <code>**true**
<code>webgl.enable-webgl2</code> | <code>**false**</code>
  
- [x] [Enable DNS over HTTPS](https://wiki.mozilla.org/Trusted_Recursive_Resolver) ([DoH](https://tools.ietf.org/html/rfc8484))
- Another way to encrypt all dns requests on your Windows / Linux / MacOS device: [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)(Recommended as the best way)
- For more DNS resolves over HTTPS: [link](https://github.com/curl/curl/wiki/DNS-over-HTTPS) | [link](https://dnscrypt.info/public-servers/)

Params | Value
--------- | ---------
<code>network.trr.mode</code> | <code>**3**</code>
<code>network.trr.uri</code> | <code>https://cloudflare-dns.com/dns-query</code>

- After defining all parameters, check your browser add-on settings

- [x] [Test DNSSEC](https://dnssec.vs.uni-due.de/)
- [x] [Test DNS over HTTPS Cloudflare](https://www.cloudflare.com/en-gb/ssl/encrypted-sni/) (_if cloudflare is selected_)
- [x] Install add-on [CanvasBlocker](https://github.com/kkapsner/CanvasBlocker) for [FireFox](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/):
- It is recommended to change 'userAgent' => 'Protect navigator API' settings
- Check the config in 'Settings' => 'Setting sanitation'
- [x] Install add-on [uBlock](https://github.com/gorhill/uBlock/) for [FireFox](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/):
- Select multiple regions to block ads
- [x] [Test](https://browserleaks.com/) | [test](https://pixelscan.net/) your Browser

- [x] Use [DuckDuckGo](https://duckduckgo.com/) or [SearX](https://searx.github.io/searx/) as your browser's search engine

- Set auto-delete history in browser settings: this will slow down the speed of the browser, but increase your privacy on the network

- Many settings do not affect your privacy, but they can potentially get to third parties.
Therefore, if you, for example, want to report an add-on error in your browser, then contact the developer directly and report it.

