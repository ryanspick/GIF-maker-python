# GIF-maker-python


Usage: python gif.py <fps> <path to images separated by space>
Example: python gif.py 60 testFolder/gifs/
Assuming "testFolder/gifs/" points to a folder of images - will automatically order by creation date
  
  
  
    Inside gif.py in MAIN find the optional paramaters
  
    #------------------------MAIN GIF SETTINGS-----------------------------------
    types = ('*.jpg', '*.png','*eps') // add any other strange image files you may have

    gifName="generatedGif" //name of gif

    grabEveryNFile=1       //used to skip n files i.e. 4 would grab every 4 images
    reversableGif=False    //will reverse the gif once completed - doubles size of gif

    drawCounter=False      //will draw a counter in red for the number of gifs
    fontSize =15           //font size of counter text

    resize= 1              //multiplier for image size
    grayScale = False      //converts everything to gray scale
    blur = 0               //applies a gaussian blur of kernal size n
    #-----------------------------------------------------------------------------
 
