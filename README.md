This is a config I've been using for months. It's essentially a heavily simplified version of J's [Ultimate Config for L4D2](https://github.com/theletterjwithadot/Ultimate-Config-for-L4D2).

The purpose of it is to reduce input lag and optimize network settings, and to make the game less visually and aurally busy.

The config is meant for playing Campaign on official servers. It's not meant for Versus.

# Prerequisites
## [Recording Helpers](https://github.com/ProdigySim/recording_helpers)
Recording Helpers will be required to adjust regular and viewmodel FOVs. It has many other applications, but that's outside the scope of this project.

Download [recording_helpers-0.6-l4d.zip](recording_helpers-0.6-l4d.zip) and extract the files to your addons folder.

The FOVs are already pre-configured in [mod_helpers.cfg](https://github.com/fennjr/L4D1-Config/blob/main/cfg/L4D1-Config/mod_helpers.cfg)

## Launch Options
Paste the following into the game's Launch Options:

`-insecure -novid -lv -high -nojoy -noforcemspd -noforcemparms -noforcemaccel +mat_motion_blur_percent_of_screen_max 0`

`-insecure` is required for Recording Helpers to work.

In L4D2, the option prevents you from connecting to VAC-secured servers. That is not the case with the first game.

## [ion's Vocalizer](https://www.gamemaps.com/details/17219)
Useful for going idle and switching between characters with the radial menu.

[mod_vocalizer.cfg](https://github.com/fennjr/L4D1-Config/blob/main/cfg/L4D1-Config/mod_vocalizer.cfg) applies the default binds for it.

## Video Settings
Disable **Film Grain**.

Set **Filtering Mode** to **Anisotropic 8X**. **16X** is also acceptable.

Disable **Vertical Sync** to reduce input lag. You may want to cap FPS if your GPU overheats.

Set **Shader Detail** to **Low**.

Set **Effect Detail** to **High**, because it affects draw distance, including Tank projectiles.

Enable **Multicore Rendering**.

Set **Paged Memory Pool Available** to **High**

The rest depends on your system.

My settings for reference:

<img width="1920" height="1080" alt="video1" src="https://github.com/user-attachments/assets/659d3360-2c6e-4836-be43-927a55891f7b" />

# Installation
-

# 
