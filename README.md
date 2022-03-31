# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Rui Jia**

Time spent: **** hours spent in total

Link to project:  https://glitch.com/edit/#!/galvanized-literate-hummingbird

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Game button appearance change goes beyond color (e.g. add an image)

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/7BJ8XSMSnQ.gif)
![](http://g.recordit.co/0rYIIM9Osc.gif)
![](http://g.recordit.co/g6kSzQIUVd.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
   
   1) Add images into my project: https://mica-web.github.io/learn/workflows/add-img-glitch
   2) How to add the image on the botton in HTML: https://stackoverflow.com/questions/17934332/how-do-i-position-an-image-at-the-bottom-of-div

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
   1) When I want to add the image to the button, I didn't know how to do it. So I search google, and find the solution. 
   2) When I want to add the sound to the button, I add the button in the HTML file and "5:600.6" in the freqmap array in JS file.  But I accidentally deleted “, ” after "4: 500.6". I checked it for a long time and even reviewed the entire code in the js file carefully, but I still couldn't find the error.  Then I think that when I usually write code in python, when there is a red prompt, it is usually a syntax error. Then I focused on this line and found this ridiculous error.
   3) When I use recordit to generate gif file, I tried many times and found that the recorded video only shows my desktop, without the content in chrome. I still found the solution on google. It turned out that I needed to open the permission for Chrome screen recording.

3. What questions about web development do you have after completing your submission?
Going through this simple project, I understand HTML, JS, CSS these three important front-end technologies. They are very interesting. But our current work seems to be focusing on the front end, but it can still be displayed on Chrome web pages. As far as I know, a full-stack web application project usually involves a server and a database. But this project did not involve them, and we could still implement some responses to client behavior and data storage.The question I want to ask is, what are the characteristics and differences between front-end projects and full-stack web application projects?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific.
I want the style of the mouse to change when the user clicks the mouse. Second, would like to be able to make a timer to set the game time for each player. In addition,  I still have some ideas which I can't reach, such as building a platform to record the performance (which includes the number of patterns and the time) of players who participate in the game and generate rankings. But this seems to be a full-stack web application project. We may need some new web pages and back-end frameworks to implement player registration and login, etc. At the same time, we need a database to record each player's performance. All in all, this looks complicated and interesting.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/mpduFwjZrbw)





## License

    Copyright [Rui Jia]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
