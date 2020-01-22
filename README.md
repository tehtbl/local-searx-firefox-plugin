
[![License](https://img.shields.io/badge/license-GPLv3-ff69b4.svg)](https://raw.githubusercontent.com/tehtbl/local-searx-firefox-plugin/master/LICENSE)


# Description

Local searx firefox search plugin.

Based on [PrivacyTools Searx](https://gitlab.com/nitrohorse/privacytools-io-search).

# How To

* start local searx docker instance:
`docker run -d --restart=always --name searx -p 8080:8888 wonderfall/searx`

* install deps: `npm i`
* build bundle: `npm run bundle`

* Run add-on in isolated Firefox instance using [web-ext](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Getting_started_with_web-ext) (open the [Browser Toolbox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) for console logging): `npm start`
