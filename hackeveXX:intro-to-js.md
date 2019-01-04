---
type: HackEve
name: Introduction to JavaScript 
event-description: Being a ubiquitous language, available on user-end wherever there is a browser, there's a wealth of things that you can do with JavaScript — some of these including making web-apps, animations, games, and more. We'll explore some of these in greater detail in the session. It'll be a hands-on session, so bring your laptops. Session is open to all students, only prerequisite is that you should know some programming language (e.g. Python)
location: C01
start-date: DD MONTH YY
start-time: 5:45 PM
speaker: @peey
duration: "2 Hours"
volunteers: @raghav-kukreti
byld-admin-poc: @peey
---

Flow: 
 - What is JS (3 minutes)
 - Demo: Syntax (5-10 minutes)
 - What can you do with JS? For this we use demos: A showcase of different things open and see (and perhaps interact with) (20-30 minutes)
 - Let's Byld (an assortment of things)

[Slides](https://docs.google.com/presentation/d/1gpeheFyMvGrcl4hehNVbR4VSsQBlOZ4pV-SwEf93fyY/edit#slide=id.g4c0a0b8078_0_9)

## Links for demo:
 - [New Year Fireworks](https://codepen.io/fuzzyma/pen/REjeex) using JS on SVG
 - [WebSpeech API](https://codepen.io/mallendeo/pen/WZdWzG)
 - [three.js examples](https://threejs.org/examples)
 - [jQuery todo List](https://codepen.io/diasnour03/project/editor/AYeQQR)
 - [Three.js Sound Visualization](https://codepen.io/nelsonr/pen/vJmQOj)
 - [Typeform esque form](https://codepen.io/arcs/pen/OmZaex)
 - [Youtube thumbnail extractor (we can interface to apps we know)](https://codepen.io/tjFogarty/project/editor/AzvroK)

## Let's Byld
   1. A counter - [Boilerplate on CodePen](https://codepen.io/peey/pen/GPyqBe?editors=1010)
   2. An animation - [Boilerplate on CodePen](https://codepen.io/peey/pen/LMeRpX?editors=1010)
   3. Hello using localStorage - [Boilderplate on CodePen](https://codepen.io/peey/pen/zypKaM?editors=1010)

## WebSocket Client Example - Echo Server
```js
// Create WebSocket connection.
const socket = new WebSocket('ws://echo.websocket.org');

// Connection opened
socket.addEventListener('open', function (event) {
    socket.send('Hello Server!');
});

// Listen for messages
socket.addEventListener('message', function (event) {
    console.log('Message from server ', event.data);
});
```


## Things to search
 - MVC frameworks like vuejs
 - node.js for backend
 - Greasemonkey / tampermonkey

## Resources
 - Syntax: https://learnxinyminutes.com/docs/javascript/, http://www.learn-js.org/en/Arrays
 - http://eloquentjavascript.net/ part 2 The: Browser, 14 and 15 for learning, 19 for a good project

This content is taken from [this gist](https://gist.github.com/peey/0bdde4f9394776b0d420de43133f3ad8) which was shared with all attendees for easy access to links.
