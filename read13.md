# Read-13 

## Sending form data

##### Client/server architecture :
* At it's most basic, the web uses a client/server architecture that can be summarized as follows. 
* a `<client>` (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

** To get a better idea of how client-server architectures work, read our Server-side website programming first steps module. **

The `<form>` element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are `<action>` and `<method>`.


### The method attribute :
The `<method>` attribute defines how data is sent. `<The HTTP protocol>` provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the `<GET>` method and the `<POST>` method


### Methods :
*  `<GET method>` : The GET method is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource."

* `<POST method>` : The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.

* If you need to send a password (or any other sensitive piece of data), never use the GET method or you risk displaying it in the URL bar, which would be very insecure.
* If you need to send a large amount of data, the POST method is preferred because some browsers limit the sizes of URLs. In addition, many servers limit the length of URLs they accept.


##### Viewing HTTP requests :
1. Open the developer tools.
2. Select "Network"
3. Select "All"
4. Select "foo.com" in the "Name" tab
5. Select "Headers"

#### Other Languages and Frameworks :
1. Django for Python (a bit more heavyweight than Flask, but with more tools and  options).
2. Express for Node.js.
3. Laravel for PHP.
4. Ruby On Rails for Ruby.

[Main Page](https://thaerm94.github.io/reading-notes301)