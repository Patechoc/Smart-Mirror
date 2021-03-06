# Smart-Mirror
Raspberry powered mirror which can display the news, weather, and time.

## Installation and Updating
### Code
If you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed, clone the repository.

```
git clone git@github.com:HackerHouseYT/Smart-Mirror.git
```

**Alternatively, you can download a zip file containing the project (green button on the repository page)**

Navigate to the folder for the repository

```
cd Smart-Mirror
```

### Install your dependencies 
make sure you have [pip](https://pip.pypa.io/en/stable/installing/) installed before doing this

```
sudo pip install -r requirements.txt
```

```
sudo apt-get install python-imaging-tk
```

### Add your api token
Make sure an editor is installed on your system, e.g. `vim` or `nano`: `sudo apt-get install vim`
Use it to edit you file

```
vim smartmirror.py
```

Register and get your token from forecast.io for accessing weather data,
then copy it in a file named `token_darksky.txt`. 

## Running
To run the application run the following command in this folder

```
python smartmirror.py
```

## Demo and Build Instructions 
(click image for link to video)
[![Link to youtube how-to video](http://i.imgur.com/cMyaSHT.png)](https://youtu.be/fkVBAcvbrjU)
