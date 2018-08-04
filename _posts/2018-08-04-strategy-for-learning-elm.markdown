# Self learning note for elm

Learning elm is probably not going to happend in a weekend. It probably will take me couple of weeks until I become productive in it. Another problem is to get an interesting project to started with. So this is why starting with a motivation note will keeps reminds me the reason I should keep going.

### Motivation

I need to eventually learn elm. Perios. This is a good long term tech investment. Because so far, it promises several things:

* No runtime error. Imagine how much time is wasted to hunt down the javascript bug. This alone must be enough reason, actually.
* It is easier to maintain, easier to write, and easier to scale.
* It promise happiness, and this is usually always leads to productivity.


### Drawback 

I write this part so I can revisit and probably delete it once I got better knowledge about ELM.

* How to use existing html template and make it come to live, fast?
* How easy to deploy and integrate with existing project?

### Learning Strategy

1. Know general concept of elm. Just read and skim many review, beginner tutorial, official get start and videos until it sinked in.
2. Know that there are two ways of starting elm. By elm-reactor to prototype things and using web pack for real deployment plan.
3. Understand that everything is actually a function. Elm architechture is just bunch of function, constant is function, etc. It is conceptually simple.
4. Remember that the confusing part is most of the time is because of unclear vocabulary. So gather understanding of as much concept and vocabulary before understanding the logic and how everything tied together.
5. Build something using elm-reactor
6. Build something using webpack, a.k.a the real way
7. Learn how to add style, remove class and add class.
8. Learn how to incorporate with existing stylesheet.
9. Learn how to use bootstrap css only.
10. Create mastermind as initial project.


## Start Fast

### Installation
	
Elm can be installed trough NPM but better install as the official docs suggested which is using installer from `http://elm-lang.org/install`

### Start project

1. Run starter

		elm-package install elm-lang/html
		
2. Hello world
	Put a file with arbitrary name: `foo.elm`
	
	```
	module Hello exposing (..)
	
	import Html exposing (text)
	
	
	main =
	    text "Hello"
	```
3. Run `elm reactor`

### Deployment
We have 2 option: 

1. Compile as HTML which can run on its own
2. Compile as javascript which can be embed inside existing html div, treat it as a component.

### The Elm Language

#### Function

Regular function with anotation and take 2 arguments

	add : Int -> Int -> Int
	add x y =
	  x + y
	  
Anonymous function which takes 2 arguments

	\x y -> x + y
	
Funtion with no argument = constant

	name = "sam"
	

It support piping function!

	3
    |> multiply 2
    |> add 1
    
 
 
To be continued