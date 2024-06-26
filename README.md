<h1 align="center">TweeterPy</h1>

## Overview
TweeterPy is a python library to extract data from Twitter. TweeterPy API lets you scrape data from a user's profile like username, userid, bio, followers/followings list, profile media, tweets, etc.

> _Note_ : `Use it on Your Own Risk. Scraping with Residential proxies is advisable while extracting data at scale/in bulk. If possible, use multiple accounts to fetch data from Twitter.` **_DON'T USE YOUR PERSONAL ACCOUNT FOR SCRAPING PURPOSES._**

## Installation

Install TweeterPy with pip

```python
  pip install tweeterpy
```

## Usage/Examples

```python
python quickstart.py
```

OR

```python
from twitter import TweeterPy

TweeterPy()
```

> ### Example - Get User ID of a User.

```python
from tweeterpy import TweeterPy

twitter = TweeterPy()

print(twitter.get_user_id('elonmusk'))

```

## Documentation

Check out step by step guide.

[Documentation](docs/docs.md)

## Configuration

> ### Example - Config Usage

```python
from tweeterpy import config

config.PROXY = {"http":"127.0.0.1","https":"127.0.0.1"}
config.TIMEOUT = 10
config.UPDATE_API = False

```

Check out configuration docs for the available settings.

[Configurations](docs/config.md)

## Features

- Extracts Tweets
- Extracts User's Followers
- Extracts User's Followings
- Extracts User's Profile Details
- Extracts Twitter Profile Media and much more.

## Authors

- [@iSarabjitDhiman](https://www.github.com/iSarabjitDhiman)

## Feedback

If you have any feedback, please reach out to us at hello@sarabjitdhiman.com or contact me on Social Media @iSarabjitDhiman

## Support

For support, email hello@sarabjitdhiman.com
