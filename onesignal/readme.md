# Aanpassingen aan OneSignal

## Lokaal hosten van SDK

Om Adblocking te vermijden, wordt alles lokaal gehost.
Zie https://github.com/OneSignal/OneSignal-Website-SDK/wiki/Self-Hosting-the-JavaScript-Web-SDK

Korte samenvatting:

- OneSignalPageSDKES6.js
- OneSignalSDK.js
- OneSignalRealSDKWorker.js

Downloaden van CDN

Vervolgens alle verwijzingen naar de cdn eruitvissen

## Merge van service workers

Voor de PWA moet de andere serviceworker ook geactiveerd worden.
Dit kan door dit toe te voegen in

- OneSignalSDKWorker.js
- oneSignalSDKUpdateWorker.js

Configuratie van PWA service worker: uit https://www.pwabuilder.com
