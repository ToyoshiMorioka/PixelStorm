# PixelStorm
![top](https://github.com/ToyoshiMorioka/PixelStorm/blob/master/top.PNG "top")
This is GPU based Particle Toolkit for TouchDesigner.

## Requirement
- Windows 10 64 bit
- TouchDesigner 099 (tested 2017.37900)

## Containers
### TOPtoVertexPixel
Suspend pixels to Geometry Container from pixel's position TOP and color TOP.
### TOPtoVertexCircle
Suspend circles to Geometry Container from pixel's position TOP and color TOP.
### TOPtoInstancePhong
TOP based Instancing. You can use translate, rotate, scale and color. shading is phong shading.
### BufferSizeCal
Convert particle counts to buffer size.
### AgeLoopTOP
grey gradation loop.
### SOPtoTOP (!Windows only)
Change SOP's tx,ty,tz,nx,ny,nz to TOP.
This Container uses "texelBuffer".
It is not supported at MacOS.
### VelocityController
Add randomize and multiply from input TOP.
### TOPtoTOP
Change TOP to pos TOP.
### PosCalculator
Mixing postion and velocity by age.

## Examples
### Basic
Very basic example.
### Circle
Circle basic example.
### Instance
Very basic examle for Instancing.

## Author

[Toyoshi Morioka](https://twitter.com/mogamogamachine)

## License

[MIT](https://github.com/ToyoshiMorioka/PixelStorm/blob/master/LICENSE)
