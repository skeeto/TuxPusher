# tuxpusher
A Tux themed 3D coin pusher game.

### Screendump
![Image of the TuxPusher game](https://dashboard.snapcraft.io/site_media/appmedia/2023/01/Screenshot_2023-01-10_04-47-51.png)

### Mechanics / Rules
- Getting a gold coin in a silver slot rewards you 2x silver coins.
- Getting a gold coin in a gold slot rewards you 2x gold coins.
- Getting a tux in a slot when you already have the tux gives you 6x gold coins and 6x silver coins.

### Controls
_Just move around your mouse and click to release a coin._
- Left Click = Release coin.
- Right Click = Show/Hide cursor.
- C = Orthographic/Perspective.
- F = FPS to console.

### Build
Linux:

    $ cc main.c -lglfw -lm

Windows:

    $ cc -mwindows main.c -lglfw3 -lgdi32

### Attribution
[Tux by Andy Cuccaro](https://sketchfab.com/3d-models/tux-157de95fa4014050a969a8361a83d366)

### License
This software TuxPusher is released under the [GPL-2.0-only](https://spdx.org/licenses/GPL-2.0-only.html) license. Being released under 'GPL-2.0-only' means that any subsequent versions of the GPL-2.0 license are NOT applicable to the source code or assets in this GitHub repository. This GPL-2.0-only licensing includes source code and all assets apart from the Tux 3D asset ([tux.h](assets/tux.h)) created by [Andy Cuccaro](https://sketchfab.com/andycuccaro) which is licenced under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
