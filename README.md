## Introduction

In [SYS6023](http://records.ureg.virginia.edu/preview_course_nopop.php?catoid=34&coid=155113) System Cognitive Engineering, one of the assignments is to replicate Zhang and Norman (1994)'s [experiment](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.2876&rep=rep1&type=pdf), which explores various representations in distributed cognitive Tasks. Therefore, I made this small game website, which design a kind of coin game, with the similar rules of [Tower of Hanoi](https://en.wikipedia.org/wiki/Tower_of_Hanoi). 


## Implementation
There are three rules for the coin games. They are presented below:

* Only one disk can be transferred at a time.
* A disk can only be transferred to a pole on which it will be the largest.
* Only the largest disk on a pole can be transferred to another pole.

In order to know how fast player finish the game, I incorperate [tock.js](https://github.com/mrchimp/tock) as the timer. However, it doesn't start to time once the game begins. It has been improved in the complex version 2. In version 2, research can collect the play's data with the database. More details see this [repository](https://github.com/haoyuchen1992/Onlline-Cognitive-Experiment).


