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

**Link to Twit** https://twitter.com/porobe/status/971285996535939072
