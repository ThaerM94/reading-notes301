# Read 05

## WHAT IS HEROKU? 
Heroku focuses relentlessly on apps and the developer experience around apps. Heroku lets companies of all sizes embrace the value of apps, not the distraction of hardware, nor the distraction of servers - virtual or otherwise.

* After log in/sign up >> and test the version >> should `<Prepare the app>` 

.. >> To clone a local version of the sample application that you can then deploy to Heroku, execute the following commands in your local command shell or terminal:

`<git clone https://github.com/heroku/node-js-getting-started.git>`
`<cd node-js-getting-started>`

You now have a functioning Git repository that contains a simple application as well as a `<package.json>` file, which is used by Node’s dependency manager. 


### View logs

Heroku treats logs as streams of time-ordered events aggregated from the output streams of all your app and Heroku components, providing a single channel for all of the events.

View information about your running app using one of the logging commands,
`<heroku logs --tail:>`


### Define a Procfile

Use a Procfile, a text file in the root directory of your application, to explicitly declare what command should be executed to start your app.

The Procfile in the example app you deployed looks like this:

`<web: node index.js>`
This declares a single process type, web, and the command needed to run it. The name web is important here. It declares that this process type will be attached to the HTTP routing stack of Heroku, and receive web traffic when deployed.


[Main Page](https://thaerm94.github.io/reading-notes301)