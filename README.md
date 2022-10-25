# My Firefox Config
## Theme
1. Create a folder in C:\Users\\`USERNAME`\AppData\Roaming\Mozilla\Firefox\Profiles\\`PROFILE` and name it "chrome"
2. Put the [userChrome.css](userChrome.css) file inside the `chrome` folder
3. Disable all theme add-ons

## Extensions
* Adblocker: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
* Dark Mode: [Dark Reader](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)

## Search Engines
1. Go to [about:preferences#search](about:preferences#search)
2. Add a new search shortcut
3. Enter `https://www.google.com/search?q=%s&pws=0` as engine URL
4. Go to `Default Search Engine` and choose this new search engine

## about:config
Hide user agent (May cause some websites to not work correctly): general.useragent.override = Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/999.99 (KHTML, like Gecko) Chrome/999.0.0.0 Safari/999.99
Hide referrer: network.http.sendRefererHeader = 0
Do not track: privacy.donottrackheader.enabled = true
Tracking protection: privacy.trackingprotection.enabled = true
Prevent IDN homograph attacks: network.IDN_show_punycode = true
Allow clipboard events: dom.event.clipboardevents.enabled = false
Hide geolocation: geo.enabled = false
Disable Pocket: extensions.pocket.enabled = false
