# Observer-Pattern
This is one of the most common Design Patterns in Java.

I've implemented a simple example in Java-Swing. 

I basically have a unique JFrame which is the Subject with JButtons inside and as many as Observer JFrames I want, identical to the Subject JFrame. 

The main scope here is that when I click a button only from the Subject JFrame, the same button it seems to be clicked at the Observer JFrames.

**1. Choose how many observers you want.**

![input](https://user-images.githubusercontent.com/77761282/116609573-31e32100-a93d-11eb-9466-139a2dc161e5.png)


**2. Now here is a gif of the result**
![observerPattern](https://user-images.githubusercontent.com/77761282/116611369-f5182980-a93e-11eb-936a-97d41d7fd286.gif)


***Also, don't forget that when you click a button from the Observer JFrames nothing must happen to the other JFrames. This is the whole idea of the Observer-Pattern.***

What is Observer Pattern? -> https://www.tutorialspoint.com/design_pattern/observer_pattern.htm
