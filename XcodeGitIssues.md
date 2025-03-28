# Xcode not Allowing Git Updates
## What?
Yeah, I know, the great Apple failed, in my opinion big time. I recently went to attempt a tutorial on how to use a rapsberry pi pico and I couldn't even run the code on Visaul Studio Code. The error I received was that my Git was not up to date. At the time of writing this Git is at version 2.49.0, but I was running 2.15.0. I had installed the Xcode Command Line Tools package a while back and assumed it would jut auto update. Nope! In fact, not only does it not auto update, but it does not update at all. Apple has a way to search for Xcode CLT updates, but each time I used that command (softwareupdate --install <product name>) it never found any updates. Well, this was obviously a huge flaw in Apple's design, but it had to be fixed.

## The Fix
I would first start by checking your version of Git: ''' git --version '''
