# Hey Rodney dataset

This is a dataset of voice samples for our wake word detection of "Hey Rodney".

All the audio samples will be licensed under the __Creative Commons Zero v1.0 Universal__ (CC0 aka Public Domain). Only upload samples containing your own voice!

## Steps to Record audio data and upload it on github

## Specifications:

| __Phrase__ | "Hey Rhodney"   |
| ------------- | ------------- |
| __Number of Samples__  | 3 (different files)|
| __Sample Rate__ | 16 KHz  |
| __Number of Channels__ | 1 |
| __Encoding__ | Signed 16-bit PCM |



## Step 1: Record the audio

### Steps to install Audacity
1. Using a web browser Navigate to the page https://www.audacityteam.org/download/
2. Choose Audacity for Windows/Mac/Linux based on your computer
3. After the download is complete open the installer file
4. Follow the steps of the installer

### Steps to implement in Audacity:
1. Open Audacity 
2. Set Project rate to 16000 ( In the bottom left ) 
3. Set the recording channel 1 (mono) recording channel ( which is in the bar just above the timestamps )
4. Record your voice saying *“Hey Rodney”*


__Export the audio file in the form of a .wav file__:<br> 
*Create a dedicated folder to store all recordings*
1. After completing each recording 
2. Go to File
3. Export
4. Export as *.wav*
5. Select the dedicated folder
6. Select signed 16-bit PCM as the encoding
7. Export the file

## Step 2: Create a Zip


### Ways to zip a file: 

__Mac__: 
- Right click on the folder 
- Compress


__Windows__: 
- Right click on the folder
- Send to  
- Compressed (zipped) Folder

__Linux__: 

```
zip -r [Name of the new folder.zip] [Name of the folder that contains the voice samples]
```

__Using a website__:  
- Go to the website https://www.ezyzip.com/zip-folder-online.html#
- choose the desired folder to be zipped 
- Upload the files 
- Click “Zip Files” 
- Click “save zip file”


## Step 3: Upload the data on GitHub

### Upload the folder to the GitHub repository *“hey-rodney-dataset”* by creating an issue:

- Open the url : https://github.com/drogue-iot/hey-rodney-dataset/issues/new
- Make a new issue with the title "Audio Sample"  
- Drag and drop the zipped folder ( which contains the sound snippets ) to the place where it says to leave a comment  
- You can also add your gender, first language ( optional ) in the comment <br>
  __Note : We are asking for the gender and first language so that we can keep a track of the distribution of sound samples over different genders and first languages__
