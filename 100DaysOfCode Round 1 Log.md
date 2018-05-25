<h1 align = "center">100DaysOfCode Log</h1>
<img src = "https://cdn.pixabay.com/photo/2017/06/23/10/48/code-2434271_960_720.jpg">
<h2>Day 1 - 30 (31 Jan. - 1st Mar. 2018)</h2>

**Summary of Progress**: Completed Basic HTML5, CSS, jQuery and some Javascript.</b>
**Projects:** Completed my Tribute page, Personal Portfolio Site and a Medium Article on 30th day uninterrupted progresss.<br/>
**Link to Tribute page:** (https://codepen.io/Zappy555/pen/xYRjZY)<br/>
**Link to Portfolio page:** (https://codepen.io/Zappy555/pen/yvKoWz)<br/>

------------------------------------------------------------------------

<h3>Day 31: March 2nd, 2018</h3>

**Today's Progress**: I covered 19 challenges in JavaScript including arrays, nested arrays, functions and loops.

**Thoughts:** On some of the challenges such as if/else, I had to use the hint on FCC to check the solution.

------------------------------------------------------------------------
<h3>Day 32: March 3rd, 2018</h3>

**Today's Progress**: More and more reading of the Eloquent Javascript. Did a few challenges on FCC.

**Thoughts**: Will keep on keeping on...

------------------------------------------------------------------------
<h3>Day 33: March 4th, 2018</h3>

**Today's Progress**: Tried a few more challenges on Codecademy JS lectures. Also downloaded VELOCITY App, an awesome tool containing a HUGE reference/documentation repository of some 150+ current programming languages. 

**Thoughts**: Still trying to wrap my head around control structure in JS. Getting there slowly though.

------------------------------------------------------------------------
<h3>Day 34 - 35: March 5th and 6th, 2018</h3>

**Today's Progress**: I re-read chapters 1 & 2 of Eloquent JavaScript and tackled the challenges (Triangle, FizzBuzz and Chessboard programs) at the end of chapter 2 as follows:

----------------------------------------------------
	Eloquent JS Challenge 1: Looping a Triangle
	----------------------------------------------------
	Write a loop that makes seven calls to console.log to output the following triangle:
		#
		##
		###
		41
		####
		#####
		######
		#######
		
		Soln:
		let triangle = " ";
		let counter = 0;
			while(triangle.length <= 8){
				triangle = triangle + "#";
				console.log(triangle);
			}
	----------------------------------------
	Eloquent JS Challenge 2: FizzBuzz
	----------------------------------------
	/*Write a program that uses console.log to print all the numbers from 1 to 100, with two exceptions. 
	 * For numbers divisible by 3, print "Fizz"   instead of the number, and 
	 * for numbers divisible by 5 (and not 3), print "Buzz" instead.
	
	Soln:
		for(let num = 0; num <= 100; num++){
		if(num % 3 == 0){
			console.log("Fizz");
		}else if(num % 5 == 0 && num % 3 != 0){
			console.log("Buzz");
		}else{
			console.log(num);
		}
	}
	 
	 * When you have that working, modify your program to print "FizzBuzz", 
	 * for numbers that are divisible by both 3 and 5 (and still print "Fizz" Or "Buzz" 
	 * for numbers divisible by only one of those).
	 *
	Soln:
		for(let num = 0; num <= 100; num++){
		if(num % 3 == 0 && !(num % 5 * 3 == 0)){
			console.log("Fizz");
		}else if(num % 5 == 0 && !(num % 3 * 5 == 0)){
			console.log("Buzz");
		}else if(num % 3 == 0 && num % 5 == 0){
			console.log("FizzBuzz");
		}else{
			console.log(num);
		}
	}
	 * (This is actually an interview question that has been claimed to weed
	 * out a significant percentage of programmer candidates. So if you solved
	 * it, your labor market value just went up.)
	 */

**Thoughts**: I finally understood better the uses and functions of conditional (if, else, and switch) and looping (while,
do, and for) statements and how to declare them properly. I also discovered that a good night rest would result in better a programmer than endless hours of sleepy and tired eyes glued to the computer screen.

**Link to Tweet** https://twitter.com/porobe/status/971285996535939072



------------------------------------------------------------------------
<h3>Day 36 - 39: March 7th - 10th, 2018</h3>

**Progress**: I read and re-read chapters 3 of Eloquent JavaScript, practicing how to create functions, learned the scope of the <b>var</b> and <b>let</b> variables, learned how to pass a function as value, create function within function and practiced object creation on FCC and how to create, access and delete object properties. 


------------------------------------------------------------------------
<h3>Day 40 - 46: March 11th - 18th, 2018</h3>

**Progress**: I completed  the Object Oriented and Functional Programming session on Free Code Camp and tackled some basic algorithm challenges such as: Reverse Str, factorialize num, check for palindromes, longest word, title case sentence, largest num in Arrays and confirm the ending etc. https://media2.giphy.com/media/5bJQBg4HGkGYM/giphy.gif
	
------------------------------------------------------------------------
<h3>Day 47 - 49: March 19th - 21st, 2018</h3>

**Progress**: I completed  three more basic algorithm challenges on FCC viz; <br>

1. Truncate a string <br>		
2. Chunky Monkey <br>		
3. Slasher Flick <br>

**Link to Tweet** Didn't tweet

------------------------------------------------------------------------
<h3>Day 50: March 22nd, 2018</h3>

<img style = "text-align: center, width: 100%" src = "https://www.healthysystem.in/wp-content/uploads/2016/08/Half-way-done.jpg">

Half-way down this path in round one, it's been both exciting and discouraging at the same time. I have struggled to grasp some of the concepts in the Basic Algorithm Scripting on FreeCodeCamp. 

**Summary of Progress** I completed 3 of the algorithms on FCC namely: **Mutation, Falsy Bouncer, and Where do I Belong,** and in the process understood more about the:
1. **The string Object method - indexOf -** which returns the index of a specified string in a set of string values declared thus:
   	"The Quick Brown Fox Jumped Over The Lazy Dog".indexOf("Jumped"); // This returns the index of the word 'jumped' - a number.
2. **Boolean Object** This one was a little tricky for me as I tried to fully understand its application as different from the primitive boolean values true and false. I came to understand however that there are only six(6) types of falsy values in JavaScript:  **false, null, 0, "", undefined, and NaN.** Thus doing this: arr.filter(Boolean); filters all falsy values from a set of string passed to the array. This can be used to check the validity of form inputs such as email addresses etc.

**Link to Tweet:** https://twitter.com/porobe/status/976779166971584513

------------------------------------------------------------------------
<h3>Day 51 & 52: March 23rd and 24th, 2018</h3>

**Summary of Progress**: I completed two of the last challenges left of the Basic Algorithm Scripting on FCC, completed the JSON APIs and Ajax section of FCC and as a complement I completed the Basic Javascript section on CodeCademy . I learnt:<br>
How to trigger click events with jQuery, how to Get JSON with jQuery getJSON method, how to Convert JSON to HTML etc.
		
**Things got a bit clear now that the whole pieces are coming together.**
**Link to tweet:** https://twitter.com/porobe/status/977368052269568000

------------------------------------------------------------------------
<h3>Days 53 - 57: March 25th-29th, 2018</h3>

**Summary of Progress**: 
I completed the Random Quote Machine Project on FCC <br>
**Link to project**: https://codepen.io/Zappy555/pen/oqpzEZ<br>

I bought a personal domain in my name for my public profile where I can collect all my works and talk more openly about my interest<br>
**Link to personal website:** www.alexporobe.com<br>

I learnt some more about Ajax, jQuery deprecated and newer classes in jQuery 3, API calls etc
**Link to tweet:** https://twitter.com/porobe/status/979133442628771840

------------------------------------------------------------------------
<h3>Days 58 - 61: March 30th - April 2nd 2018</h3>

**Summary of Progress**: 
Read the book series "You Don't Know Javascript - Up and Going" <br>
Tried to pair programme for the first time on my "Show the Local weather app" on FCC and learnt more about Teamviewer.<br>
Worked more on a side project of developing a website for startup firm that has been lingering for a while now.<br>

------------------------------------------------------------------------
<h3>Days 62 - 64: April 3rd - 5th 2018</h3>

**Summary of Progress**: 
Still digging on with my show the local weather app and my side project
Completed week 0 lecture on CS50 - Intro. to computer science.

------------------------------------------------------------------------
<h3>Days 65 - 71: April 6th - 12th 2018</h3>

**Summary of Progress**: 
1. I completed my "Show the Local Weather App" on FreeCodeCamp
This project was about the mar my zeal in the entire journey. It was so challenging wrapping my head around how to make simple API calls even when I have used an API in the "Random Quote Machine App". I was simply at a loss on how to commence the project after the HTML and CSS components. After about 4 youtube videos and countless samples of other campers work, It began to sink in gradually. Not that it was such difficult project in itself.

I also worked on my website side project to some 80% completion.

**Link to Local Weather App Project**<br>
https://codepen.io/Zappy555/pen/XEwKxg

Build a Wikipedia Viewer up next.

------------------------------------------------------------------------
<h3>Days 72 - 84: April 13th - 25th 2018</h3>

**Summary of Progress**: 
1. I needed to get grounded in Javascript concepts and so immersed myself in reading up with the YDKJS book series and some more chapters in Eloquent Javascript.
2. I made significant improvement on my portfolio site www.alexporobe.com and added a blog
3. I initiated the Wikipedia viewer project but not completed yet.
4. I got accepted into the Chingu May Cohort 

It's been a real struggle to get JS into my head but gradually things are improving.


------------------------------------------------------------------------
<h3>Days 85 - 97: April 26th - May 9th 2018</h3>

**Summary of Progress**: 

<img src="https://pbs.twimg.com/media/DcOdY-OX0AEUQ-W.jpg:large"> <br>

1. I Got accepted into the Google-Udacity-Andela Web-Dev-Front-End Nano Degree Programme for Africa
2. I Downloaded and completed Git using GitHub Tutorial using Git Bash CLI
3. I Solved challenges on HTML and CSS into lesson 6 of the programme
4. Initiated a pet dream project on StartHops

