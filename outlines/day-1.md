# Day One: Introductions and Setup

> Discussion: prepping the DH toolkit, barriers

## 1. Setup and Introductions

## 2. Physical Computing and Intro to Code

DH requires computing. 
How can we learn about the basics of computers and code?
How can we examine our relationship with the digital world?
Physical computing / minimal computing, "critical making"

Pedagogical benefits: active, project based learning, "media computing"; digital literacy; computational thinking

[Hello-Arduino](https://evanwill.github.io/hello-arduino/)
- What is a computer? Compare microcontroller ([Arduino](https://www.arduino.cc/)), minicomputer ([Raspberry Pi](https://www.raspberrypi.org/)), desktop computer, vs. server.
- What is code? Plain text, text editor, IDE.
- Explore the concept of [free](https://www.gnu.org/philosophy/free-sw.en.html) and open source software and hardware

## 3. Computer Setup

### Text editor!

All code is [plain text](https://en.wikipedia.org/wiki/Plain_text).
The web is plain text.
You need a good text editor!

- [Notepad++](https://notepad-plus-plus.org/) (windows)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)

### Git and GitHub prep

Create a [GitHub account](https://github.com/join).
If you want this to be a professional account, think about the user name you choose. 
It will be on your profile and web URLs.

Install Git. See [Get Git prep](https://uidaholib.github.io/get-git/0prep.html).

> # Lunch break

## 4. The Web

Idealistic Canadian video: [How Does the Internet Work ?](https://youtu.be/i5oe63pOhLI)

<!-- enbed <iframe width="560" height="315" src="https://www.youtube.com/embed/i5oe63pOhLI" frameborder="0" allowfullscreen></iframe> -->

A network is two or more computers connected.
The internet is network of networks.

What's in a URL:
- https://example.com/about?key=value#anchor
- protocol + domain name (or IP, optional port :80) + path + query / parameters + fragment/anchor

Demo IP addresses: 
- `ping www.google.com` 
- `nslookup www.lib.uidaho.edu` 
- traceroute / tracert / tracepath `tracepath www.google.com`

### Join the web: Set up Reclaim hosting 

## 5. Version Control: Git/GitHub

Check [Get Git!](https://uidaholib.github.io/get-git/)

## 6. Write in plain text: Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub.

Practice by starting a [GitHub Gist](https://gist.github.com/).
Give it file name ending with .md (`test.md`) and paste in this Markdown code:

```
# Heading one

Any line beginning with # will become a heading. 
Leave a blank line between headings and paragraphs.
Lines with out a blank line between them will be joined.

## Heading two

Font can be *Italic* or **Bold**.
Code can be highlighted with `backticks`.
Links look like this [GitHub Help](https://help.github.com/).

Images are like links with a exclamation in front:

![Charles Joseph Minard’s Map (1869)](https://upload.wikimedia.org/wikipedia/commons/2/29/Minard.png)

List:
- dog
- cat
- you can use a dash, asterisk, or plus sign.

Numbered list:
1. one.
2. two. 
5. the actual numbers don't matter.

> Block quote.
> Useful for formatting quotes, asides, or warnings.

A horizontal divide is just some dashes:

----
```

Click "Create public Gist" to see it rendered.
Click "Edit" button to try some more.

Check out this [GitHub Markdown tutorial](https://guides.github.com/features/mastering-markdown/) for more info.

## 7. Discussion

- [What is Digital Humanities?](http://whatisdigitalhumanities.com/) (and its [repository](https://github.com/hepplerj/whatisdigitalhumanities))
- Individual projects, assignment ideas
- Readings
- DH Toolkit barriers

# Resources

DH Making:
- [Jentery Sayers](http://www.jenterysayers.com/) and [MLab](http://maker.uvic.ca/) at UVic
- Matt Ratto, "Critical Making: Conceptual and Material Studies in Technology and Social Life", *Information Society* 27 (2011) DOI:10.1080/01972243.2011.583819
- Kazushi Ohya, ["Programming with Arduino for Digital Humanities"](http://journalofdigitalhumanities.org/2-3/programming-with-arduino-for-digital-humanities/), *JDH* 2, 3 (2013).

Teaching code:
- Deans for Impact, ["The Science of Learning"](https://swcarpentry.github.io/instructor-training/files/papers/science-of-learning-2015.pdf), 2015. (Quick intro to recent education research and teaching myths)
- Leo Porter, Mark Guzdial, Charlie McDowell, and Beth Simon, “Success in Introductory Programming: What Works?” Communications of the ACM 56, 8 (2013), [DOI:10.1145/2492007.2492020](https://doi.org/10.1145/2492007.2492020). (Spoiler: Pair programming, Media Computation, and Peer Instruction. Essentially active, collaborative learning with realistic, meaningful research projects drastically improved learning outcomes and retention in intro CS)
- Therese Huston, *Teaching What You Don't Know* (Harvard University Press, 2009). [UI link](http://search.lib.uidaho.edu/UID:everything:CP71195091260001451) 

GitHub in Education:
- Kris Shaffer, ["Push, Pull, Fork: GitHub for Academics"](http://www.digitalpedagogylab.com/hybridped/push-pull-fork-github-for-academics/), *Digital Pedagogy Lab* (2013).
- Alexey Zagalsky, ["Why you should use GitHub: Lessons for the classroom and newsroom"](http://www.storybench.org/use-github-lessons-classroom-newsroom/), *Storybench* (2015).
- Evan's [Git for Collaboration](https://evanwill.github.io/_drafts/notes/git-collaboration.html), [Get Git](https://uidaholib.github.io/get-git/), and [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/). (happy to do these workshops with a class)

Markdown for writing:
- Dennis Tenen and Grant Wythoff, [Sustainable Authorship in Plain Text using Pandoc and Markdown](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown), *Programming Historian* (2014). ([Pandoc](http://pandoc.org/installing.html) coverts `.md` to other formats such as PDF or .docx)
- [Markdowntutorial](http://www.markdowntutorial.com) (step-by-step 10 minute tutorial)
- Evan's [Writing in Markdown](https://evanwill.github.io/_drafts/notes/writing-markdown.html) notes
