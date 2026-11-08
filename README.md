# waragor.com (bare domain)

The main site lives at www.waragor.com (Railway, repo waragor-site). GoDaddy can't point the bare
domain at Railway, so this tiny GitHub Pages site answers for plain waragor.com:

- `app-ads.txt` is served here, because Google's ad crawler checks waragor.com/app-ads.txt and ignores www.
- Every other address forwards to the same page on www.waragor.com.

Keep `app-ads.txt` identical to the one in waragor-site.
