#media-converter
<h3>Script name:converter</h3>
<h4>Description</h3><p>convert your media files to different formats<br>create a video from image and audio,turn your video to mp3 file</p>
<p>converter is a unix program that can be used to do various media
		tasks.<br>it can be used to convert video files to audio files<br>,it
		can also be used to create a video from audio and image and
		other basic media conversions.</p>
		<b>-This program uses ffmpeg  video converter</b>
<h4>Installation</h4>
<p>To install just download the zip file and extract it..copy the converter file to your preffered path such as /bin or /usr/local/bin</p>
<i>To check your paths ie location where you can copy this file on the terminal just type :</i>
			<b>echo $PATH</b>
			<p>the path will be sepparated by a colon..you can copy your file to any of this path</p>

	<pre>USAGE:
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
		--help: used to display this help page</pre>

