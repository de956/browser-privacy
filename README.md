**Setting privacy in the browser FireFox and IceCat for [PC](https://www.gnu.org/software/gnuzilla/) / [android](https://f-droid.org/en/packages/org.gnu.icecat/)**
___

:exclamation: **These settings may cause problems on some sites** :exclamation:
___

Type in the address bar (and agree to the terms):
<pre><code>about:config</code></pre>
Search for parameters and set the following values:

- [x] Disable telemetry 

Parameter | Value
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
<code>toolkit.telemetry.updatePing.enable<code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.feeds.telemetry</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.fxaccounts.endpoint</code> | <code> empty value </code>
<code>browser.newtabpage.activity-stream.telemetry</code> | <code>**false**</code>
<code>browser.newtabpage.activity-stream.telemetry.ping.endpoint | <code>**false**</code>
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
<code>datareporting.healthreport.infoURL</code> | <code> empty value </code>
<code>datareporting.healthreport.uploadEnabled</code> | <code>**false**</code>
<code>datareporting.healthreport</code> | <code>**false**</code>
<code>toolkit.telemetry.cachedClientID</code> | <code> empty value </code>
<code>services.sync.prefs.sync.media.eme.enabled</code> | <code>**false**</code>
<code>browser.search.suggest.enabled</code> | <code>**false**</code>
<code>browser.search.suggest.enabled.private</code> | <code>**false**</code>
<code>browser.search.suggest</code> | <code>**false**</code>
<code>device.camera.enabled</code> | <code>**false**</code>
    
- [x] Disable WebRTC

Parameter | Value
--------- | ---------
<code>media.peerconnection.enabled</code> | <code>**false**</code>
<code>media.navigator.enabled</code> | <code>**false**</code>
<code>media.peerconnection.enabled</code> | <code>**false**</code>

- [x] Disable WebGL

Parameter | Value
--------- | ---------
<code>webgl.disabled</code> | <code>**true**
<code>webgl.enable-webgl2</code> | <code>**false**</code>
  
- [x] [Enable DNS over HTTPS](https://wiki.mozilla.org/Trusted_Recursive_Resolver) ([DoH](https://tools.ietf.org/html/rfc8484))
- Another way to encrypt all dns requests on your Windows / Linux / MacOS device: [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)
- For more DNS resolves over HTTPS: [link](https://github.com/curl/curl/wiki/DNS-over-HTTPS) | [link](https://dnscrypt.info/public-servers/)

Parameter | Value
--------- | ---------
<code>network.trr.mode</code> | <code>**3**</code>
<code>network.trr.uri</code> | <code>https://cloudflare-dns.com/dns-query</code>

- [x] [Test DNSSEC](https://dnssec.vs.uni-due.de/)
- [x] [Test DNS over HTTPS Cloudflare](https://www.cloudflare.com/en-gb/ssl/encrypted-sni/) (_if cloudflare is selected_)
- [x] Install add-on [CanvasBlocker](https://github.com/kkapsner/CanvasBlocker) for [FireFox](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/)
- [x] Install add-on [uBlock](https://github.com/gorhill/uBlock/) for [FireFox](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/)
- [x] [Test](https://browserleaks.com/) | [test](https://pixelscan.net/) your Browser



