# Fast API url shortener - a bit like bitly
[![Python application](https://github.com/RGGH/smurl/actions/workflows/python-app.yml/badge.svg)](https://github.com/RGGH/smurl/actions/workflows/python-app.yml)

![im](https://github.com/RGGH/url_shortener/blob/main/docs/2022-07-29%2016-57-30.gif)

API contains the following components; 
- An endpoint that accepts a URL to be shortened and returns a short url : `/api-1.0/create-short`
- An endpoint that accepts a short URL and returns or redirects to the original URL : `/api-1.0/visit-short`

Usage;
- A CLI that can be used to call the service : `python user_cli.py`

---

#### Install requirements `pip install -r requirements.txt`
#### Start server `bash server.sh`
#### Call service : `python user_cli.py`  
Developed for Linux/Mac - run in WSL on Windows
