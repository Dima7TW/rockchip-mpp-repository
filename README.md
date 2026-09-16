# Rockchip-MPP-Repository
Repository deb packages with RKMPP support (beta, in development).

## About this repository
This repository have:
- [x] Ffmpeg 7.1.5 (by [nyanmisaka](https://github.com/nyanmisaka/ffmpeg-rockchip));
- [x] Rockchip librga 1.10.4;
- [x] Rockchip MPP (latest);
- [x] MPV 0.38;
- [x] Celluloid 0.27 (ubuntu noble) / 0.30 (debian trixie);
- [x] OBS-studio 32.0 (by [MecoMedia](https://github.com/MecoMediaOrg/obs-rockchip));
- [x] Moonlight 6.1.0 (latest);
- [x] V4L-utils (1.30, forked by [me](https://github.com/Dima7TW/v4l-utils-rkmpp)).  
\
\
There are plans to add:
- [ ] gstreamer (1.28, 1.24 already exists, may be added or updated);
- [ ] chromium (132+);
- [ ] kodi (21+).\
At the moment, repository work only with Ubuntu Noble 24.04 LTS.
## How to install this repository?
Run in terminal
```
echo "deb [trusted=yes] https://apt.fury.io/dima7tw/ /" | sudo tee /etc/apt/sources.list.d/fury.list
sudo apt update
```
Then, install this package:
```
sudo apt install libv4l-0t64 v4l-utils
```
Then, install needed packages.

## How to remove repository?
Run in terminal:
```
sudo rm /etc/apt/sources.list.d/fury.list
sudo apt update
```
