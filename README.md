# Discord Auto Clicker

As seen in [Headed's video](https://www.youtube.com/watch?v=7QdQivv_gzU).

This is a fork of [Rowin's Autoclicker](https://github.com/GitRowin/discord-auto-clicker).

Release version without need to compile added by Amplitudes.

![Screenshot](https://raw.githubusercontent.com/GitRowin/discord-auto-clicker/master/screenshot.png)

## Flaws
* The auto clicker is easily detected client-side because of JNativeHook.
* The randomization is mediocre, it probably won't get you auto banned though.

These flaws will not be fixed, this project is mainly for demo purposes.

## How to compile

To compile the auto clicker, you need Git and Maven.

1. Download the project using `git clone https://github.com/GitRowin/discord-auto-clicker.git`
2. Modify the constants `TOKEN`, `GUILD_ID`, and `CHANNEL_ID` in Clicker.java (Optional)
3. Compile using `mvn clean install`
