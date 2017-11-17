# TouchDesigner099-Slideshow

This is a slideshow I've created to accommodates my needs in my various TouchDesigner projects.

## Features
- Works with videos and images
- Preloads images to minimize impact on the application
- Bar showing the progression of the loading process
- Choice of 5 types of transition
- Automatically adds new media added to your slideshow folder
- Slave mode that enables you to link multiple slideshow together 

## Before using
- Make sure there's no special character in the path or file name. If so, you'll get an error and the loading will get stuck in the UI.
  - To fix this, rename or remove the badly named files and click on the *Reset* parameter

## How to use
1. Import the .tox
2. Add a folder containing photos or videos in the images *Folder* parameter.
   - If the folder exists and there's videos or images in it, the other parameters will be enabled
   

## Parameters
| Parameter                     | Description |
| ---                           | --- |
| Active                        | Content Cell  |
| Reset                         | Content Cell  |
|           |   |
| Randomize Order               | Content Cell  |
| Seed                          | Content Cell  |  
| Multiply RGB by Alpha         | Content Cell  | 
| Image Fit                     | Content Cell  | 
|           |   |
| Images/Videos Folder          | Content Cell  | 
|           |   |
| Display Length                | Content Cell  | 
| Images/Videos Folder          | Content Cell  | 
| Images/Videos Folder          | Content Cell  | 
| Images/Videos Folder          | Content Cell  | 
| Images/Videos Folder          | Content Cell  | 

## To do
- Remove media from the slideshow if he is removed from the slideshow folder
