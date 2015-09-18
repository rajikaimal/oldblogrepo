---
layout: post
title: Javascript what are you ! 
---


First of all what’s JavaScript exactly ? JavaScript is a single threaded. non-blocking, concurrent language and it’s weird . JavaScript is interpreted using a JavaScript Engine and there are so many out there like V8, Chakra , Rhino . You can find more on https://en.wikipedia.org/wiki/JavaScript_engine

![V8](public/img/v8.jpg) 

Usually JavaScript can do one thing at a time or else AKA the blocking model. Blocking code is bad ! and slow. Humph , If JavaScript is single threaded and if there’s no such thing called multi threading in JavaScript , what should be the solution for concurrency in JavaScript. It’s simple , we should use non-blocking code AKA Asynchronous model which is fast relative to Synchronous code.

Synchronous code

function volume(l,b,h){
   return (h*area(b,l));
}
function area(b,l){
   return (b*l);
}
console.log('Done');
Asynchronous code

Most common Async thingy that we’re using is setTimeout which is given to you by WebAPI s contained in the browser itself.

setTimeout(function(){
   console.log('Done');
},5000);
Asynchronous model uses the mythical Event Loop. Event loop doesn’t solve this async mystery by itself, the call stack , web APIs , and the event queue together with the event loop makes a great combo to make Async code a reality in our browsers and at the same time making things weird

JavaScript is sweet ! or some might say it’s weird, either way it’s future is so bright and don’t hesitate to try it if you are a newbie to web development

JS FTW !