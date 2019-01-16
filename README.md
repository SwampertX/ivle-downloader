# IVLE Downloader written in Python3

This is a temporary solution to IVLE, since IVLE is going to be deprecated and replaced by LumiNUS in a while. 


Please note that this requires python 3 to run.

## Instructions

```
git clone git@github.com:SwampertX/ivle-downloader.git
pip install -r requirements.txt
```


Then, make a copy of the `config.json` file by running
``` cp config.json.sample config.json	```


In config.json, set the `FOLDER_DOWNLOAD_LOCATION` to your specified folder, fill in your `LAPI API` key, `IVLE username` and `password`, then just run

```
python main.py
```

A LAPI API key can be obtained by: 

`Going to IVLE, log in, then enter this URL: http://ivle.nus.edu.sg/LAPI/default.aspx`

## Random notes

If you just want to get an IVLE token to play with LAPI yourself and cant seem to figure out how, feel free to use ivle_token_generator.py. I'm surprised there isn't something like this already.

At some point, I might just create a python wrapper for LAPI, depending on time available.

