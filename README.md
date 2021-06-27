# fizzbuzz

Fizz buzz is a group word game for children to teach them about division. Players take turns to count incrementally, replacing any number divisible by three with the word "fizz", and any number divisible by five with the word "buzz". However, any number divisible by three is replaced by the word fizz and any number divisible by five by the word buzz. Numbers divisible by 15 become fizz buzz. A player who hesitates or makes a mistake is eliminated from the game.


# Requirement

In this app, there will be a screen where a random number will appear and player will have 10 seconds to determine whether it's fizz / buzz / fizzbuzz. If number is neither fizz, nor buzz, pass the number.
Screen will have:
1. 1 number which will keep changing.
2. 4 buttons namely fizz, buzz, fizzbuzz and pass
3. 1 10 sec timer.
4. A scoreboard.

score calculation:

Correct Answer:

1. fizz : 5 points
2. buzz : 5 points
3. fizzbuzz : 10 points
4. pass : 2 points

Wrong Answer:
<BR/>
what answer you'll give as wrong, it's positive score will be deducted from final score 
<BR/>
for example: 
<BR/>
if correct answer was fizz, but user answered as fizzbuzz, 10 points will be deducted. 
<BR/>
similarly if correct answer is fizzbuzz and user pressed pass, 2 points will be deducted.

# UX

<img src="https://github.com/Praxinow/android-fizzbuzz/blob/master/ScreenShots/GameScreen.png"/> <img src="https://github.com/Praxinow/android-fizzbuzz/blob/master/ScreenShots/HighestScore.png"/>

Feel free to do experiments

# Concepts to be learned

# Week - 1
- Kotlin
- MVVM
- Live Data
- Room DB
- Fragment and Fragment Navigation
- Coroutine
- Dagger

# Week - 2
- Leak Canary and Framerate -> Memory Leak
- App Launch and frame drop -> Performance Matrix
- ANR and Crash Rate -> Android Vitals
- Benchmarking -> Jetpack/Firebase

# Week - 3
- Unit testing
- Espresso

# Week - 4
- Proguarding

# Helpful Links

Project Architecture Reference :
- https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html [Must]
- https://jeroenmols.com/blog/2019/03/06/modularizationwhy/ [Must]
- https://proandroiddev.com/android-components-architecture-in-a-modular-word-7414a0631969 [Must]
- https://proandroiddev.com/how-to-implement-a-clean-architecture-on-android-2e5e8c8e81fe
- https://www.youtube.com/watch?v=Sy6ZdgqrQp0

MVVM  :
- https://proandroiddev.com/our-way-to-mvvmi-and-mistakes-we-made-when-implementing-mvvm-5f5448b5ad50 [MUST]
- Naming conventional Reference] https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md [Must]
- [Theme conventional  Reference] https://material.io/components/
- https://medium.com/androiddevelopers/android-styling-common-theme-attributes-8f7c50c9eaba [Must]

 Dagger : 
- https://proandroiddev.com/modularization-in-android-architecture-point-of-view-from-a-to-z-part-ii-8baea5b2e4fd [Must]


Deeplink : 
- https://github.com/airbnb/DeepLinkDispatch

Kotlin  :
- https://medium.com/@appmattus/effective-kotlin-31215a6cf847

coroutine :
- https://link.medium.com/vQmK0rv2v3

# Credits
<div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>

