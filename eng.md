# Digital Publishing and the Web

> **A note from the editors:** Each month, a new author from the W3C will keep 
you informed on what we're up to—and how you can be a part of it. This month's 
column is from [Ivan Herman][1], W3C Semantic Web Activity Lead.

Electronic books are on the rise everywhere. For some this threatens centuries-
old traditions; for others it opens up new possibilities in the way we think
about information exchange in general, and about books in particular. Hate it or
love it: electronic books are with us to stay.

A [press release][2] issued by the [Pew Research Center’s Internet & American
Life Project][3] in December 2012 describes an upward trend in the consumption
of electronic books. The trends are similar in the UK, China, Brazil, Japan, and
other countries.

> “…the number of Americans over age 16 reading eBooks rose in 2012 from 16 to 
23 percent, while those reading printed books fell from 72 percent to 67. …the 
number of owners of either a tablet computer or e-book reading device such as a 
Kindle or Nook grew from 18% in late 2011 to 33% in late 2012. …in late 2012 19% 
of Americans ages 16 and older own e-book reading devices such as Kindles and 
Nooks, compared with 10% who owned such devices at the same time last year.” 

What does this mean for web professionals? Electronic books represent a market
that’s powered by core web technologies such as HTML, CSS, and SVG. When you use
EPUB, one of the primary standards for electronic books, you are creating a
packaged website or application. [EPUB3][4] is at the bleeding edge of current
web standards: it is based on HTML5, CSS2.1 with some CSS3 modules, SVG,
OpenType, and WOFF. EPUB3’s embrace of scripting is sure to encourage the
development of more interactivity, which is sought after in education materials
and children’s books.

Recently W3C has been [working more closely][5] with digital publishers to find
out what else the Open Web Platform must do to meet that industry’s needs.

One comment we’ve heard loud and clear is that people care deeply about
centuries-old print traditions. For example, Japanese and Korean users have
accepted that many websites display text horizontally, from left to right. While
that may be ok for the web, when these users read a novel, they expect
traditional layout: characters rendered vertically and from right to left.
Japanese readers often find it more tiring to read a long text in any other way.
To address these requirements, W3C is looking at the challenges that vertical
layout poses for HTML, CSS, and other technologies; see for example [CSS Writing
Modes Module Level 3][6].

[Requirement of Japanese Text Layout][7] summarizes the typesetting traditions 
and resulting requirements for Japanese. These traditions should eventually be 
reproduced on the web as well as in electronic books. In June, W3C will hold a 
digital publishing workshop in Tokyo on the specific issues surrounding 
[internationalization and electronic books][8].

We have also heard that the “page” paradigm—including notions of headers,
footnotes, indexes, glossaries, and detailed tables of contents—is important
when people read books of hundreds or thousands of pages. Web technology will
need to reintegrate these UI elements smoothly; see for example the [CSS Paged
Media Module Level 3][9] (Joe Clark talked about [paged media and the production
of ebooks][10] in 2010, and Nellie McKesson [gave us an update][11] in 2012). In
September in Paris, W3C will hold a workshop on the [creation of electronic
books][12] using web technologies. Note that both this and the Writing Modes
Module are still drafts and need further work. That means now is the right time
for the digital publishing community to have its voice heard!

In the realm of metadata, important to publishers, librarians, and archivists,
the challenge is to agree on vocabulary (and there are many: Harvard’s
[reference to metadata standards][13] is only the tip of the iceberg). Pearson
Publishing recently launched the [Open Linked Education Community Group][14] to
examine creating a curated subset of Wikipedia data that can be used for tagging
educational content.

Here are a few other places to look for activity and convergence:

* People take notes in books and highlight text. Most ebook readers these days 
have built-in support for these features, but they are not widely deployed on 
the web.
* Today search engines tend to ignore electronic books; I expect that will not 
remain the case for long.
* “Offline mode” in web technology is still difficult to use if you try to 
access more than a single page of a site. Since an ebook is quite often a 
packaged website, ebook offline mode will need to improve to support browsing.
* ebooks business models are likely to drive new approaches to monetization, 
some of which may be found in native mobile environments but not yet on the web.

Although publishing has some specific requirements not common to the web
generally, I think that the distinction between a website (or app) and an ebook
will disappear with time. As I have [written before][15], both will demand high-
quality typography and layout, interactivity, linking, multimedia, offline
access, annotations, metadata, and so on. Digital publishers’ interest in the
Open Web Platform is a natural progression of their embrace of the early web.

[1]: http://www.w3.org/People/Ivan/
[2]: http://libraries.pewinternet.org/2012/12/27/e-book-reading-jumps-print-book-reading-declines/
[3]: http://www.pewinternet.org/
[4]: http://www.idpf.org/epub/30/spec/epub30-overview.html
[5]: http://www.w3.org/2012/08/electronic-books/
[6]: http://www.w3.org/TR/css3-writing-modes/
[7]: http://www.w3.org/TR/jlreq/
[8]: https://www.w3.org/2013/06/ebooks/
[9]: http://www.w3.org/TR/css3-page/
[10]: http://alistapart.com/article/ebookstandards
[11]: http://alistapart.com/article/building-books-with-css3
[12]: http://www.w3.org/2012/12/global-publisher/
[13]: http://hul.harvard.edu/ois/digproj/metadata-standards.html
[14]: http://www.w3.org/community/opened/
[15]: http://ivan-herman.name/2013/02/22/browsers-and-ebook-readers/