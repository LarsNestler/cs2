# CS2 Config
My CS2 Config files, for backup and global access.

# 🚀 Launch options

The Launch options include some nessecary optimizations and changes to how the game is launched.
1.  Go to your steam library
2.  Right click on "Counter-Strike 2" > Properties
3.  Under tab "General" you can now input following launch options

Launch options:
> ```-high -refresh 160 -console +fps_max 0 +exec autoexec.cfg +r_drawparticles 0```

Explanations:
- ```-high``` > It will make the CS2 process higher priority, and therefore, your computer will give resources (RAM, CPU, etc) to CS2 instead of any other processes that you are running.
- ```-refresh 160``` > It will set your default screen refresh time to 160hz.
- ```-console``` > It will enable the developer console by default, so as to not require changing the setting every time.
- ```+fps_max 0``` > It removes the FPS cap that is enabled by default.
- ```+exec autoexec.cfg``` > It launches your autoexec file (see below) automatically at launch.
- ```+r_drawparticles 0``` > It is known to improve performance (at the cost of graphics quality) by disabling particle animations.


# 📃 Autoexec

The ```Autoexec.cfg``` file includes all binds, settings, crosshair, etc.

Path to autoexec:
> ``` C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg ```

# ⚙️ General Settings

## 📺 Video Settings
The ```cs2_video.txt``` file includes all video related settings.

Path to Video Settings:
> ``` C:\Program Files (x86)\Steam\userdata\XXXXXXXXX\730\local\cfg ``` (replace X with your user ID)

## ➕ Crosshair Settings

