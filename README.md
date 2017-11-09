# imagemagick_watermark
simple bash script to apply a watermark image more conveniently

## Requirements
[ImageMagick](http://www.imagemagick.org)

## Install
### Download and put in executable ```PATH```
```$ wget https://raw.githubusercontent.com/drx777/imagemagick_watermark/master/watermark```
### make executable
```$ chmod u+x watermark```

## Usage
```$ watermark [watermark file] [source file] [output file]```

## Configuration
Check the ```CONSTANTS``` section in the script. Currently, the you can configure

- ```SCALE``` of watermark relative to max image dimension
- ```OFFSETX``` the distance from the image side
- ```OFFSETY``` the distance from the image top or bottom (depends on ```GRAVITY```)
- ```OPACITY``` of the watermark, 100 is opaque, use that if your image already has transparency
- ```GRAVITY``` the position of the watermark
