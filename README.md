# MNISTweb
A website that recognizes written digits.

This project reads a digit written on a canvas element and recognizes it. It also lists the probabilities that it has assigned for each digit from 0-9.



The website link: https://ayishar.github.io/MNISTweb/

Few notes on index.html
*  Include "https://code.jquery.com/jquery-2.2.4.min.js" script to be able to call variables using a $.
*  context.strokestyle is assigned a colour in #RGB. Data read from the object returned by Image() has 4 values for each pixel - (x 0 0 y) for R, (0 x 0 y) for G, (0 0 x y) for B, (0 0 0 x) for #000000, and (x x x x) for #FFFFFF (white). The required value needs to be filtered out while reading into input array.

Reference link:
https://towardsdatascience.com/deploying-a-simple-machine-learning-model-into-a-webapp-using-tensorflow-js-3609c297fb04
