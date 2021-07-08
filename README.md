![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Magic 8 Ball

## Our Goal

The objective of this challenge is to apply the skills you learned in the Dicee tutorial and get you making an app with functionality all by yourself. There’s no new concepts here. But you’re flyin’ solo this time! Most of the programming skills are gained in the challenges rather than the tutorials. It’s when you’re using your new-found programming skills to bend the app to your will that you’re truly levelling up as a developer.

## What you will create

We’re going to make a Magic 8 Ball app. You can ask the app to make all your hard decisions! With this app in your pocket, you’ll always have an answer to life’s many conundrums!



>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
------------------------------------------------------------------------------------------------------------------------------

[![BuddyBuild](https://dashboard.buddybuild.com/api/statusImage?appID=55dd277abbda430100397040&branch=master&build=latest)](https://dashboard.buddybuild.com/apps/55dd277abbda430100397040/build/latest)

# FlappySwift

An implementation of Flappy Bird in Swift for iOS 8.

![FlappySwift](http://i.imgur.com/1NLoToU.gif)

# Notes

We're launching a course [Game Programming with Swift](https://fullstackedu.com)

If you are interested in early access to the course, head to [fullstackedu.com](https://www.fullstackedu.com) and _enter in your email in the signup box at the bottom of the page_ to be notified of updates on the course itself.

# Authors

- Nate Murray - [@eigenjoy](https://twitter.com/eigenjoy)
- Ari Lerner - [@auser](https://twitter.com/auser)
- Based on code by [Matthias Gall](http://digitalbreed.com/2014/how-to-build-a-game-like-flappy-bird-with-xcode-and-sprite-kit)

------------------------------------------------------------------------------------------------------------------------------
![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Xylophone

## Our Goal

The goal of this tutorial is to dive into a simple iOS recipe - how to play sound and use an Apple library called AVFoundation. The most important skill of a great programmer is being able to solve your own problems. We’ll do that by exploring StackOverflow, Apple Documentation and learning how to search for solutions effectively. By learning to use these tools, you’ll be able to start adding custom features to an app and get it to do what you want it to.


## What you will create

You will be making your first musical instrument! Music apps are so popular on the App Store that they even get their own category. So in this module, we’re going to make a colourful XyloPhone app. Get it? Ok, the jokes are bad, but remember, I only wrote the good ones... 

## What you will learn

* How to play sound using AVFoundation and AVAudioPlayer.
* Understand Apple documentation and how to use StackOverflow.
* Functions and methods in Swift. 
* Data types.
* Swift loops.
* Variable scope.
* The ViewController lifecycle.
* Error handling in Swift.
* Code refactoring.
* Basic debugging.

## Replacement Code

```
import UIKit
import AVFoundation

class ViewController: UIViewController {
    
    var player: AVAudioPlayer!

    override func viewDidLoad() {
        super.viewDidLoad()
    }

    @IBAction func keyPressed(_ sender: UIButton) {
        playSound()
    }
    
    func playSound() {
        let url = Bundle.main.url(forResource: "C", withExtension: "wav")
        player = try! AVAudioPlayer(contentsOf: url!)
        player.play()
                
    }
}
```



>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)


