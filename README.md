# ☂️ YAUS - Yet Another Umbrel Store ![Written by humans, not AI](https://img.shields.io/badge/written_by_humans-not_ai-blue?style=for-the-badge)


> [!CAUTION]
>
> This is in very very very early early Developement
>
>What i mean by that is that nothing fukin works :)
>
>Actually windows and openmdiavault work
>
>All of these apps are Docker Containers not VMS

This App Store is intented to bring Windows/Macos/etc. to Umbrel.

## Installation
To use this jsut add this source to the Umbrel Community App Store page:
```sh
https://github.com/Ilikeguthib/YAUS
```

### ⚠️ How to add the App Store:
https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4

### Currently available apps

| App-Name                                             | Description                                                              | Port   |
|------------------------------------------------------|--------------------------------------------------------------------------|--------|
| [Dockur - Windows XP](https://github.com/dockur/windows/) | Run Windows XP inside a Docker container         | 8006 & 3389 (RDP)  |
| [Dockur - Windows 7](https://github.com/dockur/windows/) | Run Windows 7 inside a Docker container         | 8007 & 3390 (RDP)   |
| [Dockur - Windows 10](https://github.com/dockur/windows/) | Run Windows 10 inside a Docker container         | 8010 & 3391 (RDP)   |
| [OpenMediaVault - Arm + AMD](https://openmediavault.io) | Run a full Debian VM with OMV for Raid on your Umbrel         | 90 (WebUI) 9006 (noVNC) 444 (SMB)  |


## Sources
This Repo is made from
[Official Umbrel App Store](https://github.com/getumbrel/umbrel-apps).

The Docker Compose files are taken from the respective projects’ GitHub repositories.

## Disclaimer
I did not build these Docker images.
I am not affiliated with any of these projects and I do not own any associated trademarks.

## License
This project is licensed under the GNU GPLv3.
