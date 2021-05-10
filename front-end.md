---
title: Learn front-end web development
author:
  - Ori Marash
  - Yanai Shaviv
---

Being a front-end developer is all about presenting content in the best way
possible for your users. This document goes over how to learn web development
from scratch.

This syllabus is not a tutorial. It will point you to _where_ you can learn.
Nothing in this document is optional. By the end, if you follow all the steps,
you'll be a confident front-end developer.

## Tips for learning

Use the following tips to be more efficient with your learning.

* **Don't copy-paste.**

    If you copy-paste, you won't encounter as many bugs as you would when
    working normally. Programming is 80% debugging.

* **Read the entire chapter before moving on.**

    Some chapters tell you not to learn things. You won't know unless you read
    through it all.

* **Read slowly and methodically. When you get impatient, take a break.**

    Documentation is often insightful but boring. Everyone gets impatient, take
    a five-minute break when it happens.

* **Do not watch video tutorials. If you must, immediately apply what you've
  learned.**

    Video tutorials are "passive" learning. "Active" learning is more effective
    than "passive". You might watch a video and feel that you're learning, but
    if you don't apply what you've learned, you will forget it quickly.

* **Have fun.**

    If what you're trying to learn is boring, try to figure out how you could
    use it in an actual project. If that doesn't work, move on to something else
    for a bit. Bored students don't learn well.

## Development environment

**If you don't know what to use, use [Replit][replit].**

If you can, use an online system, especially one of the following:

* [Replit][replit]: Great for trying out small projects. Not great for custom
    setups, e.g. TypeScript.
* **Code Sandbox**: Alternative to Replit.
* **Google Cloud Shell**: Requires some work but great for more complicated
  setups, e.g. Webpack, TypeScript

[replit]: https://replit.com/

If you encounter problems with these, consider:

* **Google Cloud Compute virtual machines**: Computers running on Google's
    servers that you can access from your computer.

When all else fails, use your personal computer to work on code.

## HTML, CSS, and JavaScript

HTML, CSS, and JavaScript are the fundamentals of web development. This chapter
guides you through how to learn them.

### First things first, learn HTML

Although you can present content using any file, web developers use HTML.

  1. [Complete the HTML course on Codecademy][codeacademy-html].
  2. Create five websites with plain HTML. Play around with as many tags as you
     can. You can use [a random website idea generator][random-website] if
     you can't think of ideas.

[codeacademy-html]: https://www.codecademy.com/learn/learn-html
[random-website]: https://www.generatormix.com/random-website-idea-generator

* Do not learn CSS (yet), focus on writing good HTML.
* Do not memorize HTML tags, use [a reference][htmlreference] instead.

[htmlreference]: https://htmlreference.io/

**Explanation**: Codecademy has excellent courses with up-to-date information.
Working on projects is a very effective way to learn.

### Accessibility

You must make websites that everyone can use.

  1. Read through [why accessibility is important][why-a11y].
  2. Read through [this accessibility guide][a11y-guide].

[why-a11y]: https://www.w3.org/WAI/fundamentals/accessibility-intro
[a11y-guide]: https://github.com/fejes713/accessibility-guide

**Explanation:** Making the web accessible benefits individuals, businesses, and
society. Please, follow the guidelines set out by the WAI.

### Next, learn CSS

Use CSS to style your websites.

  1. Complete the [CSS course on Codecademy][codeacademy-css].
  2. Practice `flexbox` using [flexbox froggy][flexbox-froggy], and read through
     [the complete guide to flexbox][complete-flexbox].
  3. Style the sites you made earlier, using ideas from [Dribbble][dribbble].
  4. Post a screenshot of one of the sites somewhere. Your Twitter, to your mum,
     anywhere.

[codeacademy-css]: https://www.codecademy.com/learn/learn-css
[complete-flexbox]:  https://css-tricks.com/snippets/css/a-guide-to-flexbox/
[dribbble]: https://dribbble.com/

* Do not use a preprocessor such as SASS.
* Learn how to add tiny details now. Later on, focus on getting 80% of the way
  there.

**Explanation:** Flexbox is a valuable CSS property that can speed up design.
Learning CSS at an early stage is helpful, as you'll use it in loads of
projects. Posting screenshots means you work on every detail.

### Bootstrap

Bootstrap is a bunch of CSS that people from around the world have already
written. By using Bootstrap, you'll save time writing CSS.

  1. [Install Bootstrap][bootstrap] (using `<link>`, not `npm`!).
  2. Try out some styles that sound interesting to you.

