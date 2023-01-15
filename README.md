#### Not supported on mobile.

# 2fast2macropad -  a macropad copy/paste tool


It's the app I developed and use for work DAILY. Here, you can see the results of the last 10 weeks of daily use -- a crushing 41% in tickets resolved.

![redacted](https://user-images.githubusercontent.com/91502105/212519482-40747a49-21d6-4eef-b867-b7c5055cd8fb.png)

I made it because our platform has poor UX leading to losses in efficiency. When your solution hinges on solving pressing issues in real time, seconds are at a premium. Here you can see the comparison in the video below:

https://user-images.githubusercontent.com/91502105/200094696-14cb94fe-f69f-4653-8a66-3473976da863.mp4

On the right side, is BeyondTrust, the app we use at work to answer real time chats. 
To make the prompts come out, you have to click a very tiny arrow to select the custom prompt you want to use. 

<img width="420" alt="Screenshot 2022-11-04 at 13 38 10" src="https://user-images.githubusercontent.com/91502105/200040601-8a813a9e-8bb2-4f56-a163-780224267906.png">

If you didn't see the arrow, well, that's part of the problem isn't it? On average, you spend a nontrivial amount of time and actions (more than 3 clicks at the very least) just to begin a chat. This becomes a practical impossibility when 4 chats pop out at the same time leading to a large amount of nonproductive actions.

https://2fast2macropad.netlify.app/ is my personal macropad. It has 4 options which cover 90% (I use it everyday) of all chats. 

![test session w friend](https://user-images.githubusercontent.com/91502105/200043517-aa71898c-d0d7-428e-b226-25164ca5def7.gif)

In this test session with a friend, you can see how quick and simple it is to use. You just press the button and it copies the prompts so you can just paste it in the chat.

# Features:


![box demo](https://user-images.githubusercontent.com/91502105/200045794-a2d4f731-8c65-4bdf-82d1-4c24d0e41eaf.gif)


1. The last clicked item stays RED so I can visually confirm what I copied last pretty easily. This prevents pasting the wrong prompts in a fast paced high volume environment. 
2. Yellow for hover (same reason above). 
3. Black text on yellow hover (instead of white) for easy readability. 
4. Blue has high contrast with yellow/red and fades with the background so my eyes zero in on either red or yellow. 
5. Off-white background so it doesn't feel like staring at the sun.
6. I made a design choice not to go with [70-75ch-per-line "rule"](https://kickpoint.ca/the-readability-formula-making-your-website-easy-to-read/) so it retains the [macropad](https://www.tindie.com/products/dekuNukem/duckypad-do-it-all-mechanical-macropad/) feel. On the left is a macropad, and on the right is a piano key with 70ch.

![comparison](https://user-images.githubusercontent.com/91502105/200047751-f0d1bc88-4cec-4654-8b5c-c8f0bf22a812.png)

# Notes: 

- There are no hotkeys because 1 hand is always close to or on a mouse. If you like hot keys, there is [beeftext](https://beeftext.org/), which is free and open source.
- I probably could have gone with a plain purple background but I decided to be fancy. 
- I made this before we learned react in our boot camp so it was made with vanilla js, html, and css.
- In my opinion, it is currently feature complete, however there is now a demand for new features since other people started using it.

## No mobile because all our workflow is desktop.
