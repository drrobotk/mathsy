# The Fourier Series

The **Fourier series** is an expansion of a (periodic) function in terms of combinations of sines and cosines and the more you add, the closer the series gets to the original function.

These techniques have become an integral part of the toolboxes of mathematicians and scientists and the Fourier series have a diverse number of real world applications which include but not limited to file compression (e.g. JPEG or MP3), signal processing in communications, astronomy, acoustics, optics, quantum mechanics, quantum field theory and cryptography.

Recall that *Taylor series* allows us to represent a function <img src="https://render.githubusercontent.com/render/math?math=f(x)"> in terms of powers of <img src="https://render.githubusercontent.com/render/math?math=x">,

![taylor](http://www.sciweavers.org/upload/Tex2Img_1580169899/render.png)

Similarly, the Fourier series allows use to decompose a function in terms of combinations of sines and cosines,
![fourier1](http://www.sciweavers.org/upload/Tex2Img_1580170069/render.png)

The Taylor series provides a local approximation, but the Fourier series usually converges faster to the original function. In real life applications, we only consider the first few terms of the series. 

Consider file compression with MP3s, you take a sound and expand its Fourier series which will have an infinite number of terms but the series converges so fast that taking the first few terms is enough to reproduce the original sound; this allows us to reduce the file size.

| ![fourier4](https://user-images.githubusercontent.com/51001263/73301143-2836af00-420a-11ea-886d-4db751235e43.jpg) | 
|:--:| 
| *It turns out almost any kind of wave can be decomposed as a Fourier series.* |

For non-periodic functions we can restrict the function to a particular range and assume that the function repeats itself outside the range.

The function <img src="https://render.githubusercontent.com/render/math?math=f(x) = x"> with <img src="https://render.githubusercontent.com/render/math?math=-\pi \leq x \leq \pi"> and <img src="https://render.githubusercontent.com/render/math?math=f(x)=f(x%20\pm%202\pi)"> is called a *sawtooth wave* as it repeats itself periodically.

| ![fourier2](https://user-images.githubusercontent.com/51001263/73300927-c1b19100-4209-11ea-84bf-2be800c88d2a.gif) | 
|:--:| 
| *The Fourier series (orange) of the function <img src="https://render.githubusercontent.com/render/math?math=f(x)=x"> (blue).* |

For some functions, known as even or odd functions, there will be only combinations of sines or cosines, but not both.

| ![fourier3](https://user-images.githubusercontent.com/51001263/73300425-e2c5b200-4208-11ea-91a4-6ed5228df2be.gif) | 
|:--:| 
| *The Fourier series (orange) of the function <img src="https://render.githubusercontent.com/render/math?math=f(x)=x^3"> (blue).* |

The Fourier series can also be used to draw any complex shape by tracing out *epicycles*. 

If you followed a single point on the edge of a rotating disk and traced it out, you'd get a circle.  If you added a second rotating disk and traced a point around its edge, you'd get a flower shape. By adding additional disks and varying their speeds and sizes, you can get increasingly complex curves which are known as epicycles.

| ![bart](https://user-images.githubusercontent.com/51001263/73291053-59f24a80-41f7-11ea-82f7-633ac7cffc42.gif) | 
|:--:| 
| *Bart Simpson traced out using epicycles.* |
