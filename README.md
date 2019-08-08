[//]: # (For development of this README.md, use http://markdownlivepreview.com/)

# SmoothstepCHOP

## What is Smoothstep?
see [Wikipedia](https://en.wikipedia.org/wiki/Smoothstep) and [Shaderific](http://www.shaderific.com/glsl-functions)

The SmoothstepCHOP has a range input: `Fromrange1`, and `Fromrange2`. It also has a range output: `Torange1`, and `Torange2`. For an input value `x`, the SmoothstepCHOP is equivalent to the following GLSL code:
`return mix(Torange1, Torange2, smoothstep(Fromrange1, Fromrange2, x));`

There are alternative modes such as "smootherstep", "smootheststep", and "linear clamp".

## Instructions
[Build the dll yourself](https://docs.derivative.ca/Write_a_CPlusPlus_Plugin), or use of the compiled DLL files. `CPlusPlusCHOP/build/SmoothstepCHOP.dll` has been compiled for TouchDesigner 2018.26750 and `CustomOperator/build/SmoothstepCHOP.dll` has been compiled for TouchDesigner 2019.17550. This newer version can be used as a [Custom Operator](https://docs.derivative.ca/Custom_Operators)

## Changelog
* 2019-08-07 create a Custom Operator version for TD 2019.17550.
* 2019-07-16 working version of smoothstep, smootherstep, smootheststep, and linear clamp.

## Thanks
* [Ken Perlin](https://mrl.nyu.edu/~perlin/)
* [Kyle McDonald](http://kylemcdonald.net)
* [Wolfram Alpha](http://wolframalpha.com)