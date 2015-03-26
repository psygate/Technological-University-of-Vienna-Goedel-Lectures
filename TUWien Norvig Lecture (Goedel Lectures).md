Language Understanding & Recognition:
=====================================

* Wordbag Model
* Fridge Magnet Model

-------------------------------------------------

Image Recognition:
====================================

imagenet (http://www.image-net.org/): Collection of machine learning images.

Splitting images into pieces -> Tiling posters and stuff
Piece inventory:
Choose a set of 200 Pieces to make near-copies of each Image

minimize difference: Sum(Copy - Image)
where Copy(x,y) = Sum(weight x piece)

Lead to recognition that images are made of lines. (Done for black and white pictures.)

Idea: Combine a smaller bit inventory into more bit inventories, assembling larger units in stages.
First stage contains lines.
Second stage recognizes elements like nose, ears, mouth, eyes, wheels, doors.
(Youtube goes in, cat comes out.)

2012 Model: 8 Layers - Krizhevsky, Sustkever & Hinton (16% error rate)

2014 Model: 24 Layers - Google team (6% error rate)

--------------------------------------------------

Video Game Playing by Exploration:
=====================================================
(Unsupervised & supervised learning) >> Reinforced Learning (Doing well, doing poorly - Animal training)
by Google Deepmind
Taught a computer to play Atari games from the 70ties

-----------------------------------------------------

Questions:
=====================================================

language translations for odd languages?
Intermediate translation. Norwegian -> English -> ...
Sometimes languages are badly translated if words move a lot.

Can you do deepmind on the raspberry pi at home?
Some yes, some no. Better to get more. Done on a weekend with Google capacities.

Where do you see machine learning in 2-5 years, and what are the great walls you are running up against right now?
Hard to predict, but much changed with deep learning in the last few years. Perceptual problems work pretty well,
[stream cut out]. Long term planning is a problem.

How do you identify objects put into a wordbag to a computer?
Individual words are identified as simple numbers. Count what words, how often.

What role will symbolic and logic approaches play in the future?
Changes in the field of AI. When he started the dominant approach was logical based, but shifted to probabilistic models. Because the real world is messy and you can never be 100% sure. Logical based approach was bad, because you couldn't proof stuff.

SEO Question stuff.

With all the inaccuracy that is inherent in algorithms, what are the risks for people?
The field hasn't figured out how to build secure and hardened systems that run. Other fields have figured out how to do that, like civil engineering. People are apparently willing to deal with those errors. But maybe we need more processes to ensure quality of software, even if this means slowing development down. The seperate issue of privacy is more a societal one than a technological one. The field hasn't learned how to deal with apparent failures, like algorithms that work for 1 in a million, but fail on 10 of a million. Independend verification is needed.

Google is using AI technologies internally?
What's the line between AI technologies and data analysis. Interviews are analyzed, after years too. Winner at programming contests seems to be a negative factor in performing well at Google. Everyone hired at Google is pretty well. If someone passed a hiring bar, they are all at the same level. You perform better if you go slowly and get things right and ponder on questions.
