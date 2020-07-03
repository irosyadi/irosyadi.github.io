# markdown-it

## Tables (extension) 

## Strikethrough (extension) 


# Markdown basics

Just like many other apps, Zettlr makes use of `Markdown`, originally invented by [John Gruber](https://daringfireball.net/). Of course, over such a long period of time, a huge amount of developments have taken place, that have created the possibilities of modern Markdown applications. In this document the following topics are covered:

1. [A brief history of Markdown](#a-brief-history)
2. [Dialects of Markdown](#markdown-dialects)

***

## A brief history

Since the personal computer became widely available in the 1990s, there were two groups of formats existing side-by-side: word processor documents, such as `.doc`, or `.odt` and code documents, such as `.js`, `.cpp` or `.py`. Both groups of documents contain human-readable text, but there was one simple, yet huge difference: While JavaScript-files or C++-files contained plain text (i.e. only the text that you would see when you open such a file), word processor documents contained a _lot_ more stuff. Word processor documents always hold information about the page size (e.g., A4 or letter), how different blocks should be formatted (e.g., the font of headings or how much blockquotes are indented). If you open a Word/Office-document on your PC right now, you can see what I mean: You immediately see what is a heading based on the font-size font-weight of its text.

For a long time, both these groups of documents stayed as distinct as would their users. Most office-workers only know how to use Microsoft Word or Excel, maybe also LibreOffice-implementations, while close to nobody coming from a STEM-background would voluntarily use Word or similar software. Those scientists have chosen a different path: they developed a programming language called LaTeX, which allows them to create neatly formatted PDF-files from a bunch of code---they follow the same workflow as researchers from the arts and humanities or regular administrative officers, but use different documents for that.

When Markdown was inaugurated by John Gruber in 2004, it was basically like saying: "Why not both?" Markdown combines both the clear reading experience from word processor documents with the benefits of software code documents, which is both versatile and easy to use---even for people that only know how to operate Word or Writer. One small example: While in word processors you would create a heading by typing "some text" and then selecting the `Heading 1` format from some menu, in Markdown you would simply type `# some text`, where the hashtag-symbol tells you immediately: "This is a first level heading!"

At first, Markdown was basically a small script John Gruber wrote for himself to yield these benefits, and it contained a lot of inconsistencies and didn't support many different elements. But over the years, progress was made. Two dates are notable:

- 2004: [John Gruber](https://daringfireball.net/projects/markdown/) initially launches Markdown
- 2012: A group of developers form [CommonMark](https://spec.commonmark.org/) to standardise Markdown into an internationally accepted norm.

## Markdown Dialects

Today, several implementations of the Markdown syntax coexist. The most noteworthy are:

- **MultiMarkdown**: Extends the initial syntax with footnotes, tables and some metadata.
- **Markdown Extra**: Again some additions to the initial syntax.
- **GitHub Flavoured Markdown**: This is a variety of Markdown invented by the hosting platform GitHub (which Zettlr is also hosted on!) and is today one of the most common dialects.
- **Pandoc Markdown**: Pandoc Markdown is a superset of GitHub flavoured Markdown and adds support for even more elements.
- **CommonMark**: Tries to implement all possible elements, while being unambiguous. Notably, CommonMark not yet includes a specification for footnotes.