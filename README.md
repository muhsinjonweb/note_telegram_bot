

# buni test uchun readme file ni tekshirish uchun bajardim
<h3># Я сделал это, чтобы проверить файл readme для тестирования</h3>
<h3># I did this to check the readme file for testing</h3>
<h1 align="center">Node.js Telegram Bot API</h1>

<div align="center">

Node.js module to interact with the official [Telegram Bot API](https://core.telegram.org/bots/api).


[![Bot API](https://img.shields.io/badge/Bot%20API-v.5.5-00aced.svg?style=flat-square&logo=telegram)](https://core.telegram.org/bots/api)
[![npm package](https://img.shields.io/npm/v/node-telegram-bot-api?logo=npm&style=flat-square)](https://www.npmjs.org/package/node-telegram-bot-api)
[![Build Status](https://img.shields.io/travis/yagop/node-telegram-bot-api/master?style=flat-square&logo=travis)](https://travis-ci.org/yagop/node-telegram-bot-api)
[![Coverage Status](https://img.shields.io/codecov/c/github/yagop/node-telegram-bot-api?style=flat-square&logo=codecov)](https://codecov.io/gh/yagop/node-telegram-bot-api)

[![https://telegram.me/node_telegram_bot_api](https://img.shields.io/badge/💬%20Telegram-Channel-blue.svg?style=flat-square)](https://telegram.me/node_telegram_bot_api)
[![https://telegram.me/ntbasupport](https://img.shields.io/badge/💬%20Telegram-Group-blue.svg?style=flat-square)](https://telegram.me/ntbasupport)
[![https://telegram.me/Yago_Perez](https://img.shields.io/badge/💬%20Telegram-Yago_Perez-blue.svg?style=flat-square)](https://telegram.me/Yago_Perez)

</div>

## Install


```sh
npm i node-telegram-bot-api
```

## ornatish


```sh
npm i node-telegram-bot-api
```

## Usage

```js
const TelegramBot = require('node-telegram-bot-api');

// replace the value below with the Telegram token you receive from @BotFather
const token = 'YOUR_TELEGRAM_BOT_TOKEN';

// Create a bot that uses 'polling' to fetch new updates
const bot = new TelegramBot(token, {polling: true});

// Matches "/echo [whatever]"
bot.onText(/\/echo (.+)/, (msg, match) => {
  // 'msg' is the received Message from Telegram
  // 'match' is the result of executing the regexp above on the text content
  // of the message

  const chatId = msg.chat.id;
  const resp = match[1]; // the captured "whatever"

  // send back the matched "whatever" to the chat
  bot.sendMessage(chatId, resp);
});

// Listen for any kind of message. There are different kinds of
// messages.
bot.on('message', (msg) => {
  const chatId = msg.chat.id;

  // send a message to the chat acknowledging receipt of their message
  bot.sendMessage(chatId, 'Received your message');
});
```

## Documentation
## qollanma

* [Usage][usage]
* [Examples][examples]
* [Tutorials][tutorials]
* [Help Information][help]
* API Reference [api-release] / [development][api-dev] / [experimental][api-experimental])
* [Contributing to the Project][contributing]
* [Experimental Features][experimental]

_**Note**: Development is done against the **master** branch.
Code for the latest release resides on the **release** branch.
Experimental features reside on the **experimental** branch._


## Community

We thank all the developers in the Open-Source community who continuously
take their time and effort in advancing this project.
See our [list of contributors][contributors].

We have a [Telegram channel][tg-channel] where we post updates on
the Project. Head over and subscribe!

We also have a [Telegram  group][tg-group] to discuss issues related to this library.

Some things built using this library that might interest you:

* [tgfancy](https://github.com/GochoMugo/tgfancy): A fancy, higher-level wrapper for Telegram Bot API
* [node-telegram-bot-api-middleware](https://github.com/idchlife/node-telegram-bot-api-middleware): Middleware for node-telegram-bot-api
* [teleirc](https://github.com/FruitieX/teleirc): A simple Telegram ↔ IRC gateway
* [bot-brother](https://github.com/SerjoPepper/bot-brother): Node.js library to help you easily create telegram bots
* [redbot](https://github.com/guidone/node-red-contrib-chatbot): A Node-RED plugin to create telegram bots visually
* [node-telegram-keyboard-wrapper](https://github.com/alexandercerutti/node-telegram-keyboard-wrapper): A wrapper to improve keyboards structures creation through a more easy-to-see way (supports Inline Keyboards, Reply Keyboard, Remove Keyboard and Force Reply)

## License

**The MIT License (MIT)**

Copyright © 2019 Yago

[usage]:https://github.com/yagop/node-telegram-bot-api/tree/master/doc/usage.md
[examples]:https://github.com/yagop/node-telegram-bot-api/tree/master/examples
[help]:https://github.com/yagop/node-telegram-bot-api/tree/master/doc/help.md
[tutorials]:https://github.com/yagop/node-telegram-bot-api/tree/master/doc/tutorials.md
[api-dev]:https://github.com/yagop/node-telegram-bot-api/tree/master/doc/api.md
[api-release]:https://github.com/yagop/node-telegram-bot-api/tree/release/doc/api.md
[api-experimental]:https://github.com/yagop/node-telegram-bot-api/tree/experimental/doc/api.md
[contributing]:https://github.com/yagop/node-telegram-bot-api/tree/master/CONTRIBUTING.md
[contributors]:https://github.com/yagop/node-telegram-bot-api/graphs/contributors
[experimental]:https://github.com/yagop/node-telegram-bot-api/tree/master/doc/experimental.md
[tg-channel]:https://telegram.me/node_telegram_bot_api
[tg-group]:https://telegram.me/ntbasupport


# Build a Quiz App with HTML, CSS, and JavaScript

![Home Screen](./images/cover.png)

Video Playlist: https://www.youtube.com/playlist?list=PLB6wlEeCDJ5Yyh6P2N6Q_9JijB6v4UejF

Build a Quiz App with HTML, CSS, and JavaScript to improve your Core Web Development

Want to improve your **core Web Develoment skills**? Want to improve your knowledge of **HTML, CSS, and JavaScript**? In this course, you're going to learn how to build a Quiz application **without the assistance of libraries or frameworks**. Here are some of the topic we will cover!

-   Save high scores in Local Storage
-   Create a progress bar
-   Create a spinning loader icon
-   Dynamically generate HTML in JavaScript
-   Fetch trivia questions from Open Trivia DB API

-   JavaScript - Array Functions (splice, map, sort), Local Storage, Fetch API
-   ES6 JavaScript Features - Arrow Functions, the Spread Operator, Const and Let, Template Literals
-   CSS - Flexbox, Animtations, and REM units

## Course Intro and Resources

Welcome to "Build a Quiz App with HTML, CSS, and JS". I'm so excited you decided to take the initiative to improve your core Web Development skills!

In this course, we are going to use fundamental HTML, CSS, and JavaScript skills to build a quiz application. This application will be able to load questions from a 3rd party API, track and display high scores, and so much more! You'll learn how to use Local Storage, create animations, use modern ES6 JavaScript features, and more.

Resources

-   [Course Source Code](https://github.com/jamesqquick/Design-And-Build-A-Quiz-App)
-   [Learn Build Teach Newsletter](https://www.learnbuildteach.com/)
-   [Learn Build Teach YouTube Channel](https://www.youtube.com/c/jamesqquick)

## 1. Create and Style the Home Page

In this video, we are going to create the home page along with a good chunk of the necessary CSS. The home page will consist of a few links for the Game and High Scores pages. We will also create helper CSS classes for Flexbox, buttons, and hiding elements.

I encourage you all to take a look at Emmet snippets for generating HTML and CSS.

Resources

-   [Emmet in Visual Studio Code](https://www.youtube.com/watch?v=5guZjNDcVnA)
-   [Understanding REM Units](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/)
-   [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## 2. Create and Style the Game Page

In this video, we will create the Game Page and display static question and answer information. Eventually, we will load questions from an API, but for now, we will hard code one question so to establish styling.

## 3. Display Hard Coded Question and Answers

In this video, we will load questions from a hard coded array and iterate through available questions as the user answers them. We will use custom data attributes, the ES6 spread operator, and JavaScript arrow functions.

Resources

-   [Creating Code Snippets in Visual Studio Code](https://www.youtube.com/watch?v=K3gLlZm-m_8)
-   [Using Data Attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)
-   [Document Query Selector](https://developer.mozilla.org/en-US/docs/Web/API/Document_object_model/Locating_DOM_elements_using_selectors)
-   [Document Get by ID](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
-   [Spread Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
-   [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## 4. Display Feedback for Correct/Incorrect Answers

In this video, we check the user's answer for correctness and display feedback to the user before loading the next question.

Resources

-   [Bootstrap 4 Colors](https://www.w3schools.com/bootstrap4/bootstrap_colors.asp)
-   [Triple vs Double Equals](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)

## 5. Create Head's Up Display (HUD)

In this video, we will create a Heads Up Display (HUD) for our quiz app. This will display the user's score and current question number.

Resources

-   [ES6 Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

## 6. Create a Progress Bar

In this video, we will take our HUD one step further by creating a visual progress bar to track the user's progress through the questions.

## 7. Create and Style the End Page

In this video, we will create our End page where we will display the user's achieved score. This screen will provide a form for saving the score and links for playing again or going home.

Resources

-   [Local Storage](https://www.w3schools.com/jsref/prop_win_localstorage.asp)

## 8. Save High Scores in Local Storage

In this video, we will save and maintain a high scores array in Local Storage. To do this, we will need to JSON.stringify() and JSON.parse() to convert our high score array to a string and visa versa.

Resources

-   [Local Storage](https://www.w3schools.com/jsref/prop_win_localstorage.asp)

## 9. Load and Display High Scores from Local Storage

In this video, we will create our High Scores page. We will have to load the high scores from Local Storage, iterate through them, and display them on the screen.

Resources

-   [JSON Parse and Stringify](https://alligator.io/js/json-parse-stringify/)
-   [Array Sort](https://www.w3schools.com/js/js_array_sort.asp)
-   [Array Map](https://www.w3schools.com/jsref/jsref_map.asp)
-   [Array Join](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join)

## 10. Fetch API to Load Questions From Local JSON File

In this video, we will move our sample questions from a hard coded array to an external .json file. This will help clean up our Game.js file and set ourselves up to request questions from an API in the next video.

Resources

-   [How to Use the Fetch API](https://scotch.io/tutorials/how-to-use-the-javascript-fetch-api-to-get-data)
-   [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise_)

## 11. Fetch API to Load Questions from Open Trivia API

In this video, we will use Fetch to request a list of questions from the Open Trivia DB API.

Reources

-   [How to Use the Fetch API](https://scotch.io/tutorials/how-to-use-the-javascript-fetch-api-to-get-data)
-   [Open Trivia DB](https://opentdb.com/)
-   [Array Map](https://www.w3schools.com/jsref/jsref_map.asp)
-   [Array For Each](https://www.w3schools.com/jsref/jsref_foreach.asp)

## 12. Create a Spinning Loader

In this video, we will create a simple spinning loader in CSS that will be displayed until we are finished requesting/loading questions from the API.

Resources

-   [Create a CSS Loader](https://www.w3schools.com/howto/howto_css_loader.asp)

## 13. Closing

Thank you so much for going through this course. I truly hope that you enjoyed it and that you have improved your core Web Development skills!!


# boshqa

# Javascript Quiz App

- Questions are dynamically generated using objects constructor
- Login/Logout System using LocalStorage
- Random questionss are asked everytime
- Next button is disabled by default in every question - you must select any option to enable it
- Shows scored percentage + correct answer with good UI at the end
- After completing quiz - your score is saved in LocalStorage - so when you even reload your page you get result instead of questions again
- You have 'Retake Quiz' option available at the end :)

* Worked on UI as well :p

This is made as an assignment while learning Javascript

Demo: https://ovi.github.io/quiz-app

Key: **11223344**


# 222222222222


# css-spinner

[Live Demo](https://loading.io/css/)

Collection of 12 small, elegant pure css spinners for your website's loading animation.

![css spinner](https://raw.githubusercontent.com/loadingio/css-spinner/master/web/static/thumbnail.gif)


## Features

 * vanilla - no external dependency and no additional library required.
 * standalone - use any of them separately.
 * customizable - use Stylus variables to quickly customize them to fit your needs.
 * easy to use - simply copy & paste while also easy to use with pug mixins.
 * small - average size 1K per spinner unminimized, unzipped

## Usage

[loading.io](https://loading.io/) provides a [web interface](https://loading.io/css/) to quickly choose and copy your desired spinners, yet you can still find the source code in this repository. The basic usage is as:

1. Find and download the html files of desired loader under [dist](https://github.com/loadingio/css-spinner/tree/master/dist/) folder.
2. Copy its content to the place you want to use this loader.

Separated CSS and HTML files are also available under [build](https://github.com/loadingio/css-spinner/tree/master/dist/entries) folder for reusing CSS codes to reduce payload size.

We also provide stylus and pug source files for better integrating these spinners into your project. Find corresponding stylus and pug files for your desired spinners under [src/](https://github.com/loadingio/css-spinner/tree/master/src) folders.

To use stylus files alone, you will have to provide variables listed in [vars.styl](https://github.com/loadingio/css-spinner/blob/master/vars.styl).

## npm package

This module is also released through npm as [@loadingio/css-spinner](https://www.npmjs.com/package/@loadingio/css-spinner).


## Build

You can also customize all these loaders by building them yourself.

 * First, update `vars.styl` based on your needs.
 * make sure required packages are installed by `npm install`. You will need NPM / NodeJS pre-installed.
 * build with this command: `npm run build`
   - generated files will be in `dist/` folder.


## Browser Compatibility

These spinners use CSS Animation and Transformation which is widely supported by major modern browsers except IE<=9.  To support older browsers like IE9, please use [loading.io](https://loading.io/animation/icon/) to generate alternative GIF Loaders instead.



## License

All loader files here are released under CC0 License. However, you could attribute to this link: [loading.io css spinner ( https://loading.io/css/ )](https://loading.io/css/) to give loading.io a thumbs-up.

Other source codes are released under MIT License.


## Other Resources

If you want to make custom css loading animation, loading.io also provides [loading.css](https://loading.io/animation/) - A pure CSS loading animation library, and a [helper GIF builder](https://loading.io/animation/icon/). Don't forget to check it out and share your customized loader with us!

# 333 
slick
-------

[1]: <https://github.com/kenwheeler/slick>

_the last carousel you'll ever need_

#### Demo

[http://kenwheeler.github.io/slick](http://kenwheeler.github.io/slick/)

#### CDN

To start working with Slick right away, there's a couple of CDN choices availabile
to serve the files as close, and fast as possible to your users:

- https://cdnjs.com/libraries/slick-carousel
- https://www.jsdelivr.com/projects/jquery.slick

##### Example using jsDelivr

Just add a link to the css file in your `<head>`:

```html
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick.css"/>
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick-theme.css"/>
```

Then, before your closing ```<body>``` tag add:

```html
<script type="text/javascript" src="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick.min.js"></script>
```

#### Package Managers

```sh
# Bower
bower install --save slick-carousel

# NPM
npm install slick-carousel
```

#### Contributing

PLEASE review CONTRIBUTING.markdown prior to requesting a feature, filing a pull request or filing an issue.

### Data Attribute Settings

In slick 1.5 you can now add settings using the data-slick attribute. You still need to call $(element).slick() to initialize slick on the element.

Example:

```html
<div data-slick='{"slidesToShow": 4, "slidesToScroll": 4}'>
  <div><h3>1</h3></div>
  <div><h3>2</h3></div>
  <div><h3>3</h3></div>
  <div><h3>4</h3></div>
  <div><h3>5</h3></div>
  <div><h3>6</h3></div>
</div>
```

### Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
accessibility | boolean | true | Enables tabbing and arrow key navigation.  Unless `autoplay: true`, sets browser focus to current slide (or first of current slide set, if multiple `slidesToShow`) after slide change. For full a11y compliance enable focusOnChange in addition to this.
adaptiveHeight | boolean | false | Adapts slider height to the current slide
appendArrows | string | $(element) | Change where the navigation arrows are attached (Selector, htmlString, Array, Element, jQuery object)
appendDots | string | $(element) | Change where the navigation dots are attached (Selector, htmlString, Array, Element, jQuery object)
arrows | boolean | true | Enable Next/Prev arrows
asNavFor | string | $(element) | Enables syncing of multiple sliders
autoplay | boolean | false | Enables auto play of slides
autoplaySpeed | int  | 3000 | Auto play change interval
centerMode | boolean | false | Enables centered view with partial prev/next slides. Use with odd numbered slidesToShow counts.
centerPadding | string | '50px' | Side padding when in center mode. (px or %)
cssEase | string |  'ease' | CSS3 easing
customPaging | function | n/a | Custom paging templates. See source for use example.
dots | boolean | false | Current slide indicator dots
dotsClass | string | 'slick-dots' | Class for slide indicator dots container
draggable | boolean | true | Enables desktop dragging
easing | string |  'linear' | animate() fallback easing
edgeFriction | integer | 0.15 | Resistance when swiping edges of non-infinite carousels
fade | boolean | false | Enables fade
focusOnSelect | boolean | false | Enable focus on selected element (click)
focusOnChange | boolean | false | Puts focus on slide after change
infinite | boolean | true | Infinite looping
initialSlide | integer | 0 | Slide to start on
lazyLoad | string | 'ondemand' | Accepts 'ondemand' or 'progressive' for lazy load technique. 'ondemand' will load the image as soon as you slide to it, 'progressive' loads one image after the other when the page loads.
mobileFirst | boolean | false | Responsive settings use mobile first calculation
nextArrow | string (html \| jQuery selector) \| object (DOM node \| jQuery object) | `<button type="button" class="slick-next">Next</button>` | Allows you to select a node or customize the HTML for the "Next" arrow.
pauseOnDotsHover | boolean | false | Pauses autoplay when a dot is hovered
pauseOnFocus | boolean | true | Pauses autoplay when slider is focussed
pauseOnHover | boolean | true | Pauses autoplay on hover
prevArrow | string (html \| jQuery selector) \| object (DOM node \| jQuery object) | `<button type="button" class="slick-prev">Previous</button>` | Allows you to select a node or customize the HTML for the "Previous" arrow.
respondTo | string | 'window' | Width that responsive object responds to. Can be 'window', 'slider' or 'min' (the smaller of the two).
responsive | array | null | Array of objects [containing breakpoints and settings objects (see example)](#responsive-option-example). Enables settings at given `breakpoint`. Set `settings` to "unslick" instead of an object to disable slick at a given breakpoint.
rows | int | 1 | Setting this to more than 1 initializes grid mode. Use slidesPerRow to set how many slides should be in each row.
rtl | boolean | false | Change the slider's direction to become right-to-left
slide | string | '' | Slide element query
slidesPerRow | int | 1 | With grid mode initialized via the rows option, this sets how many slides are in each grid row.
slidesToScroll | int | 1 | # of slides to scroll at a time
slidesToShow | int | 1 | # of slides to show at a time
speed | int | 300 | Transition speed
swipe | boolean | true | Enables touch swipe
swipeToSlide | boolean | false | Swipe to slide irrespective of slidesToScroll
touchMove | boolean | true | Enables slide moving with touch
touchThreshold | int | 5 | To advance slides, the user must swipe a length of (1/touchThreshold) * the width of the slider.
useCSS | boolean | true | Enable/Disable CSS Transitions
useTransform | boolean | true | Enable/Disable CSS Transforms
variableWidth | boolean | false | Disables automatic slide width calculation
vertical | boolean | false | Vertical slide direction
verticalSwiping | boolean | false | Changes swipe direction to vertical
waitForAnimate | boolean | true | Ignores requests to advance the slide while animating
zIndex | number | 1000 | Set the zIndex values for slides, useful for IE9 and lower

##### Responsive Option Example
The responsive option, and value, is quite unique and powerful.
You can use it like so:

```javascript
$(".slider").slick({

  // normal options...
  infinite: false,

  // the magic
  responsive: [{

      breakpoint: 1024,
      settings: {
        slidesToShow: 3,
        infinite: true
      }

    }, {

      breakpoint: 600,
      settings: {
        slidesToShow: 2,
        dots: true
      }

    }, {

      breakpoint: 300,
      settings: "unslick" // destroys slick

    }]
});
```




### Events

In slick 1.4, callback methods were deprecated and replaced with events. Use them before the initialization of slick as shown below:

```javascript
// On swipe event
$('.your-element').on('swipe', function(event, slick, direction){
  console.log(direction);
  // left
});

// On edge hit
$('.your-element').on('edge', function(event, slick, direction){
  console.log('edge was hit')
});

// On before slide change
$('.your-element').on('beforeChange', function(event, slick, currentSlide, nextSlide){
  console.log(nextSlide);
});
```

Event | Params | Description
------ | -------- | -----------
afterChange | event, slick, currentSlide | After slide change callback
beforeChange | event, slick, currentSlide, nextSlide | Before slide change callback
breakpoint | event, slick, breakpoint | Fires after a breakpoint is hit
destroy | event, slick | When slider is destroyed, or unslicked.
edge | event, slick, direction | Fires when an edge is overscrolled in non-infinite mode.
init | event, slick | When Slick initializes for the first time callback. Note that this event should be defined before initializing the slider.
reInit | event, slick | Every time Slick (re-)initializes callback
setPosition | event, slick | Every time Slick recalculates position
swipe | event, slick, direction | Fires after swipe/drag
lazyLoaded | event, slick, image, imageSource | Fires after image loads lazily
lazyLoadError | event, slick, image, imageSource | Fires after image fails to load


#### Methods

Methods are called on slick instances through the slick method itself in version 1.4, see below:

```javascript
// Add a slide
$('.your-element').slick('slickAdd',"<div></div>");

// Get the current slide
var currentSlide = $('.your-element').slick('slickCurrentSlide');
```

This new syntax allows you to call any internal slick method as well:

```javascript
// Manually refresh positioning of slick
$('.your-element').slick('setPosition');
```


Method | Argument | Description
------ | -------- | -----------
`slick` | options : object | Initializes Slick
`unslick` |  | Destroys Slick
`slickNext` |  |  Triggers next slide
`slickPrev` | | Triggers previous slide
`slickPause` | | Pause Autoplay
`slickPlay` | | Start Autoplay (_will also set `autoplay` option to `true`_)
`slickGoTo` | index : int, dontAnimate : bool | Goes to slide by index, skipping animation if second parameter is set to true
`slickCurrentSlide` |  |  Returns the current slide index
`slickAdd` | element : html or DOM object, index: int, addBefore: bool | Add a slide. If an index is provided, will add at that index, or before if addBefore is set. If no index is provided, add to the end or to the beginning if addBefore is set. Accepts HTML String || Object
`slickRemove` | index: int, removeBefore: bool | Remove slide by index. If removeBefore is set true, remove slide preceding index, or the first slide if no index is specified. If removeBefore is set to false, remove the slide following index, or the last slide if no index is set.
`slickFilter` | filter : selector or function | Filters slides using jQuery .filter syntax
`slickUnfilter` | | Removes applied filter
`slickGetOption` | option : string(option name) | Gets an option value.
`slickSetOption` | change an option, `refresh` is always `boolean` and will update UI changes...
 | `option, value, refresh` | change a [single `option`](https://github.com/kenwheeler/slick#settings) to given `value`; `refresh` is optional.
 | `"responsive", [{ breakpoint: n, settings: {} }, ... ], refresh` | change or add [whole sets of responsive options](#responsive-option-example)
 | `{ option: value, option: value, ... }, refresh` | change  [multiple `option`s](https://github.com/kenwheeler/slick#settings) to corresponding `value`s.


#### Example

Initialize with:

```javascript
$(element).slick({
  dots: true,
  speed: 500
});
 ```

Change the speed with:

```javascript
$(element).slick('slickSetOption', 'speed', 5000, true);
```

Destroy with:

```javascript
$(element).slick('unslick');
```


#### Sass Variables

Variable | Type | Default | Description
------ | ---- | ------- | -----------
$slick-font-path | string | "./fonts/" | Directory path for the slick icon font
$slick-font-family | string | "slick" | Font-family for slick icon font
$slick-loader-path | string | "./" | Directory path for the loader image
$slick-arrow-color | color | white | Color of the left/right arrow icons
$slick-dot-color | color | black | Color of the navigation dots
$slick-dot-color-active | color | $slick-dot-color | Color of the active navigation dot
$slick-prev-character | string | '\2190' | Unicode character code for the previous arrow icon
$slick-next-character | string | '\2192' | Unicode character code for the next arrow icon
$slick-dot-character | string | '\2022' | Unicode character code for the navigation dot icon
$slick-dot-size | pixels | 6px | Size of the navigation dots

#### Browser support

Slick works on IE8+ in addition to other modern browsers such as Chrome, Firefox, and Safari.

#### Dependencies

jQuery 1.7

#### License

Copyright (c) 2017 Ken Wheeler

Licensed under the MIT license.

Free as in Bacon.
# 4444 
# django-telegram-bot
Sexy Django + python-telegram-bot + Celery + Redis + Postgres + Dokku + GitHub Actions template. Production-ready Telegram bot with database, admin panel and a bunch of useful built-in methods.

[![Sparkline](https://stars.medv.io/ohld/django-telegram-bot.svg)](https://stars.medv.io/ohld/django-telegram-bot)


### Check the example bot that uses the code from Main branch: [t.me/djangotelegrambot](https://t.me/djangotelegrambot)

## Features

* Database: Postgres, Sqlite3, MySQL - you decide!
* Admin panel (thanks to [Django](https://docs.djangoproject.com/en/3.1/intro/tutorial01/))
* Background jobs using [Celery](https://docs.celeryproject.org/en/stable/)
* [Production-ready](https://github.com/ohld/django-telegram-bot/wiki/Production-Deployment-using-Dokku) deployment using [Dokku](https://dokku.com)
* Telegram API usage in pooling or [webhook mode](https://core.telegram.org/bots/api#setwebhook)
* Reverse geocode of user via [ArcGis](https://www.arcgis.com/)
* Export all users in `.csv`
* Native telegram [commands in menu](https://github.com/ohld/django-telegram-bot/blob/main/.github/imgs/bot_commands_example.jpg)

Built-in Telegram bot methods:
* `/broadcast` — send message to all users (admin command)
* `/export_users` — bot sends you info about your users in .csv file (admin command)
* `/stats` — show basic bot stats 
* `/ask_for_location` — log user location when received and reverse geocode it to get country, city, etc.

Check out our [Wiki](https://github.com/ohld/django-telegram-bot/wiki) for more info.

# How to run

## Quickstart: Pooling & SQLite

The fastest way to run the bot is to run it in pooling mode using SQLite database without all Celery workers for background jobs. This should be enough for quickstart:

``` bash
git clone https://github.com/ohld/django-telegram-bot
cd django-telegram-bot
```

Create virtual environment (optional)
``` bash
python3 -m venv dtb_venv
source dtb_venv/bin/activate
```

Install all requirements:
```
pip install -r requirements.txt
```

Create `.env` file in root directory and copy-paste this:
``` bash 
DJANGO_DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
TELEGRAM_TOKEN=<ENTER YOUR TELEGRAM TOKEN HERE>
```

Run migrations to setup SQLite database:
``` bash
python manage.py migrate
```

Create superuser to get access to admin panel:
``` bash
python manage.py createsuperuser
```

Run bot in pooling mode:
``` bash
python run_pooling.py 
```

If you want to open Django admin panel which will be located on http://localhost:8000/tgadmin/:
``` bash
python manage.py runserver
```

## Run locally using docker-compose

If you like docker-compose you can check [full instructions in our Wiki](https://github.com/ohld/django-telegram-bot/wiki/Run-locally-using-Docker-compose).

## Deploy to Production 

Read Wiki page on how to [deploy production-ready](https://github.com/ohld/django-telegram-bot/wiki/Production-Deployment-using-Dokku) scalable Telegram bot using Dokku.

----


slick
-------

[1]: <https://github.com/kenwheeler/slick>

_the last carousel you'll ever need_

#### Demo

[http://kenwheeler.github.io/slick](http://kenwheeler.github.io/slick/)

#### CDN

To start working with Slick right away, there's a couple of CDN choices availabile
to serve the files as close, and fast as possible to your users:

- https://cdnjs.com/libraries/slick-carousel
- https://www.jsdelivr.com/projects/jquery.slick

##### Example using jsDelivr

Just add a link to the css file in your `<head>`:

```html
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick.css"/>
<!-- Add the slick-theme.css if you want default styling -->
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick-theme.css"/>
```

Then, before your closing ```<body>``` tag add:

```html
<script type="text/javascript" src="//cdn.jsdelivr.net/gh/kenwheeler/slick@1.8.0/slick/slick.min.js"></script>
```

#### Package Managers

```sh
# Bower
bower install --save slick-carousel

# NPM
npm install slick-carousel
```

#### Contributing

PLEASE review CONTRIBUTING.markdown prior to requesting a feature, filing a pull request or filing an issue.

### Data Attribute Settings

In slick 1.5 you can now add settings using the data-slick attribute. You still need to call $(element).slick() to initialize slick on the element.

Example:

```html
<div data-slick='{"slidesToShow": 4, "slidesToScroll": 4}'>
  <div><h3>1</h3></div>
  <div><h3>2</h3></div>
  <div><h3>3</h3></div>
  <div><h3>4</h3></div>
  <div><h3>5</h3></div>
  <div><h3>6</h3></div>
</div>
```

### Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
accessibility | boolean | true | Enables tabbing and arrow key navigation.  Unless `autoplay: true`, sets browser focus to current slide (or first of current slide set, if multiple `slidesToShow`) after slide change. For full a11y compliance enable focusOnChange in addition to this.
adaptiveHeight | boolean | false | Adapts slider height to the current slide
appendArrows | string | $(element) | Change where the navigation arrows are attached (Selector, htmlString, Array, Element, jQuery object)
appendDots | string | $(element) | Change where the navigation dots are attached (Selector, htmlString, Array, Element, jQuery object)
arrows | boolean | true | Enable Next/Prev arrows
asNavFor | string | $(element) | Enables syncing of multiple sliders
autoplay | boolean | false | Enables auto play of slides
autoplaySpeed | int  | 3000 | Auto play change interval
centerMode | boolean | false | Enables centered view with partial prev/next slides. Use with odd numbered slidesToShow counts.
centerPadding | string | '50px' | Side padding when in center mode. (px or %)
cssEase | string |  'ease' | CSS3 easing
customPaging | function | n/a | Custom paging templates. See source for use example.
dots | boolean | false | Current slide indicator dots
dotsClass | string | 'slick-dots' | Class for slide indicator dots container
draggable | boolean | true | Enables desktop dragging
easing | string |  'linear' | animate() fallback easing
edgeFriction | integer | 0.15 | Resistance when swiping edges of non-infinite carousels
fade | boolean | false | Enables fade
focusOnSelect | boolean | false | Enable focus on selected element (click)
focusOnChange | boolean | false | Puts focus on slide after change
infinite | boolean | true | Infinite looping
initialSlide | integer | 0 | Slide to start on
lazyLoad | string | 'ondemand' | Accepts 'ondemand' or 'progressive' for lazy load technique. 'ondemand' will load the image as soon as you slide to it, 'progressive' loads one image after the other when the page loads.
mobileFirst | boolean | false | Responsive settings use mobile first calculation
nextArrow | string (html \| jQuery selector) \| object (DOM node \| jQuery object) | `<button type="button" class="slick-next">Next</button>` | Allows you to select a node or customize the HTML for the "Next" arrow.
pauseOnDotsHover | boolean | false | Pauses autoplay when a dot is hovered
pauseOnFocus | boolean | true | Pauses autoplay when slider is focussed
pauseOnHover | boolean | true | Pauses autoplay on hover
prevArrow | string (html \| jQuery selector) \| object (DOM node \| jQuery object) | `<button type="button" class="slick-prev">Previous</button>` | Allows you to select a node or customize the HTML for the "Previous" arrow.
respondTo | string | 'window' | Width that responsive object responds to. Can be 'window', 'slider' or 'min' (the smaller of the two).
responsive | array | null | Array of objects [containing breakpoints and settings objects (see example)](#responsive-option-example). Enables settings at given `breakpoint`. Set `settings` to "unslick" instead of an object to disable slick at a given breakpoint.
rows | int | 1 | Setting this to more than 1 initializes grid mode. Use slidesPerRow to set how many slides should be in each row.
rtl | boolean | false | Change the slider's direction to become right-to-left
slide | string | '' | Slide element query
slidesPerRow | int | 1 | With grid mode initialized via the rows option, this sets how many slides are in each grid row.
slidesToScroll | int | 1 | # of slides to scroll at a time
slidesToShow | int | 1 | # of slides to show at a time
speed | int | 300 | Transition speed
swipe | boolean | true | Enables touch swipe
swipeToSlide | boolean | false | Swipe to slide irrespective of slidesToScroll
touchMove | boolean | true | Enables slide moving with touch
touchThreshold | int | 5 | To advance slides, the user must swipe a length of (1/touchThreshold) * the width of the slider.
useCSS | boolean | true | Enable/Disable CSS Transitions
useTransform | boolean | true | Enable/Disable CSS Transforms
variableWidth | boolean | false | Disables automatic slide width calculation
vertical | boolean | false | Vertical slide direction
verticalSwiping | boolean | false | Changes swipe direction to vertical
waitForAnimate | boolean | true | Ignores requests to advance the slide while animating
zIndex | number | 1000 | Set the zIndex values for slides, useful for IE9 and lower

##### Responsive Option Example
The responsive option, and value, is quite unique and powerful.
You can use it like so:

```javascript
$(".slider").slick({

  // normal options...
  infinite: false,

  // the magic
  responsive: [{

      breakpoint: 1024,
      settings: {
        slidesToShow: 3,
        infinite: true
      }

    }, {

      breakpoint: 600,
      settings: {
        slidesToShow: 2,
        dots: true
      }

    }, {

      breakpoint: 300,
      settings: "unslick" // destroys slick

    }]
});
```




### Events

In slick 1.4, callback methods were deprecated and replaced with events. Use them before the initialization of slick as shown below:

```javascript
// On swipe event
$('.your-element').on('swipe', function(event, slick, direction){
  console.log(direction);
  // left
});

// On edge hit
$('.your-element').on('edge', function(event, slick, direction){
  console.log('edge was hit')
});

// On before slide change
$('.your-element').on('beforeChange', function(event, slick, currentSlide, nextSlide){
  console.log(nextSlide);
});
```

Event | Params | Description
------ | -------- | -----------
afterChange | event, slick, currentSlide | After slide change callback
beforeChange | event, slick, currentSlide, nextSlide | Before slide change callback
breakpoint | event, slick, breakpoint | Fires after a breakpoint is hit
destroy | event, slick | When slider is destroyed, or unslicked.
edge | event, slick, direction | Fires when an edge is overscrolled in non-infinite mode.
init | event, slick | When Slick initializes for the first time callback. Note that this event should be defined before initializing the slider.
reInit | event, slick | Every time Slick (re-)initializes callback
setPosition | event, slick | Every time Slick recalculates position
swipe | event, slick, direction | Fires after swipe/drag
lazyLoaded | event, slick, image, imageSource | Fires after image loads lazily
lazyLoadError | event, slick, image, imageSource | Fires after image fails to load


#### Methods

Methods are called on slick instances through the slick method itself in version 1.4, see below:

```javascript
// Add a slide
$('.your-element').slick('slickAdd',"<div></div>");

// Get the current slide
var currentSlide = $('.your-element').slick('slickCurrentSlide');
```

This new syntax allows you to call any internal slick method as well:

```javascript
// Manually refresh positioning of slick
$('.your-element').slick('setPosition');
```


Method | Argument | Description
------ | -------- | -----------
`slick` | options : object | Initializes Slick
`unslick` |  | Destroys Slick
`slickNext` |  |  Triggers next slide
`slickPrev` | | Triggers previous slide
`slickPause` | | Pause Autoplay
`slickPlay` | | Start Autoplay (_will also set `autoplay` option to `true`_)
`slickGoTo` | index : int, dontAnimate : bool | Goes to slide by index, skipping animation if second parameter is set to true
`slickCurrentSlide` |  |  Returns the current slide index
`slickAdd` | element : html or DOM object, index: int, addBefore: bool | Add a slide. If an index is provided, will add at that index, or before if addBefore is set. If no index is provided, add to the end or to the beginning if addBefore is set. Accepts HTML String || Object
`slickRemove` | index: int, removeBefore: bool | Remove slide by index. If removeBefore is set true, remove slide preceding index, or the first slide if no index is specified. If removeBefore is set to false, remove the slide following index, or the last slide if no index is set.
`slickFilter` | filter : selector or function | Filters slides using jQuery .filter syntax
`slickUnfilter` | | Removes applied filter
`slickGetOption` | option : string(option name) | Gets an option value.
`slickSetOption` | change an option, `refresh` is always `boolean` and will update UI changes...
 | `option, value, refresh` | change a [single `option`](https://github.com/kenwheeler/slick#settings) to given `value`; `refresh` is optional.
 | `"responsive", [{ breakpoint: n, settings: {} }, ... ], refresh` | change or add [whole sets of responsive options](#responsive-option-example)
 | `{ option: value, option: value, ... }, refresh` | change  [multiple `option`s](https://github.com/kenwheeler/slick#settings) to corresponding `value`s.


#### Example

Initialize with:

```javascript
$(element).slick({
  dots: true,
  speed: 500
});
 ```

Change the speed with:

```javascript
$(element).slick('slickSetOption', 'speed', 5000, true);
```

Destroy with:

```javascript
$(element).slick('unslick');
```


#### Sass Variables

Variable | Type | Default | Description
------ | ---- | ------- | -----------
$slick-font-path | string | "./fonts/" | Directory path for the slick icon font
$slick-font-family | string | "slick" | Font-family for slick icon font
$slick-loader-path | string | "./" | Directory path for the loader image
$slick-arrow-color | color | white | Color of the left/right arrow icons
$slick-dot-color | color | black | Color of the navigation dots
$slick-dot-color-active | color | $slick-dot-color | Color of the active navigation dot
$slick-prev-character | string | '\2190' | Unicode character code for the previous arrow icon
$slick-next-character | string | '\2192' | Unicode character code for the next arrow icon
$slick-dot-character | string | '\2022' | Unicode character code for the navigation dot icon
$slick-dot-size | pixels | 6px | Size of the navigation dots

#### Browser support

Slick works on IE8+ in addition to other modern browsers such as Chrome, Firefox, and Safari.

#### Dependencies

jQuery 1.7

#### License

Copyright (c) 2017 Ken Wheeler

Licensed under the MIT license.

Free as in Bacon.
# django-telegram-bot
Sexy Django + python-telegram-bot + Celery + Redis + Postgres + Dokku + GitHub Actions template. Production-ready Telegram bot with database, admin panel and a bunch of useful built-in methods.

[![Sparkline](https://stars.medv.io/ohld/django-telegram-bot.svg)](https://stars.medv.io/ohld/django-telegram-bot)


### Check the example bot that uses the code from Main branch: [t.me/djangotelegrambot](https://t.me/djangotelegrambot)

## Features

* Database: Postgres, Sqlite3, MySQL - you decide!
* Admin panel (thanks to [Django](https://docs.djangoproject.com/en/3.1/intro/tutorial01/))
* Background jobs using [Celery](https://docs.celeryproject.org/en/stable/)
* [Production-ready](https://github.com/ohld/django-telegram-bot/wiki/Production-Deployment-using-Dokku) deployment using [Dokku](https://dokku.com)
* Telegram API usage in pooling or [webhook mode](https://core.telegram.org/bots/api#setwebhook)
* Reverse geocode of user via [ArcGis](https://www.arcgis.com/)
* Export all users in `.csv`
* Native telegram [commands in menu](https://github.com/ohld/django-telegram-bot/blob/main/.github/imgs/bot_commands_example.jpg)

Built-in Telegram bot methods:
* `/broadcast` — send message to all users (admin command)
* `/export_users` — bot sends you info about your users in .csv file (admin command)
* `/stats` — show basic bot stats 
* `/ask_for_location` — log user location when received and reverse geocode it to get country, city, etc.

Check out our [Wiki](https://github.com/ohld/django-telegram-bot/wiki) for more info.

# How to run

## Quickstart: Pooling & SQLite

The fastest way to run the bot is to run it in pooling mode using SQLite database without all Celery workers for background jobs. This should be enough for quickstart:

``` bash
git clone https://github.com/ohld/django-telegram-bot
cd django-telegram-bot
```

Create virtual environment (optional)
``` bash
python3 -m venv dtb_venv
source dtb_venv/bin/activate
```

Install all requirements:
```
pip install -r requirements.txt
```

Create `.env` file in root directory and copy-paste this:
``` bash 
DJANGO_DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
TELEGRAM_TOKEN=<ENTER YOUR TELEGRAM TOKEN HERE>
```

Run migrations to setup SQLite database:
``` bash
python manage.py migrate
```

Create superuser to get access to admin panel:
``` bash
python manage.py createsuperuser
```

Run bot in pooling mode:
``` bash
python run_pooling.py 
```

If you want to open Django admin panel which will be located on http://localhost:8000/tgadmin/:
``` bash
python manage.py runserver
```

## Run locally using docker-compose

If you like docker-compose you can check [full instructions in our Wiki](https://github.com/ohld/django-telegram-bot/wiki/Run-locally-using-Docker-compose).

## Deploy to Production 

Read Wiki page on how to [deploy production-ready](https://github.com/ohld/django-telegram-bot/wiki/Production-Deployment-using-Dokku) scalable Telegram bot using Dokku.

----
