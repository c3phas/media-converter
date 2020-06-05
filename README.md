# media-converter
### Script name:converter
#### Description: 
Convert your media files to different formats , create a video from image and audio,turn your video to mp3 file
Converter is a unix program that can be used to do various media
		tasks.It can be used to convert video files to audio files,it
		can also be used to create a video from audio and image and
		other basic media conversions.
		-This program uses ffmpeg  video converter.
#### Installation
To install just download the zip file and extract it.
Copy the converter file to your preffered path such as /bin or /usr/local/bin
*To check your paths ie location where you can copy this file on the terminal just type.*
```
$echo $PATH
```
The path will be sepparated by a colon, you can copy your file to any of this path
```

	USAGE:
		converter -option
		That simple,The program will guide you afterwords
	OPTIONS:
		-c : This option is used for basic video to audio conversion
		     if audio input is in a different directory provide
			 the full path to it
			 The output can also be directed to a different directory
			 by providing the absolute path
			 Note: if output name already exists they will be overwritten
		-p : This option is used to create a video from a raw image
		     file and audio file.
		-b : To convert your videos or audio from one format to another
			 say video from mkv to avi,audio from mp3 to mp4
		--help: used to display this help page

```
