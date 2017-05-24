# Day Four: Text as Data

Day: [0](day-0.md) | [1](day-1.md) | [2](day-2.md) | [3](day-3.md) | [4](day-4.md) | [5](day-5.md)

> Text analysis, digital reading, computation.

## 1. Reflection / discussion

## 2. Unstructured text to data

OpenRefine Sonnets project

## 3. Text and Machine Learning

OpenRefine sentiment analysis project

> # Lunch Break

## 4. Text / Data Visualization

[VPOD PoemChoice](https://uidaholib.github.io/poemchoice/)

Thinking with visualization: analytics < - > communication

New readings: statistics, visualizations, NLP

Visualize text(s):
- [Juxta](http://juxtacommons.org/) (visual collation, example classroom [assignments](http://www.juxtasoftware.org/using-juxta-in-the-classroom-scholars-lab-presentation/), [Frankenstein editions assignment](https://mla.hcommons.org/?get_group_doc=387/1420320643-Bninski.notesforMLACommons.pdf))
- Jason Davies [WordTree](https://www.jasondavies.com/wordtree/) (visual concordance, D3 web app, [academic explanation](http://hint.fm/projects/wordtree/))
- [Voyant](http://voyant-tools.org/) (suite of viz tools, [Help](http://voyant-tools.org/docs/#!/guide/start), [Voyant Docs](http://docs.voyant-tools.org/), and [VoyantServer](https://github.com/sgsinclair/VoyantServer) for offline use. Explore Adam's writing: [forest](http://voyant-tools.org/?corpus=ad9d4fbe072d540cfc40e0ce9206c9c7&panels=cirrus,reader,trends,summary,contexts), [public](http://voyant-tools.org/?corpus=9201a8d973ae5b0fb618eda9e762d4ae&panels=cirrus,reader,trends,summary,contexts))
- [AntConc](http://www.laurenceanthony.net/software/antconc/) (lots of software and publications from Laurence Anthony)

Text Big Data: 
> Think about Big Data 3 V’s (volume, variety and velocity). Advances are driven by business seeking to process unstructured text data (the web / social media) to extract value.
- Hathi Trust [Research Center Portal](https://sharc.hathitrust.org/) (big text data)
- N-Grams: [Bookworm](http://bookworm.culturomics.org/) or [Google Books Ngram Viewer](https://books.google.com/ngrams) (see [TED talk](https://www.ted.com/talks/what_we_learned_from_5_million_books?language=en))

Natural Language Processing / Machine Learning:
- Typically classification tasks: Entity recognition, POS tagging, topic modeling, sentiment, summarization. (supervised vs. unsupervised)
- Python [NLTK](http://www.nltk.org/) (plus simpler [TextBlob](https://textblob.readthedocs.io/en/dev/), and more powerful [scikit-learn](http://scikit-learn.org/stable/index.html))
- [MALLET](http://mallet.cs.umass.edu/index.php) topic modeling
- [Stanford NLP Group](http://nlp.stanford.edu/software/) (a library of Java apps, e.g. [named entity tagging demo](http://nlp.stanford.edu:8080/ner/), with academic papers explaining their use)
- [Open Calais](http://www.opencalais.com/) (NLP API trained on web and newspaper text)
- Watson [Natural Language Understanding](https://www.ibm.com/watson/developercloud/natural-language-understanding.html) (NLP API trained on web content)

Programming as inquiry

## 5. Project Work and Discussion

distant versus close reading. digital editing and annotating, versus computation. 

# Resources

Ted Underwood, ["Seven Ways Humanists are Using Computers to Understand Text"](https://tedunderwood.com/2015/06/04/seven-ways-humanists-are-using-computers-to-understand-text/) (2015). (overview of types of computational analysis)

Ted Underwood, [paceofchange](https://github.com/tedunderwood/paceofchange) (2015). (GitHub repository sharing code to reproduce analysis reported in his article ["How Quickly Do Literary Standards Change?"](https://figshare.com/articles/How_Quickly_Do_Literary_Standards_Change_/1418394))

Ted Underwood, ["The Quiet Transformations of Literary Studies: What Thirteen Thousand Scholars Could Tell Us"](http://hdl.handle.net/2142/49323), in *New Literary History* (2014).

Jeffrey M. Binder, ["Alien Reading: Text Mining, Language Standardization, and the Humanities"](http://dhdebates.gc.cuny.edu/debates/text/69) in *Debates in the Digital Humanities* (2016).

Stanford Literary Lab [Pamphlets](http://litlab.stanford.edu/pamphlets/). (ongoing series of publications relating to "computational criticism")

[Sunspring](https://youtu.be/LY7x2Ihqjmc). (a film script written by AI)

Tools directories:
- [DiRT Directory](http://dirtdirectory.org/)
- [TAPoR 3](http://tapor.ca/home) (or try [here](http://tapor-test.artsrn.ualberta.ca/home))
- [Keshif VisTools](https://keshif.me/demo/VisTools)
- [Text Visualization Browser]()

Textbooks:
- Brandon Walsh and Sarah Horowitz, [Introduction to Text Analysis: A Coursebook](http://walshbr.com/textanalysiscoursebook/) (2016). (Open textbook, Jekyll project hosted on gh-pages, [repo](https://github.com/walshbr/textanalysiscoursebook))
- Steven Bird, Ewan Klein, and Edward Loper, [Natural Language Processing with Python: Analyzing Text with the Natural Language Toolkit](http://www.nltk.org/book/). (known as the NLTK Book, good intro to using Python and textual analysis concepts, with large sample corpora)
- Stéfan Sinclair & Geoffrey Rockwell, [The Art of Literary Text Analysis](https://github.com/sgsinclair/alta/blob/master/ipynb/ArtOfLiteraryTextAnalysis.ipynb) (2016). (a Python Jupyter notebook based open text)
- Matthew Jockers, *Text Analysis with R for Students of Literature* (2014).
- Julia Silge and David Robinson, [Tidy Text Mining in R](http://tidytextmining.com/) (2017). ([Bookdown](https://bookdown.org/) project written in RMarkdown)
- Nick Montfort, *Exploratory Programming for the Arts and Humanities* (MIT Press, 2016).
- For more see Scott B. Weingart, [Teaching Yourself to Code in DH](http://scottbot.net/teaching-yourself-to-code-in-dh/).

Syllabus / assignments:
- Annie Swafford, [Sherlock Holmes topic modeling assignment](https://sherlockholmeslondondh.wordpress.com/2015/03/23/topic-modeling-assignment/) (2015).
- Lincoln Mullen, [Text Analysis for Historians](http://lincolnmullen.com/courses/text-analysis.2016/) (2016).
- Beth Platte, [Text analysis using Voyant Tools](http://blogs.reed.edu/ed-tech/2017/03/text-analysis-using-voyant-tools/) (2017).
- Pedagogy-Toolkit [Voyant Tools](http://pedagogy-toolkit.org/tools/VoyantTools.html) assignments.
- Max Kemman, [A-Republic-of-Emails](https://github.com/C2DH/A-Republic-of-Emails) (2016). (GitHub repo assignment to analyze wikileaks email dump)
- [DataBasic](https://www.databasic.io/en/). (slick, simple web apps with lessons to introduce text data concepts)
- [Programming Historian](http://programminghistorian.org/) tutorials.
- Evan's [text analysis](https://evanwill.github.io/_drafts/notes/text-analysis.html) and [data viz](https://evanwill.github.io/_drafts/notes/viz-notes.html) notes.
