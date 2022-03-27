I am having a issue with this challenge. 

Issue:
When trying to create the hover effect for the image, I decided to have an image-container with the image 
and the layer that goes on top of it

-card
  -image-container
    -image
    -layer
  -etc

So, the card haas a fixed width and some padding. This gives the image container it's size, in turn the image has a 100% width
which gives it the sixe of the image-container, it's parent.
This was working fine but then I added the .layer div. The styles I founf on the internet on how to achieve this on-top-layer effect and
I noticed that the layer actually measurres 279px instead of 275px.

To see the issue:
-have liveserver installed
-right click on index.html
-select open with liveserver
-on the browser, usee dev tools to inspect the image, thre you will see the layer first, since it is on top of the image.

considerations:
-I already have a reset.css
-code is a bit wonky, I only wanted to learn css fast and didn't even create a styles.css.
-on the index.html there are some comments explaining which are the relevant classes to check.

Please Help!
