1/ to clone 1 new repo from github.com 
Command : 
	git clone https://github.com/nguyenchanh2201/Doc.git

2/ to push data to repo in github.com

Command : Example file : README.md 
	git add README.md
	git commit -m " message "
	git push -u origin master

3/ to pull data from repo github ( always update data from repo before push data to that )
	git pull https://github.com/nguyenchanh2201/Doc.git


4/ Audio file format (sampling rate, number of channels) can be verified using below command :
			sox –i /path/to/audio/file
			
5/  You can resample audio with sox or with ffmpeg : 
			sox file.wav -r 16000 file-16000.wav
			ffmpeg file.mp3 -ar 16000 file-16000.wav
			

