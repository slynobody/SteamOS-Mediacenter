# Mediacenter for Steam-Deck / Linux 
## 'kodi', preconfigured for streaming / privacy

<img src="/kodi.png"/>

>
>
> git clone https://github.com/slynobody/SteamOS-Mediacenter
> 
> cd SteamOS-Mediacenter
>
>  chmod +x *.sh
>
> ./install.sh

# Turn your steamdeck* to a media-center 
## - a button-press away (game-mode)!

 Streaming, Music, Movies, Pictures, Radio, TV – central, one place. (relatively privacy-friendly, <a href="https://github.com/slynobody/SteamOS-Privacy">also see)</a>

 **preconfigured: 200+ streaming-services (mostly 1080p+)** -- incl. paid like netflix, disney+, amazon, crunchyroll, mubi, youtube, spotify, twitch, imdb & others + arthouse providers & nearly every   free public broadcasting tv & radio-stations.

 preinstalled: **no need to fiddle with addon-installation** -- pictures, music, videos - directly through desktop-mode-directories.

 customize: everywhere you are – just click right, set current content as 'favorite' -- and find it again in 'favorites'.

 extend : choose between hundreds of other preinstalled addons & install them easily.

*<sub>the .kodi-dir from this repo can be used in any other linux-distro.</sub>

# FAQ
## it does not work
> cd SteamOS-Mediacenter
> 
> chown -R $USER:$USER .kodi

## it does not work with flatpak installation?!
> ln -s ~/.kodi ~/.var/app/tv.kodi.Kodi/data/

## how do i get resolutions beyond 720p?
gamemode: properties: set another resolution there.

## how do i use netflix?
to get secure access to 1080p-streaming you need to login once through a browser to get a credential-file as well as a code. use 'netflix.sh' for this.

> cd SteamOS-Kodi-Installer
>
> ./netflix.sh

background: https://github.com/CastagnaIT/plugin.video.netflix/wiki/Login-with-Authentication-key

# why is 7.1-audio preconfigured?
just use https://github.com/slynobody/SteamOS-surround and you will hear.

## how do i remove this?
> ./remove.sh (all config will be lost!)

## are all components legal?
> yes, free and open. all preinstalled streaming-services do respect copyright / ip.

# about: kodi
Kodi (formerly XBMC) is a free and open-source media player and technology convergence software application developed by the Kodi Foundation, a non-profit technology consortium. It allows users to play and view most streaming media, such as videos, music, podcasts, and videos from the Internet, as well as all common digital media files from local and network storage media, or TV gateway viewer.

The software was originally created as Xbox Media Player for the first-generation Xbox game console, changing its name in 2004 to Xbox Media Center (abbreviated as XBMC, which was adopted as the official name in 2008) and was later made available under the name XBMC as a native application, then the project was renamed again from XBMC to "Kodi" in July 2014.

Kodi has attracted negative attention from the news media and law enforcement agencies due to some add-ons as plug-ins made available by third parties for the software that facilitates unauthorized access and playback of media content by different means of copyright infringement, as well as sellers of digital media players that pre-load them with third-party add-ons for the express purpose of making "piracy" easy. The XBMC Foundation have expressed that they do not endorse the use of third-party add-ons that are designed for the purpose of "piracy", and it takes active steps to disassociate and distance the Kodi project from third-party add-ons that violate copyright.

also see: https://en.wikipedia.org/wiki/Kodi_(software) as well as https://kodi.tv/

# Disclaimer
1. Use at your own risk!
2. This is for educational and research purposes only!
3. No responsibility taken for any local customizations of the git!


<a href="https://artsandculture.google.com/experiment/viola-the-bird/nAEJVwNkp-FnrQ?cp=e30."><img src="https://images.pling.com/img/00/00/78/78/79/2160403/proxy-image1.jpeg"/></a>
