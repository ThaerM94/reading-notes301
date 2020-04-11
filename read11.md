#Read-11

## EJS :
`< <%= EJS %> >`
Embedded JavaScript templating ;
EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.

##### Install
It's easy to install EJS with NPM:
`<$ npm install ejs>`

##### Use
Pass EJS a template string and some data. BOOM, you've got some HTML.

** let ejs = require('ejs'),
    people = ['geddy', 'neil', 'alex'],
    html = ejs.render('<%= people.join(", "); %>', {people: people}); **

##### Docs :
for example >>> 
** <% if (user) { %>
  <h2><%= user.name %></h2>
<% } %> **

#### Options :
`<cache>` Compiled functions are cached, requires `<filename>`
`<filename>` Used by cache to key `<caches>`, and for includes
`<context>` Function execution context
`<compileDebug>` When `<false>` no debug instrumentation is compiled
`<client>` Returns standalone compiled function
`<delimiter>` Character to use with angle brackets for `<open/close>`
`<debug>` Output generated function body
`<_with>` Whether or not to use `<with() {}>` constructs. If `<false>` then the     `<locals>` will be stored in the locals object.
`<localsName>` Name to use for the object storing local variables when not using `<with>` Defaults to `<locals>`
`<rmWhitespace>` Remove all safe-to-remove whitespace, including leading and trailing whitespace. It also enables a safer version of `<-%>>` line slurping for all scriptlet tags (it does not strip new lines of tags in the middle of a line).
`<escape>` The escaping function used with `<<%=>` construct. It is used in rendering and is .`<toString()>`ed in the generation of client functions. (By default escapes XML).
`<outputFunctionName>` Set to a string (e.g., `<'echo'>` or `<'print'>`) for a function to print output inside scriptlet tags.
`<async>` When `<true>`, EJS will use an async function for rendering. (Depends on async/await support in the JS runtime.

### Tags :
`<<%>` 'Scriptlet' tag, for control-flow, no output
`<<%_>` ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
`<<%=>` Outputs the value into the template (HTML escaped)
`<<%->` Outputs the unescaped value into the template
`<<%#>` Comment tag, no execution, no output
`<<%%>` Outputs a literal '<%'
`<%>>` Plain ending tag
`<-%>>` Trim-mode ('newline slurp') tag, trims following newline
`<_%>.` ‘Whitespace Slurping’ ending tag, removes all whitespace after it

### Includes :
`<Includes>` are relative to the template with the include call. (This requires the 'filename' option.) For example if you have "./views/users.ejs" and "./views/user/show.ejs" you would use `<<%- include('user/show'); %>>`.

You'll likely want to use the raw output tag `<(<%-)>` with your include to avoid double-escaping the HTML output.


[Main Page](https://thaerm94.github.io/reading-notes301)