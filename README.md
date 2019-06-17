
# Volothamp's Comeuppance Baldur's Guide
## Markdown and EPUB conversions

With the announcement of Baldur's Gate III, I've seen a resurgence of interest in the two classics. Many people have never finished or even 
played these fantastic games. Indeed, I have played them when they were
released at the end of the nineties, and have never finished them myself.

And so I began reading [Volothamp's Comeuppance guide](http://www.pocketplane.net/volothamp/bgguide.htm),
which many people on the [/r/baldursgate](https://www.reddit.com/r/baldursgate/) subreddit recommended and is described in its sidebar as
"Very useful, thorough, and great for beginners." After starting the guide,
I can only agree.

However, I found a desire to bring this guide with me and be able to read
it anywhere. The world has changed dramatically, after all, and has become
much more mobile. The guide's site, having been written some time ago, is
not very mobile-friendly, though. And so I set out to convert it to epub format.

## Conversion

Both conversions have had some manual fixes applied afterwards, but are still
far from perfect.

- `volothamps-comeuppance.html`: Copy/pasted and trimmed HTML from the guide's
  website. This was used to manually create the `volothamps-comeuppance.md`
- `volothamps-comeuppance.md`: Markdown file that was manually created by
  search-and-replacing relevant HTML tags and dismissing others
- `volothamps-comeuppance-with-img.md` Markdown file that was created by the
  conversion [demo site](https://domchristie.github.io/turndown/) for "Turndown"
  [(GitHub)](https://github.com/domchristie/turndown). This version includes
  the images, which may not always produce the best results in the epub format

Both Markdown files have been converted to EPUB format using `pandoc`
[(GitHub)](https://github.com/jgm/pandoc).

## Status

There are still many issues with this first version and many tables will not
show correctly. Furthermore, no images where converted yet.

## Contribution

If you want to correct a problem, that would be great! Create an issue or a
merge request and I will update the guide.

## Credits

All credits go to the original creator of the guide, Six of Spades (?).
