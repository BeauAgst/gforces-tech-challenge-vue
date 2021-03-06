![GForces][logo]

<h1 style="text-align: center;">Tech Challenge (Vue.js)</h1>

This is a simple technical challenge to show us your ability using Vue.js. If you run into any issues, please contact Chris at [chris.munn@gforces.co.uk][1]. Spend as little or as long as you wish on it, but please try to complete as much as possible. Functionality is the main priority over design. You'll be asked to talk about your code in your interview. 

Please commit often! We would like to see your thought process as you work through the challenge.

-------

### Base requirements
* We'd like you to fork this repository, and create a branch called `feature/{your name}`
* Vue.js projects built at GForces use the [Airbnb JavaScript Style Guide][2] to keep code consistent and readable. The codebase within this project has linting errors, and these will need to be resolved so that you can continue development.
* We would then like you to set up [Vue Router][3], create a `BookView` component and apply it to the route `/books`
* Using [axios][4] (or another library if you'd prefer), we'd like you to grab and display a list of 40 Stephen King novels using the [Google Books API][5].
* Use a responsive design approach to make the layout work on a range of screen sizes
* Try to create a good user experience
* Think about folder structure, and keeping code organised.
* Consider cross-browser support (Chrome, Firefox, Safari, IE9+)

-------

### Novice
All of the above requirements, plus:
* Use a pre-processor (SASS, LESS, Stylus, etc.)
* Create some CSS animations

-------

### Intermediate
All of the above requirements, plus:
* Show more information on selection of a book
* Add option to sort results by published date/price/rating/categories

-------

### Advanced
All of the above requirements, plus:
* Anything else that demonstrates your skills and competency as a developer. Here's a few possible ideas to get you started:

+ Create a more advanced search with extra features
+ Create custom routes to load specific books
+ Introduce Unit testing
+ Use the TDD process
+ Use a language that compiles to JavaScript

-------

When you feel like you've completed the challenge, please submit a PR to master, accompanied by an email to Chris at [chris.munn@gforces.co.uk][1] letting him know that you've finished.

[logo]: src/assets/logo.svg
[1]: mailto:chris.munn@gforces.co.uk
[2]: https://github.com/airbnb/javascript
[3]: https://router.vuejs.org
[4]: https://github.com/axios/axios
[5]: https://developers.google.com/books/docs/v1/using#PerformingSearch