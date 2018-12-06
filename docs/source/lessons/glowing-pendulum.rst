
glowing pendulum blocks lesson
==============================

construct a pendulum that glows using acceleration.

Topic
-----

Acceleration

Quick Links
-----------


* `activity </lessons/glowing-pendulum/activity>`_
* `tutorial </lessons/glowing-pendulum/tutorial>`_
* `challenges </lessons/glowing-pendulum/challenges>`_
* `quiz </lessons/glowing-pendulum/quiz>`_
* `quiz answers </lessons/glowing-pendulum/quiz-answers>`_

Prior learning/place of lesson in scheme of work
------------------------------------------------

Learn how to get the acceleration **acceleration**\ , ``acceleration`` value (g-force), in one of three specified dimensions. We will be learning how to get the acceleration using forever loop, a local variable, acceleration, the math library, as well as simple commands, such as led set brightness and led plot all.

Documentation
-------------

.. code-block:: cards

   basic.forever(() => {})
   let x = 0
   input.acceleration(Dimension.X)
   Math.abs(0)
   led.setBrightness(255)
   basic.showLeds(`
       . . . . .
       . . . . .
       . . # . .
       . . . . .
       . . . . .
       `)

Objectives
----------


* learn how to repeat code in the background forever
* learn how create a local variable to store data, so that you can use it in your code
* learn how to get the acceleration value (g-force), in one of three specified dimensions
* learn how to return the absolute value
* learn how to sets the brightness of the LED screen
* learn how to turn on all the LED lights on the LED screen