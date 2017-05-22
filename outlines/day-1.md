# Day One: Introductions and Setup

Day: [0](day-0.md) | [1](day-1.md) | [2](day-2.md) | [3](day-3.md) | [4](day-4.md) | [5](day-5.md)

> Prepping the DH toolkit, barriers

## 1. Introductions

## 2. Physical Computing and Intro to Code

DH assumes computing. 
How can we learn about the computers and code that underpin our research and communication?
How can we examine our relationship with the digital world and the cultural assumptions embedded in it?

[Physical computing](http://maker.uvic.ca/physcomp/), [minimal computing](http://go-dh.github.io/mincomp/thoughts/), [critical making](http://conceptlab.com/criticalmaking/).

Physical computing icebreaker: [Hello-Arduino](https://evanwill.github.io/hello-arduino/)

- What is a computer? Compare microcontroller ([Arduino](https://www.arduino.cc/)), minicomputer ([Raspberry Pi](https://www.raspberrypi.org/)), desktop computer, vs. server.
- What is code? Plain text, text editor, IDE.
- [Free](https://www.gnu.org/philosophy/free-sw.en.html) and open source software and hardware.
- Active, project based learning, "media computing"; digital literacy; computational thinking.

## 3. Computer Setup

### Text editor!

All code is [plain text](https://en.wikipedia.org/wiki/Plain_text).
The web is plain text.
You need a good text editor!

- [Visual Studio Code](https://code.visualstudio.com/)
- [Notepad++](https://notepad-plus-plus.org/) (windows)
- [Atom](https://atom.io/)

### Git and GitHub prep

Create a [GitHub account](https://github.com/join).
Think carefully about the user name you choose. It will be on your profile, web URLs, and associated with your work.

Install Git. See [Get-Git prep](https://uidaholib.github.io/get-git/0prep.html).

### OpenRefine install

See [clean-your-data start](https://evanwill.github.io/clean-your-data/3-start.html) page.
- [mac install issues](https://evanwill.github.io/_drafts/notes/open-refine-osx.html)

### ArcGIS Account Setup

[https://uidaho.maps.arcgis.com/home/signin.html](https://uidaho.maps.arcgis.com/home/signin.html)
 
Select the “USING YOUR UNIVERSITY OF IDAHO ACCOUNT” button and login using netID

> # Lunch break

## 4. The Web

Idealistic Canadian video: [How Does the Internet Work ?](https://youtu.be/i5oe63pOhLI)

A network is two or more computers connected.
The internet is network of networks.

What's in a URL:
- https://example.com/about?key=value#anchor
- protocol + domain name (or IP, optional port :80) + path + query / parameters + fragment/anchor

Demo IP addresses: 
- `ping www.google.com` 
- `nslookup www.lib.uidaho.edu` 
- traceroute / tracert / tracepath `tracepath www.google.com`

### Set up Reclaim hosting 

- domain name considerations

uidaho2017

## 5. Version Control: Git/GitHub

Check [Get Git!](https://uidaholib.github.io/get-git/) and [Git for Collaboration Intro](https://evanwill.github.io/_drafts/notes/git-collaboration.html).

Create repository for example assignment.

Introduce project management and history visualizations.
- [Ted Underwood](https://github.com/tedunderwood), [paceofchange](https://github.com/tedunderwood/paceofchange). (code for academic publication, contains more information and details for reproducability and re-use)
- Miriam Posner [Cytoscape tutorials](https://github.com/miriamposner/cytoscape_tutorials) (2016), DOI:10.5281/zenodo.56245. (tutorials for classroom, shared in easy format to re-use)
Shawn Graham, Crafting Digital History, [course workbook](http://workbook.craftingdigitalhistory.ca/), [repository](https://github.com/shawngraham/hist3907o), and [organization](https://github.com/craftingdigitalhistory).

## 6. Write in plain text: Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub.

Create a file in your test repository and give it file name ending with .md (`test.md`). 
Paste in this Markdown code:

```
# Heading One

Any line beginning with # will become a heading. 
Leave a blank line between headings and paragraphs.
Lines with out a blank line between them will be joined.

## Heading Two

Font can be *Italic* or **Bold**.
Code can be highlighted with `backticks`.
Or you can use three backticks to make a code block that will be unformatted text.

### Heading Three 

Links look like this [GitHub Help](https://help.github.com/).
Images are similar to links, with a exclamation in front and alt text in the square brackets:

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

Check out this [GitHub Markdown tutorial](https://guides.github.com/features/mastering-markdown/) for more details.

Create a basic outline of your assignment idea in Markdown.

## 7. Discussion

- [What is Digital Humanities?](http://whatisdigitalhumanities.com/) (and its [repository](https://github.com/hepplerj/whatisdigitalhumanities))
- Individual projects, assignment ideas
- Readings
- DH Toolkit barriers

# Resources

DH Making:
- [Jentery Sayers](http://www.jenterysayers.com/) and [MLab](http://maker.uvic.ca/) at UVic
- Matt Ratto, "Critical Making: Conceptual and Material Studies in Technology and Social Life", *Information Society* 27 (2011). DOI:[10.1080/01972243.2011.583819](http://dx.doi.org/10.1080/01972243.2011.583819)
- Kazushi Ohya, ["Programming with Arduino for Digital Humanities"](http://journalofdigitalhumanities.org/2-3/programming-with-arduino-for-digital-humanities/), *JDH* 2, 3 (2013).

Teaching code:
- Deans for Impact, ["The Science of Learning"](https://swcarpentry.github.io/instructor-training/files/papers/science-of-learning-2015.pdf), 2015. (Quick intro to recent education research and teaching myths)
- Leo Porter, Mark Guzdial, Charlie McDowell, and Beth Simon, “Success in Introductory Programming: What Works?” Communications of the ACM 56, 8 (2013), [DOI:10.1145/2492007.2492020](https://doi.org/10.1145/2492007.2492020). (Spoiler: Pair programming, Media Computation, and Peer Instruction. Essentially active, collaborative learning with realistic, meaningful research projects drastically improved learning outcomes and retention in intro CS)
- Therese Huston, *Teaching What You Don't Know* (Harvard University Press, 2009). [UI link](http://search.lib.uidaho.edu/UID:everything:CP71195091260001451) 

GitHub in Education:
- Kris Shaffer, ["Push, Pull, Fork: GitHub for Academics"](http://www.digitalpedagogylab.com/hybridped/push-pull-fork-github-for-academics/), *Digital Pedagogy Lab* (2013).
- Alexey Zagalsky, ["Why you should use GitHub: Lessons for the classroom and newsroom"](http://www.storybench.org/use-github-lessons-classroom-newsroom/), *Storybench* (2015).
- Evan's [Git for Collaboration](https://evanwill.github.io/_drafts/notes/git-collaboration.html), [Get Git](https://uidaholib.github.io/get-git/), and [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/). (happy to do a version of these workshops with students)

Markdown for writing:
- Dennis Tenen and Grant Wythoff, [Sustainable Authorship in Plain Text using Pandoc and Markdown](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown), *Programming Historian* (2014). ([Pandoc](http://pandoc.org/installing.html) coverts `.md` to other formats such as PDF or .docx)
- [Markdowntutorial](http://www.markdowntutorial.com) (step-by-step 10 minute tutorial)
- Evan's [Writing in Markdown](https://evanwill.github.io/_drafts/notes/writing-markdown.html) notes
