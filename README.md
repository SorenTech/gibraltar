# gibraltar

Gibraltar is a platform agnostic front-end template. It is powered by a vuejs singple page app. It gives generic routing for content objects that it expects to be delivered over a REST API, but does not offer specific connections to any specific backend. To connect to a backend, a "translater" must be added to your project to connect with the specific backend and translate it's object types into those used by gibraltar's own routing. This can be easily done using repeition.

## Why?

Gibraltar is meant to provide an easy framework for developing front-end templates powered by vuejs single-page apps. These apps will receive content from a specified backend over a REST API. Why would you want to do this?

 - Encapsulating your front-end in a separate app like this creates better separation of concerns, making development and maintenance easier in the long run
 - Moving view rendering to the front-end can speed up page-loading on your web page or application
 - JavaScript applications can be more easily cached by a CDN of your choice, reducing the workload on your back-end servers
 - Using a separate front-end app means you can keep lots of front-end functionality in the front-end without needing to load up your CMS with lots of extra plugins and extensions
 - VueJS is a lighter framework than most other alternatives, keeping your application lean and fast
 - Using a generic template framework like gibraltar lets you easily build for multiple platforms without needing to make dramatic changes to your workflow. Combining this with using repeition to provide routing translation can really speed up your workflow

## Supported Content Types Out of the Box

 - Pages
 - Posts (blog posts)
 - Menus and Menu Items
 - Category taxonomies
 - Tag taxonomies
 - Author taxonomies

Additional content types can be easily added to your app by registering routes in the router. You'll also need to add them to your translator to make them work.

## Backends Supported by Repetition

Repetition is under active development. It will eventually support the following backends:

 - WordPress (through the REST API)
 - Ghost
 - Joomla (through a REST API)
 - Drupal (in "headless mode")
 - Squarespace (through the REST API)
 - Contentful
 - Keystone JS
 - Directus
 - Prismic.io
 - others?

In addition, by passing 'all' as your backend choice, repetition will eventually be able to create version of your template for every supported platform.

## Contributing

Feel free to fork and send pull requests. Issues may also be logged in the GitHub issue tracker.

Please note that this project is in it's early stages and not yet production ready. We cannot provide production level support (yet).

Also, please note that this project is being primarily developed for our own internal use. You may freely use and adapt it for your own purposes, but we cannot offer support for uses beyond what it was designed for.


