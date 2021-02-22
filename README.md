# FOSS-Android
List of [free and open-source](https://en.wikipedia.org/wiki/Free_and_open-source_software) alternatives to proprietary Android apps.

Feel free to [contribute](https://github.com/theel0ja/foss-android/edit/master/README.md), [fork](https://github.com/theel0ja/foss-android/fork) and star this list. :)

## Operating system

|Proprietary app|FOSS App|
|---------------|--------|
|Android|[microG fork of LineageOS](https://lineage.microg.org/) (if available), [LineageOS](https://lineageos.org/)|
|[Google Play services](https://en.wikipedia.org/wiki/Google_Play_Services)|[microG](https://microg.org/)|
|[Google Play Store](https://en.wikipedia.org/wiki/Google_Play)|[F-Droid](https://f-droid.org/en/) (FOSS apps only), [Aurora Store](https://f-droid.org/en/packages/com.dragons.aurora/) or [Yalp Store](https://f-droid.org/packages/com.github.yeriomin.yalpstore/) (free Google Play clients)|

## Must have apps

* [AdAway](https://f-droid.org/packages/org.adaway/) (requires root, I recommend adding `https://energized.pro/blu` as source) or [Blokada](https://blokada.org/) (non-root, [telegram group](https://t.me/blokadachat)) to block ads & some trackers
* [Copy to Clipboard](https://f-droid.org/en/packages/se.johanhil.clipboard/) or [Share to Clipboard](https://f-droid.org/en/packages/com.tengu.sharetoclipboard/)

## Basics

|Purpose of the app|Proprietary app|FOSS App|
|------------------|---------------|--------|
|Maps|[Google Maps](https://play.google.com/store/apps/details?id=com.google.android.apps.maps&hl=en)|[OsmAnd](https://f-droid.org/packages/net.osmand.plus/), [F-Droid Maps](https://f-droid.org/en/packages/com.github.axet.maps/) (based on [MAPS.ME](https://maps.me/))|
|Photo sync|[Google Photos](https://play.google.com/store/apps/details?id=com.google.android.apps.photos&hl=en)|[Nextcloud](https://nextcloud.com/) Instant Upload|
|Browser|[Chrome](https://play.google.com/store/apps/details?id=com.android.chrome), [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox) (has Chromecast libraries)|[Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/) (Firefox fork), [Waterfox](https://play.google.com/store/apps/details?id=org.waterfoxproject.waterfox) (Firefox fork, note that not yet available from F-Droid), Tor Browser for Android, [Bromite](https://www.bromite.org/) (Chromium fork, has Adblocking features as well)|
|Contacts Sync|[Google Contacts](https://en.wikipedia.org/wiki/Google_Contacts)|Nextcloud server with [DAVdroid](https://f-droid.org/en/packages/at.bitfire.davdroid/) ([guide](https://www.davdroid.com/tested-with/nextcloud/))|
|SMS app|[Android Messages](https://play.google.com/store/apps/details?id=com.google.android.apps.messaging&hl=en), your phone's default|[Silence](https://f-droid.org/en/packages/org.smssecure.smssecure/), [QKSMS](https://f-droid.org/packages/com.moez.QKSMS/), [Signal](https://signal.org/android/apk/) ([open source](https://github.com/signalapp/Signal-Android), proprietary apk, has Google dependencies!)|
|Keyboard|[Gboard](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin), [SwiftKey](https://play.google.com/store/apps/details?id=com.touchtype.swiftkey), your ROM's included keyboard|[Simple Keyboard](https://f-droid.org/en/packages/rkr.simplekeyboard.inputmethod/), [AnySoftKeyboard](https://anysoftkeyboard.github.io/), AOSP Keyboard (included with LineageOS)|
|Launcher||[Lawnchair](https://f-droid.org/packages/ch.deletescape.lawnchair.plah/) or [KISS Launcher](https://f-droid.org/en/packages/fr.neamar.kiss/) (very minimalistic)

## Productivity

|Purpose|Proprietary app|FOSS App|
|-------|---------------|--------|
|Cloud storage|[Google Drive](https://play.google.com/store/apps/details?id=com.google.android.apps.docs), [OneDrive](https://play.google.com/store/apps/details?id=com.microsoft.skydrive), [Dropbox](https://play.google.com/store/apps/details?id=com.dropbox.android)|[Nextcloud](https://nextcloud.com/) (selfhosted)|
|Email|[Gmail](https://play.google.com/store/apps/details?id=com.google.android.gm), your phone's default Email app|[K-9 Mail](https://f-droid.org/en/packages/com.fsck.k9/), [pEp](https://f-droid.org/packages/security.pEp/)|
|Calendar sync|[Google Calendar](https://www.google.com/calendar/about/)|[Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar)|
|Calendar client|[Google Calendar](https://play.google.com/store/apps/details?id=com.google.android.calendar)|[Simple Calendar](https://f-droid.org/packages/com.simplemobiletools.calendar/)|
|Tasks|[Wunderlist](https://play.google.com/store/apps/details?id=com.wunderkinder.wunderlistandroid), [Google Tasks](https://play.google.com/store/apps/details?id=com.google.android.apps.tasks)|[Tasks](https://f-droid.org/en/packages/org.dmfs.tasks/) (sync with Nextcloud Tasks with DAVdroid)|
|PDF Reader|[Google PDF Viewer](https://play.google.com/store/apps/details?id=com.google.android.apps.pdfviewer&hl=en_US)|[Document Viewer](https://f-droid.org/en/packages/org.sufficientlysecure.viewer/), [MuPDF](https://f-droid.org/en/packages/com.artifex.mupdf.viewer.app/)|

## Instant messaging

Note: Most IM networks do not have FOSS clients or even open API for making those. 😥

* [Telegram](https://f-droid.org/en/packages/org.telegram.messenger/) - Messaging platform, similar to WhatsApp (FOSS fork, do not use Google Play version, it has proprietary dependencies!)
* [Conversations](https://f-droid.org/en/packages/eu.siacs.conversations/) - Up-to-date, maintained and modern standards supporting XMPP client for Android
* [Signal](https://signal.org/android/apk/) ([open source](https://github.com/signalapp/Signal-Android), proprietary apk, has Google dependencies!)
* [Element](https://f-droid.org/en/packages/im.vector.app/) - Matrix client
* Facebook Messenger - [MaterialFBook](https://github.com/ZeeRooo/MaterialFBook) has messaging support!

## Social media

|Proprietary app|FOSS App/Web-based alternative client|
|---------------|-------------------------------------|
|Reddit|[Slide](https://f-droid.org/en/packages/me.ccrama.redditslide/)|
|[Twitter](https://play.google.com/store/apps/details?id=com.twitter.android)|Use [Twitter Lite](https://mobile.twitter.com/home) mobile site and add to home screen|
|[Facebook](https://play.google.com/store/apps/details?id=com.facebook.katana&hl=en)|[MaterialFBook](https://github.com/ZeeRooo/MaterialFBook) (Improved mobile site wrapper for Facebook)|
|[Instagram](https://play.google.com/store/apps/details?id=com.instagram.android)|Use [Instagram mobile site](https://www.instagram.com/) and add it to your home screen ([more info on that](https://www.androidpolice.com/2017/05/10/instagram-new-mobile-web-app-ability-upload-photos/))|

## Other

|Proprietary app|FOSS App|
|---------------|--------|
|[YouTube](https://play.google.com/store/apps/details?id=com.google.android.youtube&hl=en)|[NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) (youtube client), [YouTube Vanced](https://forum.xda-developers.com/android/apps-games/app-youtube-vanced-edition-t3758757) (proprietary, modded version of the original YouTube client, no ads, etc.)
|Google Assistant|[Just Search](https://f-droid.org/packages/co.pxhouse.sas/) (just search but works for the button (long press home button)) or Fennec F-Droid/Firefox's Assist Feature (opens url box inside the app)|

<!--

## Basics

|Purpose|Proprietary app|FOSS App|
|-------|---------------|--------|

-->

## DNS Resolvers

It's important to choose privacy respecting DNS resolver.

Few ones I recommend can be found from [my wiki](https://wiki.lelux.fi/dns/resolvers).

Use [DNS-over-TLS](https://wiki.lelux.fi/dns-over-tls/#android), DNS-over-HTTPS or DNSCrypt if possible to encrypt the connection.

You can change your DNS resolver for example in [Blokada](https://blokada.org/) or [Nebulo](https://smokescreen.app/) (DNS-over-TLS & DNS-over-HTTPS).


## Some other tips and links

* [My Firefox recommendations](https://github.com/theel0ja/firefox-recommendations/blob/master/README.md)
* [uBlock Origin recommendations](https://github.com/theel0ja/ubo-recommendations/blob/master/README.md)
* [Telegram-FOSS Offtopics](https://t.me/tfossofftop) (general discussion about Free and Open Source software)
* [Small Privacy & Security Guide for Android](https://t.me/AOSDPx/80) by [@Thespartann](https://github.com/Thespartann)
* [MicroG Support Group on Telegram](https://t.me/microGSupport) 
