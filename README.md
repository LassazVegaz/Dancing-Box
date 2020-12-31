# Danacing Box

A box trying to climb higher and higher and he has got some rhythm in his body

![box record gif](box-record.gif)

What you can get from this are, TRICKS  
I have used two CSS animations and several tranformations.

1. The box is moving with an infinite animation (but it is not actually moving)
2. This animation rotates the Z axis of box 90 degress (there is a little bump that gives box a rhythm)
3. Then there is `platform` where box is placed. Platform is rotated 40 degrees.
4. Then this platform's animation moves platform backward when the box rotates

Still you did not see the main trick. Both animations have 1s duration. When the animations are over both comes to original positions to do next iteration. And that annoying feature helps to show the box as moving. Platform is moving 200px backward and box has a 200px length. And also box is rotating 90deg. When box is done rotating it is coming to original position visually because platform has moved 200px backward. Instantly box and platform reset its positions. But nothing changes visually.

Okay maths class is over happy coding 😜 (or designing 🤔)
