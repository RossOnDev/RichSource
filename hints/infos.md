# Youtube-Downloader mit Python

A simple intro to solve a problem with python. 



For a YT downloader you first need the right programme library 

To install it:

	pip install pytube
		


	

Python code for YT downloader

	from pytube import YouTube

	url = 'https://www.youtube.com/watch?v=9ZBmn5AzbPE'
	yt_video = YouTube(url)

	yt_video = yt_video.streams.get_highest_resolution()
	yt_video.download()

	print('your video is downloaded successfully')

execute with

	python ytdownloader.py
	
Open video in folder, done

## A few updates for easier operation

Add an input option for the YT url
	
	url = (input("paste the YT url: "))
	


