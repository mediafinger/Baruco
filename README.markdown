# Baruco 2012 - Barcelona

Conference notes by [Andreas Finger](http://mediafinger.com) [@mediafinger](http://www.twitter.com/@mediafinger)

## Day 1
1. [Keynote: Back to First Principles](https://github.com/mediafinger/Baruco#scott-chacon-chacon)
2. [Rubymotion for faster Client/Server Development](https://github.com/mediafinger/Baruco#randall-thomas-daksis--tammer-saleh-tsaleh)
3. [Uniformity ain't all bad: getting Consistent Behavior across your API](https://github.com/mediafinger/Baruco#alex-koppel-arsduo)
4. [Deconstructing the Framework](https://github.com/mediafinger/Baruco#gary-bernhardt-garybernhardt)
5. [Life beyond HTTP](https://github.com/mediafinger/Baruco#anthony-eden-aeden)
6. [Programming Workout](https://github.com/mediafinger/Baruco#micha%C5%82-taszycki-mehowte)
7. [Tracing your way through Ruby](https://github.com/mediafinger/Baruco#elise-huard-elise_huard)
8. [Why Agile (a short History of Software Engineering, and other Ideas that didn't work)](https://github.com/mediafinger/Baruco#paolo-perrotta-nusco)
9. [Lightning Talks](https://github.com/mediafinger/Baruco#lightning-talks)

## Day 2
1. [Keynote: The Top 10 Ways to Scam the Modern American Programmer](https://github.com/mediafinger/Baruco#zed-a-shaw-zedshaw)
2. [Grand Unification Theory: Writing and running Code](day_2_2)
3. [Constant Autoloading in Ruby on Rails](day_2_3)
4. [Message in a Bottle](day_2_4)
5. [Micro-Service Architecture](day_2_5)
6. [It's not how good your app is, it's how good you want it to be](day_2_6)
7. [Rubinius - Tales from the Trenches of Developing a Ruby Implementation](day_2_7)
8. [Unsucking Your Team's Development Environment](day_2_8)


## Saturday


### Scott Chacon [@chacon](http://www.twitter.com/chacon)
#### KEYNOTE: BACK TO FIRST PRINCIPLES
[Baruco Page](http://baruco.org/agenda/keynote-back-to-first-principles)

* Disrupt industries with software - and take over the world.
* *Let frustration guide you.*
* first principles ~= basic, foundational proposition
* re-imagine everything
    * workplace
    * work-time
    * communication
    * hiring
    * office
    * meetings
    * managers
    * vacation
    * long hours
    * expense reports
* what functions of managers are helpful for the organization - and can you do that in software?
* groups will handle problems and find solutions.
* the future: well led networks instead of well managed companies.

***

### Randall Thomas [@daksis](http://www.twitter.com/daksis) & Tammer Saleh [@tsaleh](http://www.twitter.com/tsaleh)
#### RUBYMOTION FOR FASTER CLIENT/SERVER DEVELOPMENT
[Baruco Page](http://baruco.org/agenda/rubymotion-for-faster-client-server-development)

* Why use RubyMotion - instead of Objective-C?
* Is it worth handling with RubyMotion?
* What is broken in RubyMotion?

Summary: RubyMotion might be fine for small projects - but risky to use for larger ones.

***

### Alex Koppel [@arsduo](http://www.twitter.com/arsduo)
#### UNIFORMITY AIN'T ALL BAD: GETTING CONSISTENT BEHAVIOR ACROSS YOUR API
[Baruco Page](http://baruco.org/agenda/uniformity-ain-t-all-bad-getting-consistent-behavior-across-your-api)

* APIs should work by the 'principle of least surprise'
    * uniform pattern
    * consistent naming
    * consistent parameter formatting
* return expected responses
* return error messages
* change is tricky - so do it right in the beginning
* receive consistent data through standard scopes
* send different datasets to different devices
* keep authorization in mind
* try to simplify - only serve JSON for example
* process batch calls as regular calls (or use HTTP pipelining)
* become your first consumer - to check your API
* define and document all your API behaviour

***

### Gary Bernhardt [@garybernhardt](http://www.twitter.com/garybernhardt)
#### DECONSTRUCTING THE FRAMEWORK
[Baruco Page](http://baruco.org/agenda/deconstructing-the-framework)

* 1/5 Test in the small
    * decoupling
* 2/5 Service Wrapper Record
    * wrap functionality your own (tiny) methods
* 3/5 The Squishing Rule
    * obey to the SRP, also for Controllers - a class should have one and ONLY ONE reason to change
* 4/5 Decomposing MVC - or what parts are in a (fat) Controller
* 5/5 The Raptor Framework
    * Stateless Services & Simple 3rd Party Wrappers -insulated from- Rails and (simple) Records

***

### Anthony Eden [@aeden](http://www.twitter.com/aeden)
#### LIFE BEYOND HTTP
[Baruco Page](http://baruco.org/agenda/life-beyond-http)

* *Protocols are a set of procedureds to be followed when communicating*
* SMTP...HTTP...DNS...XMPP...SPDY...TCP...UPD
* Coding examples


***

### Michał Taszycki [@mehowte](http://www.twitter.com/mehowte)
#### PROGRAMMING WORKOUT
[Baruco Page](http://baruco.org/agenda/programming-workout)

Train and repeat your skills dojo style.

*Did not attend - saw it @ Euruko in Amsterdam*

***

### Elise Huard [@elise_huard](http://www.twitter.com/elise_huard)
#### TRACING YOUR WAY THROUGH RUBY
[Baruco Page](http://baruco.org/agenda/tracing-your-way-through-ruby)

*Did not attend - enjoyed the CosmoCaixa Museum*

***

### Paolo Perrotta [@nusco](http://www.twitter.com/nusco)
#### WHY AGILE (A SHORT HISTORY OF SOFTWARE ENGINEERING, AND OTHER IDEAS THAT DIDN'T WORK)
[Baruco Page](http://baruco.org/agenda/why-agile-a-short-history-of-software-engineering-and-other-ideas-that-didn-t-work)

* Paolo is an agile coach, wrotes Ruby code only at night and keeps it for himself
* His only claim for fame in the ruby community: the book Metaprogramming Ruby (read it, it's great)
* He does more Ruby than Agile Conferences
* Only 4 people in the audience were alive in 1968 ;)
* in 2009 24% of software projects failed (but it's not a crisis, it's the status quo)
* Three sources of problems:
    1. Complexity of source code
        * Solution: eliminate source code, fire all programmers and live happily ever on...
    2. Human imperfection
        * Solution: eliminate human errors (with math, so you need no more tests)
    3. Project variability
        * Solution: turn software craftmanship into industrial engineering
* If you can not eliminate the problems, embrace and handle them through
    1. observation
    2. hypothesises
    3. experiments
* *All good (unique) architecture leaks.*

***

### Lightning talks

* @bryanl - zsh is my rifle
* @albertoperdomo - Graph databases
* @basiszwo - Cloudlist 
* @markoa - Benefits of CI 
* @arcandros - Raiding Software Instances
* @ryanlecompte - Redis Failover (with ZooKeeper)
* @josephwilk - Go (*As soon as a child stops eating the stones, it will beat any grown-up.*)
* @porras - ✓
* @mlainez - Agile Estimating & Planing
* @malditogeek - Astor
* @paolodona - There is hope (for average programmers) 

## Sunday


### Zed A. Shaw [@zedshaw](http://www.twitter.com/zedshaw)
#### KEYNOTE: THE TOP 10 WAYS TO SCAM THE MODERN AMERICAN PROGRAMMER
[Baruco Page](http://baruco.org/agenda/keynote-the-top-10-ways-to-scam-the-modern-american-programmer)

* Only a dick online
* You won't see the Scams, if you're stuck in the 'Community'
* The 'Manifestos' up to 2100 (Monkeys, Aliens, Robots...)
* If You Work For Free We Will All Be Rich - Scam
* Bullying: Gang instead of Team Mentality
* Abstractions should stay readable and close to the actual solution
* *Actively destroying communities, is kind of a hobby.*
* You don't need a process, just be creative and code!

PROGRAMMING, MOTHERFUCKER!

***

### Brian Ford [@brixen](http://www.twitter.com/brixen)
#### GRAND UNIFICATION THEORY: WRITING AND RUNNING CODE [day_2_2]
[Baruco Page](http://baruco.org/agenda/grand-unification-theory-writing-and-running-code)

* In Smalltalk writing code was a function of the running programm
* The Editors we use did not evolve that far in the last 50 years
* Don't obey to tools and process, use them thoughtful
* Communication is most important
    * clear
    * simple
    * relevant
    * precise
    * (medium, tone, safe, open)
* Think of a programming language as the medium for communication
* Some aspects of dynamic typed languages...
* Some Rubinus examples...
* In future versions of Rubinus it should be able to check the compiled program flow

***

### Name [@fxn](http://www.twitter.com/fxn)
#### CONSTANT AUTOLOADING IN RUBY ON RAILS [day_2_3]
[Baruco Page](http://baruco.org/agenda/constant-autoloading-in-ruby-on-rails)

* Explaining how Autoload works in Rails under the hood
* loads of code examples

***

### Konstantin Haase [@konstantinhaase](http://www.twitter.com/konstantinhaase)
#### MESSAGE IN A BOTTLE [day_2_4]
[Baruco Page](http://baruco.org/agenda/message-in-a-bottle)

* There are more than 50 different Ruby implementations
* Comparing some methods of the three largest:
    * MRI: method dispatch
    * Rubinus: inline caches and JIT
    * JRuby: invokeddynamic
* in depth byte code explanation

***

### Fred George [@fgeorge52](http://www.twitter.com/fgeorge52)
#### MICRO-SERVICE ARCHITECTURE [day_2_5]
[Baruco Page](http://baruco.org/agenda/micro-service-architecture)

***

### Josh Kalderimis [@j2h](http://www.twitter.com/j2h)
#### IT'S NOT HOW GOOD YOUR APP IS, IT'S HOW GOOD YOU WANT IT TO BE [day_2_6]
[Baruco Page](http://baruco.org/agenda/it-s-not-how-good-your-app-is-it-s-how-good-you-want-it-to-be)

***

### Dirkjan Bussink [@dbussink](http://www.twitter.com/dbussink)
#### RUBINIUS - TALES FROM THE TRENCHES OF DEVELOPING A RUBY IMPLEMENTATION [day_2_7]
[Baruco Page](http://baruco.org/agenda/rubinius-tales-from-the-trenches-of-developing-a-ruby-implementation)

***

### Zach Holman [@holman](http://www.twitter.com/holman)
#### UNSUCKING YOUR TEAM'S DEVELOPMENT ENVIRONMENT [day_2_8]
[Baruco Page](http://baruco.org/agenda/unsucking-your-team-s-development-environment)
