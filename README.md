# RedditVidBot
Automatically creates a video which reads out comments in a reddit thread overbackground gameplay, just like you'd see in youtube shorts or on tiktok

This isn't actively being worked on, however the biggest improvement to be made is to automatically find a series of comments that would make the video 30 seconds long

# How it works:

1. Find one of the top 10 current posts on hot in AskReddit
2. Using DOM elements, takes a screenshot of the post title and top comment
3. Generate text to speech for the comment and title
4. Download minecraft gameplay and cut to a random part
5. Process everything together using moviepy

# Imporant Info
It uses python3 and was tested on ubuntu.

It takes about 2 minutes to generate a video, however this all depends on comment length

All necessary libraries are listed at the top imports

# How to use:
1. Run pip install discord-webhook pytube moviepy praw playwright mutagen gtts colorama
2. Run playwright install
3. Launch .py file

# Example of output

https://user-images.githubusercontent.com/40571030/175141970-2bfffd38-9501-4d13-ae44-84c3f4105ce7.mp4

