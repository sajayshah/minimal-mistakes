This is the first in a series of blog posts on the numerous projects I've embarked on. I'm not a fan of verbose writing. These posts aim to explain:

 1. Why I did what I did.
 2. Mistakes I made.
 3. The takeaways that made me a better software engineer.

**Anecdote.** I've always been a fan of iOS, lurking on the jailbreak scene since the days of iOS 2.1.2 on my iPod Touch 2G. I still remember the heart attack I got thinking I bricked ```myPod``` through misuse of a boot logo mod. Fear of being deemed irresponsible with expensive tech and some ```DFU``` magic brought my precious back to life.


[Ordin Task Manager is the first software application I built.](https://itunes.apple.com/us/app/ordin-task-manager/id1080540755?mt=8)
------------------------------------------------------------------------

 As a sophomore in college, I found myself using ```Stickies``` to make a quick, prioritized list of stuff I had to do. I was a fan of [Clear Todos](https://itunes.apple.com/us/app/clear-todos/id493136154?mt=8), but became annoyed that it didn't have calendar organization. I ultimately wanted to:
 
 - Quickly create and prioritize tasks similar to Clear Todos.
 - Organize tasks on a calendar. HOWEVER:
	 - Incomplete tasks without a due date would be on top of the stack.
	 - Scheduled tasks would appear on given date and could be prioritized ahead of unscheduled tasks.
 - Have a list of completed tasks by month. A simple way to reflect on progress made.

So I did just that. I purchased the [Big Nerd Ranch Guide on iOS Programming](https://www.bignerdranch.com/books/ios-programming/), got my hands dirty with ```Objective-C``` and ```CocoaPods```, [found inspiration](https://www.invisionapp.com/do), survived several Xcode updates, figured out Github (a little too late), made an icon with Photoshop, made a preview video in iMovie, and eventually pushed the thing to the Apple App Store.

**Mistakes**

 1. [OrdinListViewController.m](https://github.com/sajayshah/OrdinApp/blob/master/Ordin/OrdinListViewController.m)
 2. No tests. Well kind of. See 1.
 3. commits on Github.
 4. Abandoned design patterns.

**Takeaways**

> I loved every minute I spent on this project because I made it for me.

With software there's this prevalent problem of overfitting solutions. Software engineers often feel pressure to add bells and whistles fearing users will leave their ecosystem for the next shiny thing. The value proposition gets replaced with "***We need to increase our daily active users.***"

I never moved forward with cloud integration, in-app advertising, or in-app purchases. Ordin solved my problem and proved useful throughout my college career. I still pay my yearly Apple Developer fee to keep it on the App Store because I believe in what Ordin represents:

Software engineering is about solving problems to improve quality of life.
-----------------------------------------------------------------
