#WEEK 1:
Eloquent Js: https://github.com/gSchool/eloquent-javascript-solutions

#Week 2:
Stretch #1
  Tip Calculator: Refactor the entire page so it contains no markup in the body at all (other than the script tags)
  Use createElement and appendChild and the like.

Stretch #2
Rewrite both Eloquent JavaScript solutions without using a loop. Consider forEach, map and reduce.

HTML FORMS ASSESSMENT
Iterations: https://github.com/gSchool/js-iteration
Intro to Objects: https://github.com/gSchool/intro-to-objects-js
CSV-Markdown: https://github.com/gSchool/csv-to-markdown-js
Eloquent Js: http://eloquentjavascript.net/17_http.html#h_uaWwL8WGXf

STRETCH:
  http://eloquentjavascript.net/04_data.html#h_nSTX34CM1M
  http://eloquentjavascript.net/04_data.html#h_IJBU+aXOIC

STRETCH:
Create your own Pixel Art Maker, which lets you click on a grid to "paint" pixel art.
  A user selects a color and clicks on pixels to paint them with the selected color.
  Get 10 or so small divs on the screen
  Add an event listener to each so that when I click on a pixel it turns red
  Add a color palette div with 2 colors(red and purple)which allows the user to set the current "paintbrush" color instead of it always being set to red
  Add the rest of the standard rainbow colors to the color palette
  Add enough divs to fill up the entire screen

Bonus Challenges:
Add a color picker which allows the user to select any color. Look into the HTML5 color input.
Add the ability to click and drag to paint multiple pixels at once
Add a paintbucket tool which allows a user to drag a box across the screen and paint all pixels that fall inside that box


#Week 3:
** See Daily Plans
1pm - leftPad / rightPad
2pm - transpose
3pm - max / queryString

1pm - Query string parsing with multi-select input, duplicate names
2pm - AJAX error handling
3pm - AJAX timeouts

STRETCH:
should take: "person[first_name]=jeff&person[last_name]=dean";
should return:
{
  person: {
    first_name: "jeff",
    last_name: "dean",
  }
}
STRETCH: https://github.com/gSchool/http-errors-timeouts-and-circuit-breakers
JavaScript Challenges: https://github.com/gSchool/javascript-challenges

#WEEK 4
** See Daily Plans

Iteration and Object Assessment: https://github.com/gSchool/iteration-and-object-assessment
Node Parsing: https://github.com/gSchool/node-async-text-parsing-0
Node log Parsing: https://github.com/gSchool/js-node-log-file-parsing

Express Calculator Exercise
Create a simple calculator app using Express.
When a user visits /add/9/3, it should display 12
When a user visits /sub/9/3, it should display 6
When a user visits /mult/9/3, it should display 27
When a user visits /div/9/3, it should display 3
Bonus: Refactor your code to use only one route rather than 4 separate routes.

Song That Doesn't End: https://github.com/gSchool/song-that-doesnt-end-js
Objects To Tables: https://github.com/gSchool/objects-to-tables-js
Async reduce with constraints:https://github.com/gSchool/async-reduce-with-constraints
Body Parser Practice: https://github.com/gSchool/module-exports-body-parser-practice
Exercise 2: Air Travel Calculator
Apply what you've learned by grabbing (and slightly modifying) the logic you wrote for air-travel-calculator and using it to make the same app but with Express, Node.js, and Jade.
Mimetic (query string parser) - github repo only
mail-merge-express: https://github.com/gSchool/mail-merge-express


