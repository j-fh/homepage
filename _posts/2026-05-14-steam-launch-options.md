---
layout: post
title:  "My Steam launch options on Linux"
tags: linux gaming steam proton
categories: linux gaming
description: A collection of all my custom Steam launch options for my games.
---
## A Way Out
```
gamemoderun %command%
```

## Balatro
```
WINEDLLOVERRIDES="version=n,b" %command%
```

## BeamNG.drive (Linux version)
```
gamemoderun %command%
```

## Chained Together
```
gamemoderun %command%
```

## Elite Dangerous
```
kitty -e ./MinEdLauncher %command% /autorun /autoquit
```

## Mirror's Edge Catalyst
```
PROTON_DISABLE_NVAPI=1 WINEDLLOVERRIDES="dinput8=n,b" %command% -dataPath ModData/Default
```

## Nobody Wants to Die
```
gamemoderun %command%
```

## SubwaySim Hamburg
```
PROTON_ENABLE_HIDRAW=0x044f/0x0407 %command%
```