# Read-04 

### Flags
We are learning how to construct a regex but forgetting a fundamental concept: flags.
A regex usually comes within this form /abc/, where the search pattern is delimited by two slash characters /.

* data validation (for example check if a time string i well-formed)

* data scraping (especially web scraping, find all pages that contain a certain set of words eventually in a specific order)

* data wrangling (transform data from “raw” to another format)
string parsing (for example catch all URL GET parameters, capture text inside a set of parenthesis).

* syntax highlightning, file renaming, packet sniffing and many other applications involving strings (where data need not be textual).

### Common Responsive Layouts with CSS Grid (and some without!)

**a responsive template that you’ll see all over the web, a large intro image followed by smaller images, buttons or articles. Have a look at the code from the glitch link above.**

* The repeat() function takes two arguments, the first will define the number of column tracks and the second, what width the tracks should be.

#### The Holy Grail Layout (with no set heights!)

* The ‘Holy Grail’ layout describes a page with a header and footer that stick at the top and bottom of the window respectively, and a content section that is split into two sidebars and the main content sits between them.

*  This has been notoriously difficult to solve in an elegant way with CSS due to the need to stretch the content to push the footer down to the bottom of the page. With CSS grid, creating this layout requires very few lines of code.


[Main Page](https://thaerm94.github.io/reading-notes301)