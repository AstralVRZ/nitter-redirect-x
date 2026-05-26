# ![nitter-redirect](images/icon32.png) Nitter Redirect

[![Firefox Add-on](images/badge-amo.png)](https://addons.mozilla.org/en-US/firefox/addon/nitter-redirect/) 

A simple browser extension that redirects Twitter/X requests to [Nitter](https://github.com/zedeus/nitter) instead.

No unnecessary permissions required, only listens for and redirects requests made to `twitter.com`, `www.twitter.com`, `mobile.twitter.com`, `x.com`, `www.x.com`, `mobile.x.com`, `pbs.twimg.com` & `video.twimg.com`, nothing else.

Allows for setting custom [Nitter instances](https://github.com/zedeus/nitter/wiki/Instances) and toggling redirects on & off.

## Build

1.  `npm install --global web-ext`
2.  `web-ext build`
3.  See `web-ext-artifacts/` for outputs.

## License

Code released under [the MIT license](LICENSE.txt).
