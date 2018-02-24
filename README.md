# tinker-pad
A place to collect some ideas for a collaborative software project, from mildly megalomaniac to plain and pragmatic

## Project Ideas
Maglomaniac:
	
- modernize "Plan The Jam" (but not now): we could use the standard backend first and then set up
a react native interface and focus on frontend development. we could use redux and graph ql to throw 
in new technologies. nice could be to implement pure LSD ideas, an interface that is just completely crazy
and flashy. my vision for a band management system would be that besides finding dates one could even manage
jam recordings, etc which brings me to a new idea:

- Cut the Jam Sound (or similliar)
Sratchpad for musicians, everyone records songs on their devices, these songs can be annotated to mark cool fragments,
new ideas can be recorded at home - find some way to make the whole composing by ear process cool and avoid 
the "dude what did we play last time, where was the cool part in the recording" thing. 

- maglomaniac to the max: form a cult to completely work through all books of knuths "the art of computer programming" 
(may take 40 years to complete)

Less crazy:

- implement some standard algorithms in a well-known/new/dreaded/loved/hyped programming language:
standard sorting algorithms to get started, like a self made cookbook then:
focus on graph algorithms: implement depth-first search which should find the shortest path in a maze.
here a nice motivation could be to apply the graph algorithm: PacMan comes to mind directly. I have a self written pacman
we could try to make those monster chase the hell out of pacman: https://github.com/simonlischka/dsl_pacman
also, port to ScalaJS 

- build a web crawler with Go (focussing on its abilities for parallel computing). For ex. give me info on my favourite bars, 
crawl different web site formats with different extractors, eventually persist to db, connect a flask app to crank up a simple
website, have it running in two docker container (just dropping known keywords here). Flask web app would communicate 
with go app over simple rest api. 


## Tech List
- [GoLang](https://golang.org/)
- [Clojure](https://clojure.org/)
- [Haskell](https://www.haskell.org/)
- [ReactNative](http://facebook.github.io/react-native/)
- [GraphQL](http://graphql.org/learn/)
- [Kotlin](https://kotlinlang.org/ "woohoo!") a Scala-like language targeting the JVM, Android, JavaScript or even native binaries (!) with out-of-the-box support from IntelliJ
- [Vavr](http://www.vavr.io/) a library to provide Scala features for Java
- [Flask](http://flask.pocoo.org/) a microframework for web development with Python
- [RxJava](https://github.com/ReactiveX/RxJava) a reactive library that brings ReactiveX to Java
- [RxScala](http://reactivex.io/rxscala/) a reactive library that brings ReactiveX to Scala 
- [Scala.Rx](https://github.com/lihaoyi/scala.rx) another reactive library for Scala (by Li Haoyi)
- [Scala.js](https://www.scala-js.org/) Scala in the browser - we know and love it
- [Jigsaw](http://openjdk.java.net/projects/jigsaw/) Java's brand new module system
- [Redis](https://redis.io/) a fast in-memory database
- [Docker](https://www.docker.com/) something hyped with containers instead of VMs
- [Raspberry Pi](https://www.raspberrypi.org/) a small and cheap computer
- [Spring](https://spring.io/) hic sunt leones