[bootstrap]: https://getbootstrap.com/

> Bootstrap is one example of a CSS library. There are [other CSS
> libraries][css-frameworks] but lots of sites use Bootstrap.

[css-frameworks]: https://github.com/troxler/awesome-css-frameworks

### To complete the trinity, learn JavaScript

JavaScript adds interactivity to your site.

  1. Complete the [JavaScript course on Codecademy][codeacademy-js].
     TODO: find a better resource for OO
  2. Reach 100 "honour" on [Codewars][codewars].
  3. Read [this Mozilla article][mozilla-dom], and complete the challenge at the
     end of it.

[mozilla-dom]: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents

* This will be tricky if you haven't used any programming language before. If
    you already know a programming language, consider reading through
    [JavaScript in Y minutes] first.
* This will take longer than learning HTML and CSS.

[JavaScript in Y minutes]: https://learnxinyminutes.com/docs/javascript/

**Explanation:** JavaScript is essential in modern web development.
Understanding it well is critical. You will use JavaScript in almost every
project. Reaching 100 honour will take a while. Stick with it, and you'll have
outstanding problem-solving skills.

### You can now practice HTML, CSS, and JavaScript

Great! Now comes the fun part:

  1. Create an *exciting* website using something that you haven't used before.
  2. Create a *practical* website. Something you might use every day.

Repeat these two steps for as long as you want. The more projects you work on,
the better you will get.

* You can find exciting JavaScript on [Mozilla's documentation of
  JavaScript][mozilla-javascript]. Read through and find something fun.
* When you make practical websites, solve problems which you encounter every
    day.

[mozilla-javascript]: https://developer.mozilla.org/

Here's [a list of some website ideas][website-ideas] if you're stuck.

[website-ideas]: https://workshops.hackclub.com/

**Explanation:** learning by working on projects is a highly effective
learning method.

### Publish your work using GitHub Pages

Now that you have done a few projects, upload them to the Internet. GitHub
provides free hosting for static sites. This service is called "GitHub pages".

  1. Read the [documentation on how to upload projects][github-new-repo],
  2. Read the [documentation on how to use GitHub pages][github-pages].
  3. Upload your projects to GitHub pages.

**Note:** You don't have to name your repository anything specific (contrary to
what the documentation might imply).

[github-new-repo]: https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site#creating-a-repository-for-your-site
[github-pages]: https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site#creating-your-site

**Explanation:** Publishing your work means that you complete everything.
Completion is critical for effective learning at this stage.

## Useful development tools

Now that you're comfortable with HTML, CSS, and JavaScript, you can move on with
your learning. Your first step is to increase the number of tools at your
disposal. This chapter guides you through learning software that your colleagues
might expect you to know as a developer.

This chapter covers the following:

* Git
* Chrome dev tools

### Learn Git

Git is software that manages the versions of your code.

  1. Install Git on your computer. Download [Github Desktop][github-desktop],
     it will install Git for you.
  2. Install [Git-it][git-it] and complete all the tutorials.

[github-desktop]: https://desktop.github.com/
[git-it]: https://github.com/jlord/git-it-electron#what-to-install

**Explanation:** Companies and coworkers will expect you to have a basic
understanding of Git. These steps will give you 80% of the commands and
knowledge you need to use Git.

### Chrome devools

