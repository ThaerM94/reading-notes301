# Read-12


### EJS Partials :

* Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in.
 Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

* Like a lot of the applications we build, there will be a lot of code that is reused

##### Using EJS Partials  :
We have our partials defined now. All we have to do is call them in the files that we need them. Let's go into `<index.ejs>` and `<about.ejs>` and use them in there. We will also define the full width and sidebar layouts here using the good old Bootstrap grid. Using Partials The syntax to use an EJS partial is: `<<% include FILENAME %>>`. The path to the partial is relative to the current file.

Advanced Layouts
Currently, EJS doesn't support the ability to have layouts. So far we have just brought in other partials, but not really used layouts the way we would expect templating to work (extending a layout file and passing a view file into that). There have been projects in the past to try to bring templating to EJS. The two main projects are EJS Locals and EJS Express Layouts.
These provide the ability to define different layouts like a sidebar layout and a full width layout and then call those on the fly. Sadly, EJS Locals is no longer maintained and EJS Express Layouts doesn't work with Express 4 at the time of this writing. Hopefully that will change in the future.

### Conclusion :
EJS let's us spin up quick applications when we don't need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.


[Main Page](https://thaerm94.github.io/reading-notes301)