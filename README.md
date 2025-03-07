# Dawn

This project was originally made by [Theo Browne](https://github.com/t3dotgg) and was called [Und\*ck](https://github.com/t3dotgg/unduck).

The following text was copied from the original repository

(original text begins here)

DuckDuckGo's bang redirects are too slow. Add the following URL as a custom search engine to your browser. Enables all of DuckDuckGo's bangs to work, but much faster.

```
https://unduck.link?q=%s
```

## How is it that much faster?

DuckDuckGo does their redirects server side. Their DNS is...not always great. Result is that it often takes ages.

I solved this by doing all of the work client side. Once you've went to https://unduck.link once, the JS is all cache'd and will never need to be downloaded again. Your device does the redirects, not me.

(original text ends here)

## What is Dawn?

Dawn is a simple fork of Und\*ck and is purely just for myself to have custom bangs when I use it in my browsers. This lets me get all the features of DuckDuckGo's bangs while also having bangs of my own that I can easily make by adding to the `bang.ts` file. I've also removed Theo's `!t3` bang because I just don't really like AI chat apps too much. Sorry Theo.

I literally only forked this so that I could change the `!mtgs` bang from linking to the Fandom page to the new [MTG Wiki](https://mtg.wiki/) hosted by [Scryfall](htpps://scryfall.com/).

As usual, hosting is done on Vercel. The same client cached stuff should still work.
