# histPsychol
An Online History of Psychology Textbook

## The original motivation for this repo

I have become disappointed with the history of psychology textbooks we offer to undergraduates. First, they are way too expensive. Second, they are too limited. The internet and places such as [archive.org](http://archive.org) have made a wealth of material available at the click of a button. Rather than reading a textbook as an isolated experience, it ought to be possible to integrate that reading with the consultation of original material.

The purpose of this repo is to host what are a bunch of files transitioning from notes I used in my lectures to what I would like to become an online textbook.

For now the material is hosted here in its raw form, and it is built into useful documents on [readthedocs](http://history-of-psychology.readthedocs.org/en/latest/). This allows for either html, pdf, or epub versions to be built from the same source files. 

The plan is to just slowly work away at the conversion as time permits, and, more recently, to use this repo as a teaching resource.


## A teaching resource

I still have all the motivations that follow in the sections below, but now I am using this material as the basis for a course in the [Arts First](https://uwaterloo.ca/arts-first/about) initiative at the University of Waterloo. I am organizing my effort to teach writing and communication around the history of psychology generally, but with the specific tool of contributing sections to this book. The first effort at this was Fall 2018. It went really well. The students engaged in a scaffolded series of assignments over the term to produce (as members of a group) an article for the textbook on one of Scientific Psychology's founders. Beginning with short outlines they built to full entries. As an aside each group also made a short video on their founder that was uploaded to the `uWaterlooPsych <https://www.youtube.com/c/UWaterlooPsych>`__ YouTube channel, and then linked in their write-ups. There were separate instructional sections on plagiarism, and referencing, as well as working through the content and feedback on the mechanics of technical writing. For a group of first-year University students that had not even had a Psych 101 course, I think the results were quite commendable, and advertise the value of having students create content as a route to learning. 

The entries for Arts 140 Fall 2018 can be found at:

1. `Fechner <https://history-of-psychology.readthedocs.io/en/latest/fechner.html>`__
2. `Washburn <https://history-of-psychology.readthedocs.io/en/latest/washburn.html>`__
3. `Terman <https://history-of-psychology.readthedocs.io/en/latest/terman.html>`__
4. `Köhler <https://history-of-psychology.readthedocs.io/en/latest/kohler.html>`__

## Please feel free to contribute

From fixing a typo to making suggestions I am happy to have others offer their input. If you are a psychologist who knows nothing about github, but has some material that you would like to donate for inclusion, just send me it to me by email, and I will take care of adding it to the repository and converting it to a form that allows for it to be exoported to the read the docs site. I am also happy to support and teach you how to do it if you, like me, feel git repositories, and on line documentation offer under exploited tools for educational resources outside of Engineeing and Computer Science. 

If you are one of those who does feel comfortable with these tools and wants to contribute anything from a typo repair to submitting an entry to replace a "stub" just feel free to generate a pull request. And if you like the broad scope of the idea, but don't like the specific content feel free to clone the book and edit, amend or add to the book. Any copyrighted content of mine that you find here is material where I am freely giving up the copyrights with a CC0 license; I want to act as an advocate for expanding the value of these tools to replace the expensive, slow to update, siloed educational materials we so often foist on our students. But, having said that, any works of others referenced or quoted in the present work are subject to the original copyrights of their creators or copyright holders. 

## Brief note on the process

I write using emacs out of preference. Therefore, I have grown to know, and enjoy using the org-mode mark-up language. I  export to rst relying on the [ox-rst package](https://github.com/masayuko/ox-rst) - this is now part of org-mode and no special imports are required. If you have a recent version of emacs and org-mode you can `C-e C-c r r`. However, this was too hard a route for the students that I am asking to contribute. I have them write in any markdown dialect they choose, and I use pandoc to convert to .rst and then I edit the raw rst file to get things to work. I am not an expert in that, and am happy if someone finds something they want me to fix, if they would just tell me how to do it. I test locally with sphinx using a `make html` from the root directory. When all seems to work right locally in the _build directory I push to github and rebuild on read the docs.
