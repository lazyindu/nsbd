# Telegram Views V4 ( Asynchronous )

![Gif](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExOGFkOTRiMTdjMTc3OTJhZmU0MDRmZGFlNGJiMjA3NGYxOGQwM2Y2ZSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/jStbo9qVAJsObKKr5a/giphy.gif)


## Features
- Asynchronous
- Support All Proxy Types: ( HTTP/S, SOCKS4, SOCKS5 ) 
- Auto Proxy Scraping Mode: ( You don't have to get proxies )


Arguments Exmaple + Modes

```python
# In this examples we are sending to channel @tviews and the post number is ( 4 )
# e.g: https://t.me/tviews/4
```

```python
# Auto Scraping Mode ( Auto Proxy "PROXYLESS" )
# This mode scrape proxies automatically from many sources
# You can update the sources from the auto dir
# This mode run forever it auto resecrap proxyes when the first loop done

tviews.py --mode auto --channel tviews --post 4
```

```python
# Load Proxies From File ( File List Of Proxies )
# This mode allow you to run your own proxies from a txt file

tviews.py --type http --mode list --proxy http.txt --channel tviews --post 4
```

```python
# Using Rotating Proxy ( Rotating Proxies )
# This mode allow you to run your own Rotated Proxies

tviews.py -t http -m rotate -p user:password@ip:port -c tviews -pt 4
```
