<p align="center"><img src="https://raw.githubusercontent.com/SeinopSys/Fur-Notify/master/screenshots/chrome/notification.png" alt="Fur-Notify Chrome Notification Screenshot" width="300px"> <img src="https://raw.githubusercontent.com/SeinopSys/Fur-Notify/master/screenshots/chrome/popup.png" alt="Fur-Notify Chrome Popup Screenshot" width="300px"></p>
<h1 align="center"><img src="https://raw.githubusercontent.com/SeinopSys/Fur-Notify/master/furnotify/img/app-48.png" alt="Fur-Notify Extension Logo" height="30px"> Fur-Notify</h1>

Keep track of your Furbooru notifications and messages in (almost) real time

<p align="center"><a href="https://chrome.google.com/webstore/detail/fur-notify/gonadpaoceeebehkpojhfoeiifgblghn"><img src="https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_340x96.png" height="60" alt="Download Fur-Notify from the Chrome Web Store"></a> <a href="https://addons.mozilla.org/en-US/firefox/addon/fur-notify"><img src="https://addons.cdn.mozilla.net/static/img/addons-buttons/AMO-button_1.png" height="60" alt="Download Fur-Notify from Firefox Add-ons"></a></p>

<p align="center"><img alt="Download Fur-Notify from the Chrome Web Store" src="https://img.shields.io/chrome-web-store/v/gonadpaoceeebehkpojhfoeiifgblghn"> <img alt="Download Fur-Notify from Firefox Add-ons" src="https://img.shields.io/amo/v/fur-notify"></p>

## How does it work?

The extension sends a request to the About page (which is the most lightweight page on the site) every `N` seconds (which can be adjusted in the options) and looks for the notification and message counters on the page.

The total amount is then displayed on the icon, and when clicked it opens a menu that looks similar to the site's top bar with the notifications and messages icons, both of which can be clicked to go to their respective pages. You should choose the domain you're normally signed in on using the options, otherwise the extension can't keep count of your notifications and messages.

If you browse the site on the domain of your choosing the extension will keep the count synced with the page contents without having to wait for the next timed update.

By default, the extension sends a notification and plays a sound when the total increases, but both the notification and its sound can be disabled if you only want the counter. The notification also disappears after a few seconds initially, but this can be changed to a longer duration or disabled entirely (by setting the timeout to 0), so only a click on the close button or one of the buttons will clear it.

## Attributions

 - Notification sound: [Stairs](https://notificationsounds.com/message-tones/stairs-567) from [NotificationSounds.com](https://notificationsounds.com)
 - Icons: [Font Awesome](https://fontawesome.com/license) v5.0.10
 - Color picker: [Spectrum](https://bgrins.github.io/spectrum/)
