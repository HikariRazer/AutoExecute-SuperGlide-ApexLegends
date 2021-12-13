# AutoExecute-SuperGlide-ApexLegends
Super Glide Season 11 cfg file

### Apex Legends Super Glide  Hotkey Config Season 11

**autoexac.cfg**
```
exec superglide.cfg
cl_fovScale "1.7"
```
`cl_fovScale "1.7"` field of view setting from 110 to 120

**csuperglider.cfg**
```
bind "MWHEELDOWN" "+duck; fps_max 190; exec superglide.cfg" 0
```

**superglide.cfg**
```
bind "SPACE" "+jump; exec superglider.cfg
bind "MWHEELDOWN" "+jump" 0
```

**superglider.cfg**
```
bind "MWHEELDOWN" "+jump; fps_max 30; exec csuperglider.cfg" 0
```

**on game properties > advanced launch options > command line arguments**
```
+exec autoexec +exec superglide.cfg +fps_max unlimited
```

**Put the 4 cfg file into Apex folder > cfg folder**
