# Show-Tooltip-Jquery
showToolTip is function that can be invoked on a Jquery matched element(s) to show a tooltip.

### Features
+ Tooltip is designed to be shown at the top of the host element. 
+ If top space is not available then it shows at the bottom, left or right where space is available.
+ If space is not available in any direction then it pops open the tooltip atop the host element.
+ Its color and dimensions can be easily customised in the CSS.
+ Easy to use API

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

##### Built With
+ HTML5
+ CSS3
+ Jquery

# Live Version
#### URL: [Play with the Tooltip](https://note-taking.ayezahmed.now.sh )

# Authors
+ Saintaze [@saintaze](https://github.com/saintaze/)


