# Show-Tooltip-Jquery
showToolTip is function that can be invoked on any Jquery matched element(s) to show a tooltip.

### Built With
+ HTML5
+ CSS3
+ Jquery

### Features
+ Tooltip is designed to be shown at the top of the host element. 
+ If top space is not available then it shows at the bottom, left or right where space is available.
+ If space is not available in any direction then it pops open the tooltip atop the host element.
+ Its color and dimensions can be easily customised in the CSS.
+ Easy to use API.

![Play with the Tooltip](https://media.giphy.com/media/XDM26hJA4z7tVzXrTI/giphy.gif)

### How to Use
+ include Jquery in your code then include the tooltip JS code.
+ Add the tooltip CSS in your CSS file.
+ Invoke the tooltip 
  
  ```js
  $('anyElement').showToolTip({
    title: 'Congratulations!',
    content: 'You are our lucky draw winner!',
    onApprove: function(){
      console.log('OK is clicked!');
    }
  });
  ```
  In the options object, you can pass title, content and onApprove method(called when Ok button is cliked) as arguments.

# Live Version
Change the host element top, left, right, bottom margin and change viewport width and height to see where the tooltip pops up
#### URL: [Play with the Tooltip](https://tooltip.ayezahmed.now.sh)

# Author
+ Saintaze [@saintaze](https://github.com/saintaze/)