Chrome and other browsers provide a panel for troubleshooting your code.

  1. Instsall [Chrome][chrome-install] (if you don't have it already).
  2. Read through [the documentation for Chrome Devtools][chrome-devools]

[chrome-install]: https://chrome.google.com
[chrome-devtools]: https://developer.chrome.com/docs/devtools/overview/

**Explanation:** This panel helps you find and fix issues with your front-end
code quickly. The tool gets even more necessary when debugging complicated front-end
setups.

## A little bit of theory

When moving on to more advanced projects, it's helpful to know some information
about the tools your users will use. This chapter covers the following:

* The Internet
* Browsers
* Domain names
* Web security

### How does the internet work?

The Internet is what the browser accesses to get to your website.

  1. Read through [how the internet works][how-internet-works].

[how-internet-works]: https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work

### How does your browser show websites?

Browsers are software that displays web pages.

  1. Read through ["How Browsers Work"][how-browsers-work].

[how-browsers-work]: https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work

**Explanation:** Your users will access your websites using browsers such as
Chrome, Firefox, or Safari. You're accessing this tutorial using a browser right
now! It's helpful to know how the browser works for troubleshooting and debugging
issues. This chapter might solidify knowledge you've already gotten from
practical experience.

### How do domain names work?

You should use a domain name so your users won't have to remember the IP address
to your server.

  1. Read through [how domain names work][how-domain-names-work]

[how-domain-names-work]: https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name

**Explanation:** When publishing a website, people often don't know how to link
a domain name to it. You should understand how domain names work to make this
process easier.

### Security on the web

TODO: Can't find a good resource that collates this...

## Showing valuable data

Front-end web development is all about displaying content. This chapter guides
you through learning how to bring more helpful content to your website. This
chapter covers the following:

* APIs
* Databases

### Communicating with APIs

An "application programming interface" (API) lets one software
easily communicate with another. You can use JavaScript to get data from
another service and show it to your users.

TODO: Can't find a good resource that collates this...
use reqres.in
use axios/fetch

### Databases

You've learned how to query APIs in the previous chapter. Now, it's time to make
your own. Most APIs need databases, a way of storing data for a long time.
Databases are the backbone of every website. It is essential to understand them.

  1. TODO: introduction to databases

  2. SQL is a way of telling your database what to do. It's different from other
  programming languages because you don't have to tell the database _how_ to do
  things, just what result you want. Complete [the Codecademy course on
  SQL][codecademy-sql].

  3. Now, you should build up experience with communicating with a database.
  Just like how you queried endpoints in the last chapter, you can query your
  database with a JavaScript library.

     TODO: find out a way to try out local development without any server-side
     things, find a pre-made one!! dog thing on GitHub??
       FOUND IT!! <https://github.com/parse-community/parse-server>  although,
       this is no-sql

  4. So far, you've looked at SQL databases. The next step is to look into the
     more modern `no-SQL` databases. These databases look more like objects than
     tables. Read through [the Firestore documentation][firestore-docs].

  5. Do five projects with Firebase.
    TODO: more help here

[codecademy-sql]: https://www.codecademy.com/learn/learn-sql
[firestore-docs]: https://firebase.google.com/docs/firestore

## Development tools

Developers love making their lives easier. These tools make developing websites
more accessible. Modern developers use these tools to improve their productivity.

### Static site generators

Instead of making an HTML file for each page, developers use static site
generators to do this for them. For example, you can make a template for "blog
post", then reuse it for all your articles instead of copy-pasting for each one.

  1. Make [the quickstart Jekyll project][jekyll-quickstart]. You might have to
  tinker with your development environment for this to work.
  2. Make a Jekyll website with a customised theme using [this tutorial][jekyll-custom-theme-tutorial].
  3. Read through [this page on Hugo][hugo-introduction].

[jekyll-quickstart]:
[jekyll-custom-theme-tutorial]:
[hugo-introduction]:

### Webpack

TODO
  > include babel

### NPM

TODO

### TypeScript

**Knowledge Section:** You only have to read the following section. It is
intended to provide you with an overview of existing technologies, so you have
the context for when you encounter them in the real world.

  1. Read through [TypeScript for the New Programmer][typescript-intro].

[typescript-intro]: https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html

### SASS

SASS is a tool that compiles your CSS files. SASS adds features to CSS to make
it more scaleable. For example, variables, functions, and nesting.

  1. Read through [this gist that goes through SASS examples][sass-examples].

[sass-examples]: https://gist.github.com/arsho/4f87ba7ed0ac8f580c8bf3f265ceba0d

## React and other libraries

With the work you've done so far, you might have encountered some of the
following problems:

* Having to read through big HTML files.
* Writing the same code over and over again for the same effect. For example,
    three buttons that look the same but have different text require lots of
    repeated code.
* Complicated events and reactions to events. For example, showing dialogs
    or creating dropdown menus.

React solves these problems by letting you write HTML inside your JavaScript
code.

This section also covers other commonly-used JavaScript libraries.

### React

Most front-end web development jobs will require you to know React.

  1. Follow this [the React beginner tutorial][react-tutorial].
  2. Read and try out [the React main concepts][react-main-concepts].
  3. Read and try out [React hooks][react-hooks].
  4. Build five projects using React.
  5. Look through [sample React projects]

  TODO: i need more info

[react-tutorial]: https://reactjs.org/tutorial/tutorial.html
[react-main-concepts]: https://reactjs.org/docs/hello-world.html
[react-hooks]: https://reactjs.org/docs/hooks-intro.html
[react-sample-projects]: https://reactjs.org/community/examples.html#small-examples

### Axios

Developers use Axios to make HTTP requests. Axios uses the Promise API so
the code to make requests has nice syntax.

  1. Read through [the Axios documentation][axios-docs].
  2. Try out sending some HTTP requests.

[axios-docs]: https://www.npmjs.com/package/axios

### Lodash

Developers use [Lodash] to prevent having to write standard algorithms.

An example:

```js
var _ = require('lodash')

_.partition([1,2,3,4], n => n % 2) // returns [[1, 3], [2, 4]]
```

[lodash]: https://lodash.com/

(There are no steps to complete in this section.)

### Vue.js

**Knowledge Section:** You only have to read the following section. It is
intended to provide you with an overview of existing technologies, so you have
the context for when you encounter them in the real world.

Vue.js has similar functionality to React. It provides ways to create
components, build interactions, maintain a state, and more. It is less popular
than React. However, it is the only primary JavaScript framework not to be
backed by a company. Facebook owns React; Google owns Angular (another
alternative). Vue.js is entirely open-source and maintained by the community.

If you'd like to learn more about Vue.js, you could get started by reading [the
Vue.js documentation][vuejs].

