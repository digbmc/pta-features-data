# Method

## Capturing stills 

1. Download [FFmpeg](https://www.ffmpeg.org)
2. Add FFmpeg to your path
3. Use command **ffmpeg -i inputvideo.mp4 -vf fps=0.5,"scale=iw*sar:ih,setsar=1" directory/outputname_%04d.png**
   - Courtesy of [Dave Rodriguez](https://drodz11.github.io/colors-of-ozu/methods.html)
   - This command takes a still every two seconds 

## Downloading other software

1. Download [Fiji](https://fiji.sc) (ImageJ)
   - ImagePlot automatically downloads a version on ImageJ, so you can use technically that instead of downloading Fiji, but I prefer Fiji's GUI and search function.
2. Download [ImagePlot](https://github.com/culturevis/imageplot)

## Creating z-projections and montages

### Z- projections 

1. Launch Fiji
2. Search for 'import image sequence'
3. Select directory containing stills
4. make sure 'virtual stack' is selected
5. Search for z-projection
6. Select 'sum slices'

### Montages
1. Launch Fiji
2. Search for 'import image sequence'
3. Select directory containing stills
4. make sure 'virtual stack' is selected
5. Search for make montage
   - the menu path should be image > stacks > make montage
7. Lower the scale factor if necessary (I had to lower it from .25 to .1 for the montage to load properly)

## Using ImagePlot
1. Launch ImageJ within the ImagePlot directory
2. I followed [this](https://blogs.baylor.edu/digitalscholarship/2015/12/08/imagej-with-imageplot/) tutorial from Baylor University Digital Scholarship to create my graphs!
