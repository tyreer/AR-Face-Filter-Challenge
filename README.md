# Halloween AR Face Filter Challenge

Dev challenge at Stink Studios London: use [Spark AR Studio](https://sparkar.facebook.com/ar-studio) to make a spooky Halloween experience.

![In process image 1](https://github.com/tyreer/AR-Face-Filter-Challenge/blob/master/images/dev-screengrab-0.png?raw=true)

I've included the custom `script.js` file I wrote to drive the interactions and timer. Spark AR has gone through 37(!) major version in the 8 months since I made this project, so the APIs this code references have likely changed. I've got version 48.1 of Spark AR on my machine. 

The core technical aspect I was interested in was getting the knife to look like it was stuck in the head (i.e. to get the tracking and layering occlusion right). I then figured it needed a build up for the suspense and foreshadowing, so that the "big reveal" would satisfying. I ended up with something a bit like an interactive music video that requires around 2 minutes of attention. Definitely more an art experiment than an attempt to make a filter people would use on Instagram! 

I screen recorded an entire end-to-end run here: [vimeo.com/407093062](https://vimeo.com/407093062)

To build the project, I found it helpful to go through the [tutorials](https://sparkar.facebook.com/ar-studio/learn/documentation/tutorials-and-samples/) Spark AR Studio provides. I combined techniques from those tutorials. For instance, the 3D object occlusion method is based on the sunglasses demo, and the blood streams are a _slight_ twist on the confetti particles and a happy birthday message. All the 3D knifes and fantasy-novel looking blades are from the free assets available in the Spark AR marketplace.

Unrelated work that Stink Studios has done in Spark AR:
- [Mickey Mouse 90th Birthday AR](https://www.stinkstudios.com/work/disney-mickey-mouse-90th-birthday-ar)
- [Selfridges AR Experience](https://www.stinkstudios.com/work/auxiliary--selfridges-ar-experience)

### Selfies taken in the filter

![Selfie take using AR face filter 1](https://github.com/tyreer/AR-Face-Filter-Challenge/blob/master/images/selfie-grab-0.JPG?raw=true)
![Selfie take using AR face filter 2](https://github.com/tyreer/AR-Face-Filter-Challenge/blob/master/images/selfie-grab-3.JPG?raw=true)
![Selfie take using AR face filter 3](https://github.com/tyreer/AR-Face-Filter-Challenge/blob/master/images/selfie-grab-5.JPG?raw=true)


