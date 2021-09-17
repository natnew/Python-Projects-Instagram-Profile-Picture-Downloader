# Python Projects: Instagram Profile Picture Downloader 🐍
Python Script <br>
This repo contains python code that downloads the profile picture of an Instagram account. <br>
Run the code.

Python
```python
import instaloader

bot1 = instaloader.Instaloader()

username="profile_username"

print(bot1.download_profile(username,profile_pic_only=True))
```

Output
```
profile_username\2021-01-22_08-40-45_UTC_profile_pic.jpg
```
