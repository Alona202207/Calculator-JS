
## Overview
Simple Calculator JS

This calculator has a dark theme with comfortoble button
### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**


## My process
 The first step was to find a calculator design. This code focuses only on the JavaScript logic employed to make the calculator work.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Vanilla JS


### What I learned

I decided to reduce the number of characters after the period in the result and used this code for that:

if(this.id=="="){
					var result=eval(history).toFixed(2);
					printOutput(result);
					printHistory("");


### Useful resources
For the design I used an example from this resource:

- (https://dribbble.com/shots/10269957-Simple-Calculator) - This is an amazing design which helped me to create  my own. 


## Author

- GitHub - [Alona202207](https://github.com/Alona202207)