## Audio-Meter using JS
This is the simple Audio Visualizer using JS.
It will take the audio from the microphone and display the audio level in a canvas at realtime. 

Demo Link: https://shreekrishnalamichhane.github.io/Audio-Meter-with-JS/
> 🔴🔴Note: 
> Since Modern Browsers like Crome,Firebox, etc  blocks the microphone access on **page onload** by
> default due to security concerns, you cannot start the **window.AudioContext** on the page onload.

### Error Message from Crome Console.
>The AudioContext was not allowed to start. It must be resumed (or created) after a user gesture on 
>the page. https://goo.gl/7K7WLu
![Error](/images/error.png)

So, Here I use a button to solve that problem. So the function will load only you click on that button.

### I believe on opensource.
So any pull requests with the bug fixing and new feature will be appreciated.
Thanks.
