## <p align="center">`linucc224`</p>

##  
### Dependencies <img alt="" align="right" src="https://badges.pufler.dev/visits/owl4ce/linucc224?style=flat-square&label=&color=000000&logo=GitHub&logoColor=white&labelColor=373e4d"/>
> **Required:**  
> `sh` `netpbm` `file` `coreutils` `grep` `sed` ( `doas` or `sudo` )

> **Optional:**  
> `imagemagick` `diff`
>
> * *imagemagick for better image identification.*
> * *diff for verbose mode to view patch changes.*

##  
### Usage
```sh
$ sh <(curl -s "https://raw.githubusercontent.com/owl4ce/linucc224/main/linucc224") -h
```
```sh

* Easily add your own Linux framebuffer logo by patching it!

USAGE:
  linucc224 [options] /path/to/kernel_sources

OPTIONS:
  -p /path/to/your_logo			[    patch    ]
  -r					[ restore all ]
  -v					[   verbose   ]
  -h					[    helps    ]

https://github.com/owl4ce/linucc224

```

> :heavy_check_mark: **5.13.x**

##  
### Enable config

> `Device Drivers` -> `Graphics support` -> `Support for frame buffer devices`
<p align="center"><img src="./screenshots/2021-08-12-051730_1301x748_scrot.png" align="center"/></p>

> `Device Drivers` -> `Graphics support` -> `Console display driver support`
<p align="center"><img src="./screenshots/2021-08-12-051704_1301x748_scrot.png" align="center"/></p>

> `Device Drivers` -> `Graphics support` -> `Bootup logo`
<p align="center"><img src="./screenshots/2021-08-12-051654_1301x748_scrot.png" align="center"/></p>
