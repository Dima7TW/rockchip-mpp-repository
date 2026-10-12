# Rockchip-MPP-Repository
Repository deb packages with RKMPP support (beta, in development).

## About this repository
This repository have:
- [x] Ffmpeg 7.1.5 (by [nyanmisaka](https://github.com/nyanmisaka/ffmpeg-rockchip)) <in this month upgrade to 8.1.2 version>;
- [x] Rockchip librga 1.10.4;
- [x] Rockchip MPP (latest);
- [x] MPV 0.38;
- [x] Celluloid 0.27 (ubuntu noble) / 0.30 (debian trixie);
- [x] OBS-studio 32.0 (by [MecoMedia](https://github.com/MecoMediaOrg/obs-rockchip));
- [x] Moonlight 6.1.0;
- [x] V4L-utils (1.30, forked by [me](https://github.com/Dima7TW/v4l-utils-rkmpp)).

There are plans to add:
- [ ] gstreamer (1.28, 1.24 already exists, may be added or updated);
- [ ] chromium (132+);
- [ ] kodi (21+);
- [ ] maybe, add 32-bit ARM support (armhf/armv7) <it's needed?>.

At the moment, repository work only with Ubuntu Noble 24.04 LTS. Tested on Orange Pi 3B (RK3566) and Orange Pi 5 Plus (RK3588).

Information about how to install or remove repository merged to [wiki](https://github.com/Dima7TW/rockchip-mpp-repository/wiki).
## Problems
At the moment, in Ubuntu Noble ffmpeg not supported API Vulkan.

