Table des matières
------------------

-   [1 README contents](#sec-1)
-   [2 Informal notes](#sec-2)
    -   [2.1 Project initialization](#sec-2-1)
    -   [2.2 Producing this README file](#sec-2-2)

1 README contents
-----------------

Nodemacs is essentially a wild experiment.

Its *official* goal is to duplicate the [Pymacs
project](http://pinard/progiciels-bpi.ca/notes/Pymacs.html), replacing
Python by JavaScript in the process. Briefly said, the resulting tool,
once started from Emacs, should allow both-way communication between
Emacs Lisp and JavaScript.

The *real* goal is to experiment in two areas:

-   First, I just do not write enough JavaScript, while I would like to
    deepen my mastering of it. My job duties have never been much on
    this side so far. A good while ago, I switched to Node for serving
    most of my Web sites, as a way to get more frequent contacts with
    JavaScript through required maintenance. But the sad truth (!) is
    that it worked so well, and so quickly, that I was never pulled into
    maintenance afterwards. I guess that developing Nodemacs, and using
    it routinely once it exists, would have better success at
    establishing regular contacts with JavaScript.
-   Second, all projects I have published so far had a fair amount of
    written code, or detailed specifications at least, before I push
    them out in the crowd, so the public drive and direction has always
    well established from the start. Nodemacs escapes this pattern in
    that it has no code, and not even an analysis, before I put it out.
    Moreover, while likely, I am not even sure at this stage that it
    would be usable enough to be useful. So, I intend to develop this
    project on the public place from its real start, instead of having a
    private initial phase.

I expect this to be a humbling path to development: my weaknesses,
hesitations, and wanderings are quite exposed to anybody following the
project. There is the danger of the project being taken over by anyone
disagreeing with the development direction or pace. Years ago, I've been
hurt in the GNU Music project, where Robert Strandh successfully lobbied
Richard Stallman for acquiring the lead, and our whole setup. One-way
forking may indeed occur on GitHub, but I guess I could swallow it more
easily. So I'm risking it!

2 Informal notes
----------------

### 2.1 Project initialization

2012-05-08 mar This is the first time ever that I fully initialize my
own copy of a new project from GitHub, without having it locally first.
While preparing the GitHub project, I checked the *Initialize this
repository with a README* button and also set *Add .gitignore* to
**Node**, to see how it goes.

After cloning the repository locally, I notice a minimal **README.md**
file, in [Markdown
format](http://daringfireball.net/projects/markdown/). The generated
**.gitignore** is missing a newline at end, which I add locally; I also
report this tiny flaw to GitHub maintainers.

### 2.2 Producing this README file

2012-05-08 mar I currently much enjoy Org format for handling my own
notes, and do not feel like switching to Markdown for original sources.
So, **README.md** gets derived automatically from the Org source.

Some of my Org notes are private, and even for the public ones, there
are **:noexport:** sections. Because of these private parts, I do not
make my Org sources directly available. **Nodemacs.org** becomes [an
HTML file](http://pinard.progiciels-bpi.ca/notes/Nodemacs.html) through
the Org publishing feature, and that HTML file is later turned into a
Markdown file using the impressive [Pandoc
tool](http://johnmacfarlane.net/pandoc/).
