# Les_Sons
Welcome to the github repository for the Les_Sons product sound conceptualization tool.

## Getting started 
1. Download the project repository from this github page.
2. Make sure to download and install Cycling74's Max or Max runtime from https://cycling74.com/downloads
3. Start the program by clicking on LesSonsV3.mxf in the *../Les_Sons-main* folder
4. When Les_Sons is starting a prompt will ask you to select a folder. To start with the example sounds of electric shavers select the *../Les_Sons-main/features_samples* folder within the *../Les_Sons-main* folder
   (To use your own samples new samples can be added to the features samples folder)
6. If needed put the max patch in presentation mode
7. You can now start using Les_Sons!
   
To help you getting started it is recommended to watch the Les_Sons tutorial video below. Clicking on the picture will bring you to the actual youtube video.

[![Les_Sons video Tutorial](https://i9.ytimg.com/vi/Q_ZCD8cKsXk/mqdefault.jpg?sqp=CIDnn78G-oaymwEmCMACELQB8quKqQMa8AEB-AHSCIAC0AWKAgwIABABGF8gXyhfMA8=&rs=AOn4CLBuunh0m6VAftop-AtPqapsCco8mA)](https://youtu.be/Q_ZCD8cKsXk "Les_Sons Video Tutorial")

## Troubleshooting
### The feature sound samples drop down list is empty, no sample can be selected
1. Click on the Select sounds folder icon 
2. Select the folder which contains the samples you want to work with. To use the example sounds of electric shavers select the *../Les_Sons-main/features samples* folder within the *../Les_Sons-main* folder 
3. Click open
4. Use the feature source samples drop-down list to select a desired sample

### The feature source visuals drop down list is empty, no visual can be selected or is shown
1. Click on the Select visuals folder icon 
2. Select the folder which contains the visual you want to work with. To use the example sounds of electric shavers select the *../Les_Sons-main/visuals* folder within the *../Les_Sons-main* folder 
3. Click open
4. Use the feature source visuals drop-down list to select a desired sample

### No audio can be heard
#### Make sure Max is using the correct audio device
1. Click Options in the top bar menu
2. Select Audio status...
3. Select the correct Audio driver in the Audio driver drop-down list
4. Select the correct Audio output in the Output device drop-down list
5. Hopefully you problem is solved, otherwise continue below

#### Make sure a feature sample is loaded
1. Select a feature sample in the drop-down list
2. Check whether an audio waveform is shown in the waveform display
3. Click on the play feature button to play a single feature sample
4. Check whether the time bar is moving over time
5. Hopefully you problem is solved, if the time bar is moving but no sound can be heard continue below

#### Known bug with housing filter
If you followed all the steps above but still no sound can be heard follow these steps.
1. Slide the Effect of housing slider above 0.0%
2. Bring back the slider to 0.0% or any desired position
3. Click play feature
4. Hopefully you problem is solved, otherwise try any of the steps above

## Project video
To get to know more about the master graduation project behind Les_Sons, please watch the video below. Clicking on the picture will bring you to the actual youtube video.

[![Graduation Project Overview - Tim Deltrap](https://i9.ytimg.com/vi/T6gMbs0yCYM/mqdefault.jpg?sqp=CITun78G&rs=AOn4CLDwWzTCs86Yt0GGYc7JMF0h6Lzk9Q)](https://youtu.be/T6gMbs0yCYM "Graduation Project Overview - Tim Deltrap")

## Repository structure
* LesSonsV3.mxf _Main application in the form of a Max collective to be run in the Max runtime_
* Dependencies _Folders that contain 
  - Feature Samples _Pre made libary containing multiple samples of product sound sources_
  - Scene Samples _Pre made library containing multiple samples of possible sounds present in a bathroom_
  
* Source Folder _All max patcher sources_ 


## License
Les_Sons © 2024 by Tim Deltrap is licensed under CC BY-NC-SA 4.0 

Spat5~
HISSTools 
Freesound © 2024 by https://freesound.org/help/tos_web/ under CC-BY 4.0