[vuejs]: https://vuejs.org/

## DevOps

This section helps you gain familiarity with some production aspects of web
development.

Every company has different ways of shipping their code to their users. Some
websites have developers working in the live version, where every change is
reflected to their users immediately. Other companies have a development
environment, which the public can't access, where the developers can try out
changes.

When working on a new project, ask about the system in place before making
changes. Repositories will often have a file called `CONTRIBUTING` to explain
how to make changes to their code.

This section covers:

* Testing
* Hosting
* CI/CD

### Testing

  1. writing basic tests
  2. using jest
  3. testing react
  4. how to write good tests

### Hosting

You can't serve your site from your computer. If your computer shuts down or
needs to restart, your site goes down. Also, hackers could get into your local
network and steal your information if your code has security flaws.

Luckily, big companies such as Google, Amazon, and Microsoft rent out their
computers to whoever wants them. You can run your code on their servers for a
fee.

These services also provide specialised computers which do specific tasks, for
example, run a database. The specialists at these companies work on the
database, so you don't have to set it up yourself.

However, having access to a computer is still not very helpful. You have to do
various tasks which you would probably instead not do. For example:

* Set up a server without any security vulnerabilities.
* Copy in the latest code every time you make a change.
* Set up the environment in the server (installing `npm`, `node`, etc.)

There are better solutions, though. More abstracted computers where you upload
code, and they do the rest. Some examples of these services are:

* Vercel
* Heroku
* Firebase
* Netlify
* GitHub pages (static only)

  1. Upload a project to each of the above services.
  2. Set up a website on Amazon Web Services.

**Note:** As a front-end web developer, this usually isn't your problem.
But, it's good to have an idea of how this all works. Also, if you want to
publish your website, you should know how to do so correctly.

### CI/CD

**Knowledge Section:** You only have to read the following section. It is
intended to provide you with an overview of existing technologies, so you have
the context for when you encounter them in the real world.

Continuous integration/Continuous delivery (CI/CD) allows developers to work on
products and release the new code efficiently. CI/CD systems usually take the
following form:

* A Git repository to which developers upload code.
* A server that runs tasks on this repository.

For example, the server could run some of the following tasks:

* Run style checks (e.g. using semicolons in JavaScript files).
* Check that all tests pass.
* Send a message to the lead developer.
* Upload the new code to the server.
* Upload the new code to a staging (temporary) server for further tests.

CI/CD is helpful because it prevents mistakes. For example, developers don't
accidentally upload test code to the live server. Also, it enforces best
practices such as testing.

You can use [GitHub Actions][github-actions] to run a CI/CD system. There are
other platforms which provide similar services such as GitLab, CircleCI and
Jenkins.

[github-actions]: https://github.com/features/actions

## Business and ethics

To launch websites that represent your business or make money, you must know
about the following topics:

* Privacy
* SEO
* Advertisements

### Privacy

TODO

### SEO

A large part of users will discover your website through their search engine.
Just like how you probably found this website. To make search engines display
your website instead of other people's websites, you need to use Search Engine
Optimisation.

  1.

TODO

### Advertisements

Lots of websites make money from advertisements. Most of these advertisements
run with [Google AdSense].

[google adsense]: https://www.google.com/adsense

TODO: pros and cons?

## Final words

Congratulations on completing this course. Hopefully, you feel confident as a
front-end web developer. If you have any ideas for improving the syllabus, please
[fill out an issue on GitHub][kea-github].

[kea-github]: https://github.com/penguoir/kea/issues
