# histPsychol
An Online History of Psychology Textbook

**Update** 

I still have all the motivations that follow in the sections below, but now I am using this material as the basis for a course in the Arts First initiative at the University of Waterloo. I am organizing my effort to teach writing and communication around the history of psychology generally, but with the specific tool of contributing sections to this book. The first effort at this is Fall 2018. Hopefully, the book will get a bit more populated with content, but more importantly I may gain some useful insight in how to teach the learning of content by creating content. Stay Tuned.


# The original motivation for this repo

I have become disappointed with the history of psychology textbooks we offer to undergraduates. First, they are way too expensive. Second, they are too limited. The internet and places such as [archive.org](http://archive.org) have made a wealth of material available at the click of a button. Rather than reading a textbook as an isolated experience, it ought to be possible to integrate that reading with the consultation of original material.

The purpose of this repo is to host what are a bunch of files transitioning from notes I used in my lectures to what I would like to become an online textbook.

For now the material is hosted here in its raw form, and it is built into useful documents on [readthedocs](http://history-of-psychology.readthedocs.org/en/latest/). This allows for either html, pdf, or epub versions to be built from the same source files. 

The plan is to just slowly work away at the conversion as time permits.

Of course anyone wanting to clone the book for their own purposes is encouraged to do so, as well as edit, amend or add to the book with a pull request. While I am freely giving up my copyrights with a CC0 license, any works of others referenced or quoted in the present work are subject to the original copyrights of their creators or copyright holders. 

## Brief note on the process

I write using emacs out of preference. Therefore, I have grown to know, and enjoy using the org-mode mark-up language. I  export to rst relying on the [ox-rst package](https://github.com/masayuko/ox-rst). Sometimes there still seems to need to be some native rst, but for the most part it works well. After that I test locally with sphinx-build2 -b html <source> <destination> (actually I now do a `make html`). And when all seems to work right I push to github and rebuild on read the docs.
