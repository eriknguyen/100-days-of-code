# 100 Days Of Code - Log

### Day 1: Jan 03, 2017 
##### 

**Today's Progress**: Started github page with a basic single-page portfolio

**Thoughts:** I spent around 2 hours for this and I think this can be improved. This is a very simple page since I haven't got any idea how I should design my page and I don't have much information to put as well. It's at least a good start for the challenge though.

**Link to work:** [Erik's Github Page](http://eriknguyen.github.io/)

### Day 2: Jan 04, 2017
##### 

**Today's Progress**: Fixed scrolling bug on Safari. But failed to fix the same one on iOS Chrome.

**Thoughts**: I think I've spent too much time trying non-sense options without digging deep to the problem. A failed day or a tried-hard day.

**Link(s) to work**: [Erik's Github Page](http://eriknguyen.github.io/)

### Day 3: Jan 05, 2017
##### 

**Today's Progress**: Joined Javascript30 Challenge to refresh vanilla JS foundation. Finished day 1.

**Thoughts**: Simple exercise to start new challenge and to relax but still building coding habit. Practised some ES6 (back text, template string, arrow function), browser events and sound element.

**Link(s) to work**: [JavaScript30#1](https://github.com/eriknguyen/javascript30/tree/master/exercises/01_drumkit)

### Day 4: Jan 06, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 2: build an analog clock.

**Thoughts**: #TGIF. Another simple exercise to relax after a busy week and busy Friday. Used: JS Date api, ES6 template string.

**Link(s) to work**: [JavaScript30#2](https://github.com/eriknguyen/javascript30/tree/master/exercises/02_clock)


### Day 5: Jan 08, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 3: Practise CSS variables and 

**Thoughts**: Some useful stuffs: css variables, css ":root", dataset for html data attributes (with "data-" prefix) and a badass color #BADA55 LOL

**Link(s) to work**: [JavaScript30#3](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 6: Jan 09, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 4+5: JS Array Cardio + Created Flex Panel Gallery

**Thoughts**: 
1. JS Array Cardio: Learnt many useful stuffs: filter, map, sort, reduce... I wonder how fast I would implement all my function with these. Don't know why I have always been doing it the long way.

2. Flex Panel Gallery: Used flexbox to build a flex panel gallery. I've never used flexbox before as well and may consider to start playing with it since it's very useful and hopefully it will be fully supported by Edge in near future.


**Link(s) to work**: [JavaScript30#45](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 7: Jan 10, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 6: JS Input Auto Suggestion

**Thoughts**: Learnt a few new ES6 stuffs today which includes: fetch, promise, funny syntax of spread function (...) and continues practising some useful stuffs like JS regex, back text, and array methods. Well, the more I learnt the more stupid I feel and the bigger and more interesting JS world I can see. Need to work harder to be better at this language.


**Link(s) to work**: [JavaScript30#6](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 8: Jan 11, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 7+8: JS Array Cardio#2 and HTML5 Canvas

**Thoughts**: Practised some other useful Array methods, I'm gonna need to note it all down and check out more from the MDN, browser compatibility would be the problem of some. For HTML5 Canvas, it's kinda fun exercises while playing around with canvas 2d context, it's relatively easy since I'm working on some WebGL stuffs to build an online interior design tools.


**Link(s) to work**: [JavaScript30#7+8](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 9: Jan 12, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 9+10: Learnt some cool dev tool tricks and built the shift-holding checkboxes check

**Thoughts**: Yes, those are some very cool dev tools and it will be the start for me to check out more tutorials on utilizing the dev tool that Addy Osmani has tweeted a lots about :D They work so hard to build it and to ease the pain for fellow developers so it would be disrespectful and be the shame for me not to use it the smart way. 

For day 10 of the series, I built the shift-holding check function for a checkboxes list with a slightly different method than what Wes Bos used and it's kinda more ugly though. Btw, there is still a new thing which is a e.shiftKey @@ I've always using e.keyCode === 16 with a keydown event for that simple task. Well....


**Link(s) to work**: [JavaScript30#9+10](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 10: Jan 14, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 11: Build custom video player

**Thoughts**: Yes, I've skipped one day on Jan 13. I just couldn't make it since I was too tired after the whole day working. So I think I'll break the rule abit. And I will be fined 5 extra days for any single day that I skip. So at least there would be some more flexibility now with trade off.


**Link(s) to work**: [JavaScript30#11](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 11: Jan 15, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 12: Very relaxing piece of code about key sequence detection

**Thoughts**: But it's kinda cool trick...


**Link(s) to work**: [JavaScript30#12](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 12: Jan 16, 2017
##### 

**Today's Progress**: Completed Javascript30 Day 13: Slide in effect for page scrolling

**Thoughts**: Practising some JS events and classList manipulation to create the sliding in effect for images when page scrolling. Nothing much except that for today's session, I welcome my new coding buddy and put him into action. Getting started with Mac OS and I'll try to get some benefit in knowledge (and money maybe lol) from this big investment!!!


**Link(s) to work**: [JavaScript30#13](https://github.com/eriknguyen/javascript30/tree/master/exercises/)



### Day 13: Jan 17, 2017
##### 

**Today's Progress**: JS30 Day 14 JS References vs Copying

**Thoughts**: Well, today I'm learning something that is very basic and I continue to question myself on why I didn't know this before... That's really strange!

So a quick recap: it's about references and copying. Copying is used in most of the simple type (string, numbers, boolean) where the assignment expression creates new variable and value. Array & object assignment use reference => the new array/object is just another reference to the same original one, everything that was changed from the newly created array/object will be reflected to the original one because they actually point to the same object. There are multiple ways to create a "actually new" (~copy) array/object which was listed below. Those must be noted.
* Array: 
	* `slide()`: `const arr2 = arr1.slide()` will copy arr2 to new arr1
	* `concat()`: `const arr2 = [].concat(arr1)` create new arr2 and concat arr1 in
	* ES6 Spread: `const arr2 = [...arr1]`
	* `Array.from()`: `const arr2 = Array.from(arr1)`
* Object:
	* `Object.assign()`: `const obj2 = Object.assign({}, obj1, {/*update property here*/})`, this is only 1 level deep, can search for JS deep clone method (eg. lodash)
	* JSON poor hack: `const obj2 = JSON.parse(JSON.stringify(obj1))` convert obj1 to string and parse string to obj2


**Link(s) to work**: [JavaScript30#14](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 14: Jan 18, 2017
##### 

**Today's Progress**: JS30 Day 15 Local Storage and Event Delegation

**Thoughts**:
* Some things to remember:
	* Use `Preserve Log` in Chrome DevTool to save log when page refresh
	* Use default value when creating function as fallback for invalid input

* Recap:
	* Array `map()`
	* Event delegation: listen for an event on a "parent" element then check if the event target is the correct element that we want


**Link(s) to work**: [JavaScript30#14](https://github.com/eriknguyen/javascript30/tree/master/exercises/)


### Day 15: Jan 17, 2017
##### 

**Today's Progress**: Setting up my dev env on my new coding buddy

**Thoughts**:
* I think this might take much longer with a Windows machine considering if I'm used to Mac OS:-?
	* Setting sublime text (get it to run from terminal, install frequently used packages and their settings, UI settings)
	* Install node, python3, pip3, virtualenv, MySQL (stuck here for very long) @@, gulp and other packages
	* `git clone` some of the current project that I'll be working on


**Link(s) to work**: [JavaScript30#15](https://github.com/eriknguyen/javascript30/tree/master/exercises/)