# Face++ to identify a person 
#download github code
```
$git clone https://github.com/lbaitemple/facematch.git
$cd facematch
```


#install picamera on raspberry pi
```
$sudo apt-get update
$sudo apt-get upgrade

$sudo apt-get install python-picamera python3-picamera
```

# make sure you create pictures 
```
$mkdir -p test/pictures_faces
$cp someone.jpg /test/pictures_faces
```

# how to run the code
```
python  rpi_pic_comp.py 
```
