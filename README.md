# **About This Manual**
Here I have created a manual for finding out the url and downloading the video to host using chrome dev tools.


![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/18635232-489f-4432-b1ed-18fd0808015b)# 
# **Step 1. - Getting the video link**
Firstly get to the site that you watch the video on
Click ```ctrl + shift + c``` and this will open
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/3e5a29a6-3ae1-47bf-8732-b23bb583b4e3)

Then go to ```Network```
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/e8c96a1e-ce74-4b59-8de2-3d7beab71a49)

After getting there reload the page and start the video. After it has been running for a few seconds, pause it. Look at the ```Name``` column and look for reocurring urls.
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/384e9467-42e5-403d-ae44-6c3c270be2c2)
Here can be seen that ```19-011021.mp4``` is reoccuring many times. That means that it is sending chunks of data continuously. That means that it is the video playing and getting to host system. Find the first one occuring.
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/7718751e-da32-44ea-99fa-4973a736877f)

# **Step 2. - Downloading the video**
After that copy the url and open terminal and run the following command:
```
youtube-dl --no-mtime <copied url>
```

For example ```youtube-dl --no-mtime https://sirrah.carnet.hr/hls-baltazar/19-011021.mp4.m3u8?st=CE0ZLykhVzIaFJ88vewjtQ&e=1703109314```
If windows system youtube-dl has to be downloaded, for that search on google. Then open CMD and type that same command
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/0c4407c4-3735-43be-aa68-de9c58454bda)
First line is the command

It will start downloading and echoing a lot of info. Depending on the size of the video, it will have more/less info printed. Here is how it looks at the end
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/381a1654-ef18-41e8-a884-2c5ba9d8e14d)
Now open the folder you donwloaded the video in and watch the video!
![image](https://github.com/GoranSustekJr/video-downloader/assets/139004385/6141d235-99ac-4b23-b44f-4a608036cdb0)
