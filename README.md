# README


Mood Based Music Player is an android application which detects the current mood of the user and play a song accordingly.

## Installation


Follow these instructions on your os.Make sure to create a **virtualenv** for your project


```bash
 $ git clone http://github.com/hemanditwiz/mood-based-music-player && cd mood-based-music-player
 ```


```bash 
$ sudo apt install python-opencv 
```


```bash 
$ python3 -m venv projenv 
```


```bash 
$ source projenv/bin/activate 
```


```bash 
(projenv) $ pip install -r requirements.txt 
```


## Notes


* After installing python-opencv, you need to copy it from your local directory to the project directory

* Eg: **cp -r /home/user/.local/lib/python3.5/site-packages/cv2  projenv/lib/python3.5/site-packages/**

* DO NOT add your env folder to git.

* Always apply the latest migrations after pulling changes from remote repo.

