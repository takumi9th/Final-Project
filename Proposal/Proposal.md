# Camera Synthsizer
### This is a multifunctional visual synthsizer that convert visual information to audio data. The instrument has multiple modes; Wavetable mode, Additive mode, Spectral Filter mode. In Wavetable Mode, you can make wavetable from photo that you take through the instrument. When you take a photo, it generates instant data that can impacts on internal FX like Saturator and Reverb. It also has performance mode that allows you to play the sound from real-time video data.

### The processing is mainly done by Max/MSP. The wavetable is designed by contrast from the photo. Partials of the additive synth is made by spectral view that is also consists of contrast data from a tiny pixel of the image. Mostly, the shape of the filter is also made in a same way. In a matter of FX, Reverb is made by the instant data from multiple sensors including camera, humidity sensor, distance sensor. Each sensor detects important element for the Reverb. For example, the humidity sensor, change the amount of reverb and distance sonsor size of it. The parameter of the saturator is set by RGB information of camera. The more you have bright color, the more sound will be distorted.

## Good outcome deliverable 
### Wavetable mode
### Additive mode
### Spectral Filter mode

## Better outcome deliverable
### Weather Reverb
### RGB Saturator

## Best outcome deliverable
### Performance Mode

## Outlook
### For the next step, I need more research for each sensors and I'll see What the good sensors and what is the good parameter to control the signal. I also have to know the processing of wavetable from photo and the way to make wavetable synth using Max/MSP. As a reference, I'll do breakdown of "Image2Wavetable" made by Dillon Bastan and Carlo Cattan. For additive and spectral filter mode, I'll study more about "Spectral Image Filter" in BEAP and additionally I'll try to export the stream data of pixel to the partials. To implement performance mode, I'll learn jitter and cv.jit that give me some data and parameters to manuplate the sound. In short, I'll "research the sensors, learn a lot of patch that related to my project, try the efficient way to get data through jitter".

## Materials
### Camera - Adafruit OV5640 160 Degree $14.95 
### https://www.adafruit.com/product/5841

### Temperature & Humidity Sensor - AHT20 $4.50 
### https://www.adafruit.com/product/4566

### Distance Sensor

## Reference
### "Image2Wavetable" 
### https://dillonbastan.com/store/maxforlive/index.php?product=image2wavetable