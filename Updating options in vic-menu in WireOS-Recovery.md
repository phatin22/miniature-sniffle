Compile vic-menu `https://github.com/ThommoMC/vic-menu` unless its there already and replace `vic-menu` in `/data` with new one 

 Create a new file called `ota-list.json` and place in `/data` with these contents and feel free to make changes

```
[
  {
    "name": "WireOS Dev",
    "url": "http://ota.pvic.xyz/vic/latest/dev.ota"
  },
  {
    "name": "WireOS OSKR",
    "url": "http://ota.pvic.xyz/vic/latest/oskr.ota"
  },
  {
    "name": "Viccyware Dev",
    "url": "http://ota.viccyware.com/latest-dev.ota"
  },
  {
    "name": "Viccyware OSKR",
    "url": "http://ota.viccyware.com/latest-oskr.ota"
  },
    {
    "name": "PurplOS",
    "url": "http://api.froggitti.net/ota/purplos/latest.ota"
  },
    {
    "name": "RedOS",
    "url": "http://api.froggitti.net/ota/purplos/red.ota"
  },
    {
    "name": "thommOS Dev",
    "url": "http://anki.thommo.dev/latest-dev.ota"
  },
    {
    "name": "rainbOS Dev",
    "url": "http://api.froggitti.net/ota/dev/rainbos.ota"
  },
    {
    "name": "Anki 1.6.0.3331 Dev",
    "url": "http://api.froggitti.net/ota/ankidev/1.6dev.ota"
  },
    {
    "name": "Anki 2.0.1.6081 PROD",
    "url": "http://api.froggitti.net/ota/ankidev/2.0.1.6081rmi.ota"
  }
]
```
