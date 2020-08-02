# LiveWire
Video sharing website (YouTube clone)


## Description
LiveWire is a video sharing website done using PHP and MySQL. It is a website built exclusively for sharing videos on the demonstration of sensors.



***Instruction on usage:***
````
1. Clone or download this repositories
2. Unzip and open with TextEditor (VS Code)
3. Create MySQL database and name it to 'LiveWire'
4. Change host, username and password of MySQL database in 'includes\config.php'
5. Apply and Upload livewire.sql to 'LiveWire' database
6. Run!
````

***You can download latest version of FFMPEG Static file for conversion of video and to generates Thumbnail***
````
( FFMPEG available for Linux, Windows and Mac )
Choose FFMPEG Static files based on your operating system, Download and replace it in ffmpeg folder
````

***If you wish to process video or upload it to localhost folder***
````
1. Go to 'includes/classes/' and rename 'VideoProcessor-localhost' to 'VideoProcessor' (Ovewrite)
2. You need to create 3 folder,
  - uploads (top)
    - videos (inside uploads folder)
      - thumbnails (inside videos folder)
````

If you have anything to ask or would like to share your opinion, can email me:
> **rishabhv11@gmail.com**

## List of Features
- [x] Upload / Delete / Edit Video
- [x] Comment / Like / Dislike Video
- [x] Profile Page / Subscribe
- [x] Comment and Delete Comment
- [x] Search Video
- [x] Total views / Upload Date
- [x] Trending / Subscription Pages
