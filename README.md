**Setting privacy in the browser FireFox and IceCat for [PC](https://www.gnu.org/software/gnuzilla/) / [android](https://f-droid.org/en/packages/org.gnu.icecat/)**

- These settings may cause problems on some sites:exclamation:

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
