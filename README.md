# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**
* Like this:
* **Jackie Cohen (jczetta)**
* Yea-Ree Chang (cyearee)
* Ruchi Ookalkar (ruchido)
* Innocent Obi (innoobi)
* Zhen Wang (alejwang)
* etc.

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

Commenting out in JavaScript may be coded as follows:

```js
// INSERT COMMENT
```

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

It appears by simply clicking on the html files will render/run the code in a web browser, demonstrating the viewable results of the code.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

There appears to be two kinds of 'print functions' that occur in javascript. The first appears to be the alert way, which is shown as follows:
```js
alert("hello");
```
The second appears to be the console.log method which appears as follows:
```js
console.log("hello in console");
```
While both allow for output to be shown, console.log may be helpful when looking at the inspect/web developer view in the web browser. While the alert way seems to render output in the popup window.

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

It appears that the alert function in line 12
```js
alert("hello");
```
would be responsible for the pop up box. Commenting that line out appears to remove the pop-up window. TO build a pop-up with the dat and the time, the following code appears to do this task:
```js
alert(new Date())
```
Please note that in order for these changes to be applied the page much be refreshed.

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

The function starting in line 16 provides a subsequent line that is as follows:
```js
document.querySelector('h1').innerHTML = "A Name";
```
Changing this line by editing the "A Name" in quotes within the function will allow the text to be changed in this case, I will change A Name to Monica Pagani, as such:
```js
document.querySelector('h1').innerHTML = "Monica Pagani";
```
Please note that in order for these changes to be applied the page much be refreshed.

* **What does the word `document` represent in this code? Explain briefly.**

The word document appears first n line 17. It seems to be referenced in a similar what to an object/self in a class definition. Within this code document appears to have methods applied to in in a similar way to an object.  

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

The above line of code reads all the tags within the html. Specifically, the querySelector() method returns the first element that matches a specified CSS selector of an element. Additionally getElementsByTagName() returns a collection of an elements's child elements with the associated tag name. This occurs as a NodeList object.

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

In line 22 the code as follows appears responsible for setting the visible lime green background.
```js
body.style.background = "#CCEE00";
```
When commenting this line out and refreshing the page, the background appears white.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

The text box that originally appear in grey are associated with the color and boarder specifications occurring in line 38-42. To change the color to blue, you can adjust the background specifications as follows:
```js
background-color: #3399ff;
// green #b3b3b3
// blue  #3399ff
```

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

In order to get a text pop-up when hovering over the text McGill University, I did some googling in order to find out what the proper terminology was for that instance. I first read about things like tooltip and mouseover. After some reading, I made the following changes in order to get the Oh, Canada text to hover over McGill.
```js
<li><div title="O Canada">McGill University</div></li>
```

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**

```js
function handleClick(){
	alert("hello");
}
```
There appears to be a function defined such that when something is clicked the hello text pop-up is rendered as demonstrated by the above code.

**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```
In this block of code it appears that the function is applied to the instance of the wow button such that the button's onclick variable has a value of the above function. Simply put, when the wow button is clicked, the handleClick() function is run, and the alert('hello') is rendered via the text pop-up.

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**

The follow code is associated with the Spring Equinox button per the specifications of the problem. It may also be found in the code.

```js
function springClick(){
	alert("March 20, 2019");
}
```
.
.
.
```js
<button onclick=springClick() id="spring-button">Spring Equinox 2019</button>
```

### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

It appears that the code contains the specifications for errors to appear in red and valid input to appear in blue based on the following code specifications for text style:
```js
<style type="text/css">
    .error{
        color: red;
    }
    .good {
        color: blue;
    }
```

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

This statement is associated with regular expression term. For the purposes of this example, it appears to include all alphabetical letters (lower and upper case) text. I did not do any substantial researching to provide the above answer.

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**

It appears that the following code is a working example of conditional statements in javascript:
```js
if(regex.test(currentValue) == false){
		$("#result").html('<p class="error">Not valid!</p>').show().fadeOut(10000);
		// Preventing form submission
		event.preventDefault();
} else {
		$("#result").html('<p class="good">Nice!</p>').show().fadeOut(10000);
}
```
While there does appear to be some noticeable differences in syntax, overall structure appears quite similar. In both python and javascript cases the if and else conditional statements are followed by the indented actionable code. One contrast appears to be the use of {} brackets to break up the if and else conditional statements.

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**

I would guess the fadeout specifies the number of milliseconds that it takes the "Not valid!" text to fade away when invalid input is submitted in the text box.

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

```js
$(document).ready(function()
$("form").submit(function(event)
```

To me it seems as though this code works to first prepare the document and then applies a function for the purposes of the form. In the second line it seems as though the function is invoked on the submission via the function(event) part.


* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
