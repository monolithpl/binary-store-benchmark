# binary store benchmark
Benchmarking various tools for storing binary data files in the browser [Local Storage & JavaScript]

### why?
Suppose you want to store some audio or video in the browser for offline use in a [Progressive Web App](https://developers.google.com/web/progressive-web-apps/). You need to figure out some [binary to text encoding](https://en.wikipedia.org/wiki/Binary-to-text_encoding), since JavaScript storage is text.  The standard for storing binary blobs as text is Base64, which was maybe OK-ish for ASCII text in the 1980s. Since JavaScript uses UTF16 internally, it opens up the field for dramatic space savings, which is critical in mobile.  

### how?
* https://github.com/qntm/base32768
* https://github.com/simonratner/base32k
* https://github.com/pieroxy/lz-string
* https://en.wikipedia.org/wiki/Binary-to-text_encoding
