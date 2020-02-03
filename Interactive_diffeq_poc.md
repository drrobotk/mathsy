# Ideas for interactive elements for *differential equations*

## Mathematica worksheets

Mathematica can be used to create interactive demonstrations of particular concepts related in mathematics and physics, including modelling phenomena and creating simulations. 

In the short essay on differential equations, we looked at exponential growth in the context of modelling cancer. 

To this end, I have created a Mathematica notebook from scratch (see cancer.nb) which can explore the solution further;

| ![Cancer](https://user-images.githubusercontent.com/51001263/73688043-169a4f00-46c3-11ea-9278-3e3fd8f18653.gif) | 
|:--:| 
| *Modelling Cancer Growth in Mathematica, with initial value N₀ and growth rate λ.* |

Here the user can visualise how the growth increases over time, as well as change the parameters such as the initial value or growth rate using the sliders which provide interactivity.

There are many other demonstrations available online: https://demonstrations.wolfram.com/

Instead of reinventing the wheel, it may be more efficient to use or improve on these demonstrations. 

In the end, the goal is to deliver the best content available for learning - whether that's creating these notebooks from scratch or adapting a pre-existing one, what ever it takes to deliver quality demonstrations.

## Can you crack the code? Proof of concept

This is a proof of concept for a game that can be played to crack a particular code by solving differential equations, the solution(s) of which are used to find the hidden message. 

The final solution can be hidden until the user enters it to check if it is correct.

The difficulty can also be increased by changing the particular differential equation or using a different cipher to decrypt the message. 

It can also be used in a competition format, where by the challenger has to solve a series of differential equations of various types and orders, to find the message and win a prize.

<pre>
<img src = "https://user-images.githubusercontent.com/51001263/73676598-8d781d80-46ac-11ea-90ab-2457113cfca9.png">

<img src = "https://user-images.githubusercontent.com/51001263/73676599-8d781d80-46ac-11ea-9a58-de49e1047825.png">

You can find the message by using a (A1Z26) substitution cipher. 

That is, assigning each letter in the alphabet a number from 1 to 26. e.g <img src="https://render.githubusercontent.com/render/math?math=A=1, B=2">.. etc.

First you need to solve the ODE. 

What function do you know that you can differentiate to get '3'?

Differentiating the function y = ax + c gives <img src="https://render.githubusercontent.com/render/math?math=dy/dx = a">. 

So the solution we have is y = 3x + c. 

We can find the number c by using the initial condition <img src="https://render.githubusercontent.com/render/math?math=y(0)=5">, to obtain <img src="https://render.githubusercontent.com/render/math?math=c=5">.

Hence the solution to the ODE is,

<img src = "https://user-images.githubusercontent.com/51001263/73676600-8d781d80-46ac-11ea-8790-ad0ba80ed674.png">

Now it's a simple matter of substitution of the numbers into the solution to find the encrypted cipher. 

e.g 
<img src = "https://user-images.githubusercontent.com/51001263/73676597-8cdf8700-46ac-11ea-915e-22b25a2d1a68.png">

Repeating this for all the numbers gives us: 20;15;15;20;8;2;18;21;19;8

This message can be decrypted easily to find the word: toothbrush
</pre>
