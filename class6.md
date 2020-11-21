Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine

The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.


However, when we say that Node is built on the V8 engine, we don’t mean that Node programs are executed in a browser. They aren’t. Rather, the creator of Node (Ryan Dahl) took the V8 engine and enhanced it with various features, such as a file system API, an HTTP library, and a number of operating system–related utility methods.

Node Binaries vs Version Manager
Many websites will recommend that you head to the official Node download page and grab the Node binaries for your system. While that works, I would suggest that you use a version manager instead. This is a program that allows you to install multiple versions of Node and switch between them at will. There are various advantages to using a version manager. For example, it negates potential permission issues when using Node with npm and lets you set a Node version on a per-project basis.

You can check that Node is installed on your system by opening a terminal and typing node -v. If all has gone well, you should see something like v12.14.1 displayed. This is the current LTS version at the time of writing.

npm is also the world’s largest software registry. There are over 1,000,000 packages of JavaScript code available to download, with billions of downloads per week.

They can be used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.

And if you want to start developing apps with any modern JavaScript framework (for example, React or Angular), you’ll be expected to have a working knowledge of Node and npm (or maybe Yarn).
Aside from speed and scalability, an often-touted advantage of using JavaScript on a web server — as well as in the browser — is that your brain no longer needs to switch modes. You can do everything in the same language, which, as a developer, makes you more productive (and hopefully, happier). For example, you can easily share code between the server and the client.

Another of Node’s big pluses is that it speaks JSON. JSON is probably the most important data exchange format on the Web, and the lingua franca for interacting with object databases (such as MongoDB). JSON is ideally suited for consumption by a JavaScript program, meaning that when you’re working with Node, data can flow neatly between layers without the need for reformatting. You can have one syntax from browser to server to database.

 can also be used to write your own command line tool, such as this Yeoman-Style generator to scaffold out new projects.


 With the ever-increasing popularity of smartphones, developers are looking into solutions for building mobile applications. For developers with a web background, frameworks such as Cordova and Ionic, React Native, NativeScript, and Flutter allow us to create mobile apps with languages we’re already familiar with: HTML, XML, CSS, and JavaScript.

 React Native is a framework for building apps that work on both Android and iOS. It allows you to create real native apps using JavaScript and React. This differs from frameworks like Cordova, where you use HTML to build the UI, which will then just be displayed within the device’s integrated mobile browser (WebView). React Native has built-in components which are compiled to native UI components, while your JavaScript code is executed through a virtual machine. This makes React Native more performant than Cordova.

 In simple terms, Expo allows you to build React Native apps without the initial headache that comes with setting up your development environment. It only requires you to have Node installed on your machine, and the Expo client app on your device or emulator.

