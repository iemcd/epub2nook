# epub2nook

epub2nook is a bash script that optimizes all the epub files in the current directory for display on a Nook Simple Touch Reader from Barnes & Noble. It does this mostly by shrinking large images that are larger than the screen and constraining their palettes to 16 greyscale colors. The major benefit of this is that the files may take up much less of the device's limited disk space. It's a work in progress.

The name is slightly wrong, becuase the output is also an epub file. Currently it avoids overwriting the original by appending "nook" to the end before the extension, but this may change.

The tool currently requires **imagemagick**, **zip**, and **sed**.

For an unscientific sample of epubs that I own or have downloaded, I see about a 50% reduction in size.

See [the wiki](https://github.com/iemcd/epub2nook/wiki) for more information.