STRETCH: Express Library!
Build an Express application from scratch (don't use the generator) that allows users to create books. You should use an array as your way of storing book objects and each book should have a title, author and year. Figure out how to add css styling to your app.

$ mkdir express-library
$ mkdir views
$ touch app.js
$ npm init
$ npm install --save express
$ npm install --save body-parser
$ npm install --save jade
$ touch .gitignore
$ echo node_modules > .gitignore
$ git init
$ git add -A
$ git commit -m "Initial commit"
More:if you examine all of your views and find that you are repeating yourself, research what partials are in Express and how to include them - use partials to refactor and clean up your code.
add an additional route that allows the user to sort all of the books alphabetically

STRETCH:
http://howto.galvanize.com/tutorials/2015-05-27-javascript-weather-app/
http://howto.galvanize.com/tutorials/2015-05-15-javascript-filtering/
http://howto.galvanize.com/tutorials/2015-05-07-javascript-inbox/

#WEEK 5:
READ: wed, watch video: thurs
http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/
JS ACCUMULATOR ASSESSMENT: https://github.com/gSchool/js-accumulator-assessment
On the side: https://github.com/kolodny/exercises
Mongo Bookstore: https://github.com/gSchool/mongodb-bookstore/
Express-Mongo-Crud: https://github.com/gSchool/express-mongo-crud
Sequence Diagrams: https://github.com/gSchool/sequence-diagrams
Selector Demo: https://github.com/gSchool/selector-demo
* CSS exercises: https://github.com/gSchool/css-exercises
* CSS Grid Building: https://github.com/gSchool/css-grid-building
* CSS Floats exercises: https://github.com/gSchool/css-floats-exercise
http://learnlayout.com/
http://www.smashingmagazine.com/2009/10/the-mystery-of-css-float-property/
Markdown-table-processor: https://github.com/gSchool/markdown-table-processor

#WEEK 6:
SEE MONDAY/(WEDNESDAY/Thurs for cookies/password)/FRIDAY!!!!
Path mathching: https://gist.github.com/zilkey/a7ff021fe2599ab54763
Express-validations: https://github.com/gSchool/express-validations-intro
STRETCH
  Extract your errors out into an include and use it to render errors for both forms
  Case insensitive uniqueness validation on puppy ID
  Extract validations out to test driven functions / objects

#WEEK 7: Personal Projects!

#Week 8:
SEE - mon, tues/wed / Thurs/
Cookie-Session: https://github.com/expressjs/cookie-session
middleware: https://github.com/gSchool/express-middleware-practice
cookie: https://github.com/expressjs/cookie-session#simple-view-counter-example
higher Order Functions: https://github.com/gSchool/express-higher-order-function-practice
Passport Oath: https://github.com/gSchool/express-passport-linkedin
TIC TAC TOE

#WEEK 9:
SEE MON/TUES/thurs/FRI!
oop: https://github.com/gSchool/js_oop_exercise
methods/constructors: https://github.com/gSchool/js-methods-this-constructors
this: https://github.com/gSchool/what-is-this
shapes: https://github.com/gSchool/shapes_javascript_inheritance
styleguide: http://gocode.colorado.gov/styleguide/ && https://www.rockymountaincancercenters.com/styleguide/#
Start styleguide: https://agile-cove-8646.herokuapp.com/styleguide
mongoose: https://github.com/gSchool/mongoose_countries_app

Suppose you're in a hallway lined with 100 closed lockers. You begin by opening every locker. Then you close every second locker. Then you go to every third locker and open it (if it's closed) or close it (if it's open). Let's call this action toggling a locker. Continue toggling every nth locker on pass number n. After 100 passes, where you toggle only locker #100, how many lockers are open?

#WEEK 10/11:
See week 11 TUESDAY
modeling data: https://github.com/gSchool/modeling-data
zoo associations: https://github.com/gSchool/mongo_zoo_associations_app
asynchronous callbacks: https://github.com/gSchool/asynchronous-js-nested-callbacks
mongo associations: https://github.com/gSchool/mongo-associations
promises: https://github.com/gSchool/javascript-promises-with-monk
associated objects: https://github.com/gSchool/express-mongo-associated-objects
assessment: https://github.com/gSchool/express-mongo-associations-assessment

canvas: https://github.com/zbunde/intro_to_canvas
canvas tutorial: https://github.com/pgrunde/CanvasTutorial/tree/master
recursion: https://gist.github.com/zbunde/13137cea1a9bcc61cabb
databases: https://www.youtube.com/watch?v=OmpsGuQTMs0
crud assessment: https://github.com/gSchool/express-crud-assessment
recursion: http://blog.javascriptroom.com/2013/01/10/fibonacci-an-introduction-to-recursion/
snippets: https://github.com/gSchool/snippets
CSS-Animations: https://github.com/gSchool/css-animations/tree/gh-pages


#WEEK 12: Group Projects

#WEEK 13:
module.exports: https://github.com/gSchool/module.exports

#Week 14:

Angular:
	Reddit Clone
  "Mean Tea Firebase apps"
  "Angular w/ User Auth + APIs
SQL
  "Units 1-3 Workshop on Express"
  Build an entire CRUD app and deploy
  Build CRUD with associations / migrations
Algorithms
  "In JavaScript Strings / Arrays TDD"
  "In JavaScript Recursion - Depth-first-search LinkedLists"
  "TDD in Java Binary trees / Linked lists Stacks / Queues"
Rails
  New app
  Create routes, controllers, models, views
  Basic form_for
  Deploy to Heroku / run migrations
  install rails_12factor gem
  Associations
  Validations
  CRUD
  "Asset Pipeline Devise + Auth APIs"


#REST:
gulp
divshot
rails - CRUD, auth, partials SEE WEEK 17: WEDNESSDAY 9/9
Java
sql
jquery-https://github.com/gSchool/boxes-jQuery-playground
      -https://github.com/gSchool/js-audio-layering
SOLID-https://github.com/gSchool/refactoring-to-solid
polymorphism-https://github.com/gSchool/polymorphic-activity-feed-js
ES6-https://github.com/gSchool/es2015-with-babeljs
Babel
RegEx
Express - PostgreSQL - (Sequelize)
React- https://github.com/gSchool/react-intro/tree/step-01
Rantly-https://github.com/gSchool/rantly-language-framework-agnostic

<!-- angular express mongo
angular express PostgreSQL
react express mongo
react express PostgreSQL
angular rails mongo
angular rails PostgreSQL
react rails mongo
react rails PostgreSQL
php angular
php react
mySQL
Socket.io -->


#Angular:
Practice assessment: https://github.com/gSchool/angular-practice-assessment
ui-router: https://github.com/gSchool/simple-ui-router-tutorial
