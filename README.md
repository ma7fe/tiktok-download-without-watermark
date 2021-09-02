# tiktok-download-without-watermark

Hello! 👋 This is fast private API to download music and videos without watermark from TikTok.

You don't need to use X-Gorgon and X-Khronos 🥳

# Usage:

Base URL: https://still-earth-46953.herokuapp.com/

**Aveme ID** is required to work. It can be obtained using the [tiktok-scraper](https://github.com/drawrowfly/tiktok-scraper) for example.

## Get URL's of video without watermark 
**URL:** {Base URL}/v1/video/{awemeId}

**Method:** GET

**Headers:**

* Token: {TOKEN}

### Response:
``` json
{
    "urls": [
        "https://v16m-default.akamaized.net/7dc9b14a1a829110618900a07dabf863/6131acb2/video/tos/alisg/tos-alisg-pve-0037c001/3d54f4834c4141c986d8364b9ec8e55a/?a=0&br=6042&bt=3021&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=UC2fP_b3aGh-Inz&l=20210902230334010245147099385DDB29&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3FnOGY6ZjRuNzMzODczNEApZjY6OjZkO2UzN2g8PDwzNGctMmtzcjRfM2pgLS1kMS1zczNfMC0tYF4xXy8yXl40YmE6Yw%3D%3D&vl=&vr=",
        "https://v16m.byteicdn.com/7dc9b14a1a829110618900a07dabf863/6131acb2/video/tos/alisg/tos-alisg-pve-0037c001/3d54f4834c4141c986d8364b9ec8e55a/?a=0&br=6042&bt=3021&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=UC2fP_b3aGh-Inz&l=20210902230334010245147099385DDB29&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3FnOGY6ZjRuNzMzODczNEApZjY6OjZkO2UzN2g8PDwzNGctMmtzcjRfM2pgLS1kMS1zczNfMC0tYF4xXy8yXl40YmE6Yw%3D%3D&vl=&vr=",
        "https://api.tiktokv.com/aweme/v1/play/?video_id=v10044g50000c4mk61bc77ucv5nd5n00&line=0&is_play_url=1&source=PackSourceEnum_AWEME_DETAIL&file_id=1d0e979a9ae5420bb48aac3070733bc6"
    ]
}
```

## Get URL's of music from video 
**URL:** {Base URL}/v1/music/{awemeId}

**Method:** GET

**Headers:**

* Token: {TOKEN}

### Response:
``` json
{
    "urls": [
        "https://sf16-sg-default.akamaized.net/obj/tiktok-obj/7002326577015229186.mp3"
    ]
}
```
---
## Contact me to get a token for a demo 🦋

**Telegram: [@ma7fe](https://t.me/ma7fe)**
