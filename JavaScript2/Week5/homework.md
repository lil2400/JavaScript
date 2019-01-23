## Homework Week 5

## So why this homework?
We want you to realise that functions are just variables in javascript. It is exactly the same as string or a number. This homework forces you into using functions in weird ways that forces you to think differently about functions. 


## Warmup

The warmup is a little abstract, it will get more concrete later on!

1. Log out the text `Called after 2.5 seconds` after 2.5 seconds 
1. Create a function that takes 2 parameters: `timeToWait` and `stringToLog`. Calling this function should log out the `stringToLog` after `timeToWait` seconds. Call the function you have created with some different arguments. 
1. Create a button in html. When clicking this button, use the function you created in the previous task to log out the text: `3.5 seconds after button is clicked` 3.5 seconds after the button is clicked.
1. Create two functions and assign them to two variables. One function logs out `Hello World`, the other function logs out `Hello Universe`. Now create a new function (outer) that has one parameter: `logFunction`. The only thing this new function should do is call the provided parameter function. Try call the outer function with different arguments, once with the `hello world` function and once with the `Hello universe` function.
1. Create a button with the text called "Log location". When this button is clicked the location (latitude, longitude) on the user should be logged out using this [browser api](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) 
1. *Optional* Now show that location on a map using fx the [Google maps api]( https://developers.google.com/maps/documentation/javascript/tutorial)
1. Create a function called `runAfterDelay`. It has two parameters: `delay` and `callback`. When called the function should wait `delay` seconds and then call the provided callback function. Try and call this function with different delays and different callback functions
1. Check if we have double clicked on the page. A double click is defined by two clicks within 0.5 seconds. 
1. Create a function called `jokeCreator` that has three parameters: `shouldTellFunnyJoke`, `logFunnyJoke` and `logBadJoke`. If you set `tellFunnyJoke` to `true` it should call the `logFunnyJoke` that should log out a funny joke. And vice versa.

### Function as a variable
Create funtions that are used in these different ways:

- Create an array with 3 items. All items should be functions. Go through the array and call them.
- Create a function as a const and try creating a function normally. Call both function.
- Create an object that has a key whose value is a function. Try calling this function.
- Create two setTimeouts one uses a function that is defined as a const. The other uses an anonomous function that is defined inside the setTimeout.
- Create a function (outer) that returns a function (inner). Call the outer function and assign the return to a variable. Now call this variable (that is the inner function)


Create a game where there are two buttons. The one that clicks most in a minute wins

## The fastest presser in this realm


In the [homework/hyf-bay folder](homework/hyf-bay) there is a project you should continue working on. So copy all the files into your hyf-homework/Javascript/javascript2/week3 folder and start working in the main.js file. 

## Feedback giving time!
Find a student to give feedback using this site: https://hyf-peer-review.herokuapp.com/
The feedback should be given after the homework has been handed in preferably latest two days after. 

To help you get started we have created some ressources about giving feedback. Find them here: https://github.com/HackYourFuture-CPH/curriculum/tree/master/review

### Hand in Homework:
Go over your homework one last time:
- Does every file run without errors and with the correct results?
- Have you used `const` and `let` and avoided `var`?
- Do the variable, function and argument names you created follow the [Naming Conventions](https://github.com/HackYourFuture/fundamentals/blob/master/fundamentals/naming_conventions.md)?
- Is your code well-formatted (see [Code Formatting](https://github.com/HackYourFuture/fundamentals/blob/master/fundamentals/naming_conventions.md))?

If you can answer yes to the above questions then you are ready to hand if the homework:
* Find the hyf-homework git repo (forked from [here](https://github.com/HackYourFuture-CPH/hyf-homework))
* Add your homework files in the Javascript/javascript2/week2 folder
* To submit the homework use the link in the top of your classes slack channel. 