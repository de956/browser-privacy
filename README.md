**Setting privacy in the browser FireFox and IceCat for [PC](https://www.gnu.org/software/gnuzilla/) / [android](https://f-droid.org/en/packages/org.gnu.icecat/)**
___

:exclamation:These settings may cause problems on some sites:exclamation:
___
Type in the address bar (and agree to the terms):
<pre><code>about:config</code></pre>
Search for parameters and set the following values:

- [x] Disable telemetry 

Parameter | Value
------------ | ------------
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
  
- [x] Disable WebRTC

Parameter | Value
--------- | ---------
<code>media.peerconnection.enabled</code> | <code>**false**</code>
  
