# RTSPtoImage

!!! THIS IS A FORK !!!

RTSP Stream to Image or Mjpeg

use ffmpeg 

![RTSPtoImage image](https://user-images.githubusercontent.com/45854343/127688407-2ec5c234-caaf-45ea-b112-b5bcf93c909a.png)

## Fork changes

Reduce the cpu usage by 70% by showing only 1/5 of the frames
the webUi show all cameras all at the same time
reload button on the bottom
perfect fit for any 9.7 inch ipad screen (ipad 2,3,4,2017,2018, ecc)

## Installation

### mac os

brew install ffmpeg

### debian / ubuntu

apt install libavcodec-dev libavcodec-ffmpeg56 libavformat-dev  libavformat-ffmpeg56

### Download Source

1. Download source
   ```bash 
   $ git clone https://github.com/deepch/RTSPtoImage  
   ```
3. CD to Directory
   ```bash
    $ cd RTSPtoImage/
   ```
4. Test Run
   ```bash
    $ GO111MODULE=on go run *.go
   ```
5. Open Browser
    ```bash
    open web browser http://127.0.0.1:8083 work chrome, safari, firefox
    ```


## Configuration

### Edit file config.json

format:

```bash
{
  "server": {
    "http_port": ":8083"
  },
  "streams": {
   "H264_AAC": {
      "url": "rtsp://wowzaec2demo.streamlock.net/vod/mp4:BigBuckBunny_115k.mov"
    }
  }
}
```

## Limitations

Video Codecs Supported: H264 

Audio Codecs Supported: no

## Team

Deepch - https://github.com/deepch streaming developer

Dmitry - https://github.com/vdalex25 web developer

## Other Example

Examples of working with video on golang

- [RTSPtoWeb](https://github.com/deepch/RTSPtoWeb)
- [RTSPtoWebRTC](https://github.com/deepch/RTSPtoWebRTC)
- [RTSPtoWSMP4f](https://github.com/deepch/RTSPtoWSMP4f)
- [RTSPtoImage](https://github.com/deepch/RTSPtoImage)
- [RTSPtoHLS](https://github.com/deepch/RTSPtoHLS)
- [RTSPtoHLSLL](https://github.com/deepch/RTSPtoHLSLL)

  
  
 !!! NOT ME !!! But I will leave it because the software is cool
  
[![paypal.me/AndreySemochkin](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/AndreySemochkin) - You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
