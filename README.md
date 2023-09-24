## I DO NOT OWN ANY OF THE CUSTOM MUSIC ADDED:   CREDITS GOES TO HOYO-MIX, YU-PENG CHEN AND HOYOVERSE.
***
**Sounds of Teyvat** aims to add most music from the popular gacha game Genshin Impact to Minecraft. The custom soundtrack is entirely situational, changing fittingly to the biome you're walking into, creating a more nicer adventure experience. This vanilla resource pack replaces all Minecraft OST and adds a little over 170 custom songs to the game.

The goal is to bring Genshin's incredible music to fit Minecraft's enviroment. Because of that, some songs that would play in Genshin's context doesn't necessarily play in the equivalent Minecraft's context. A good chunk of them were repurposed to fit Minecraft's biomes the best it can with no business with the original game. There is also some songs that were deliberately not added because it didn't fit Minecraft totally, those mostly being domain BGMs, battle BGMs and so on, with few expections. 

## Soundtrack Regions
Those are the regions currently implemented to the pack and their overall presence in the game, though they are largely distributed between biomes:
- Mondstadt -> General Biomes
- Dragonspine -> Snowy Biomes <small>(complete)</small>
- Liyue -> Badlands, Desert <small>(complete)</small>
- Sumeru -> Badlands, Desert, Jungle
- Inazuma -> Cherry Grove <small>(complete)</small>
- Fontaine -> Ocean, Underwater <small>(complete)</small>

## Accompaniment for this pack
**Optional Generation:** Sounds of Teyvat works great with vanilla's [Large Biomes] generation and [Tectonic] data pack as both of those provides bigger biomes. 

[Terralith], unfortunately is NOT supported, this also incluses other mods that adds custom biomes. The reason is because of the absence of biome-based custom triggers for music like `terralith:music.overworld.yellowstone` (In that case, generic overworld music will play instead) so, custom music can't be introduced via Resource Packs.

**Optional Mods:** I strongly suggest using them to a more interesting sound experience alongside with the custom music:
- [Ambient Sounds]: Adds various enviromental sounds for each biome.
- [Endless Music]: Allows you to tweak delay between music. Any mod that lets you change how often music plays works.  <small>**Note:** requires [Mod Menu] to configure delay</small>
- [Presence Footsteps]: Adds custom footsteps sounds for your player.
<details>
<summary>For Players: Recommended Settings</summary>

Music Delay <small>[Endless Music]</small> = No less than 70 (seconds)

Considering your Master Volume is 80%:

- **Ambiental Sounds Volume** <small>[Ambient Sounds]</small> = Volume 30%
- **Music Volume** = Volume 35%
- **Footsteps** <small>[Presence Footsteps]</small> = Global Volume 20%

Those are my recommendations, but of course you can try your own to see what fits best for you.
</details>

<details>
<summary>For Streamers and YouTubers: Copyright</summary>

I cannot stress enough:  **I did not made this music**. Those are all copyrighted by **HOYO-MIX**, **Yu-Peng Chen**, and **Hoyoverse**. Your content WILL be copyright-claimed. 

</details>

<details>
<summary>For Audiophiles: Audio Quality and Loudness</summary>

- All songs are Stereo, 320kbps <small>(exception:  Fontaine)</small>, Ogg Vorbis files. 
- Quiet music stayed quiet, while louder music were normalized to around **-16 LUFS** (for in-game music) and **-10 LUFS** (for menu music) with about 1.5 LUFS of error magin.
- No compression was applied. The dynamic range of all songs are intact.
- All songs were produced by HOYO-MIX and are available on YouTube.

</details>

<details>
<summary>For Wild Modders</summary>

If only there was a mod that enhances the situational music system that reads time of day (day, night, dusk, dawn, midnight), weather (clear, raining, thunderstorm), the current biome (minecraft:plains), dimension (overworld, nether) the player are in, and selects the best music based on a certain set of criterias (day+raining = calm1.ogg), defined by the resource pack...  imagine that.
![Ahh Eto, Bleh](https://media.tenor.com/XnGK5CaQTt4AAAAd/ah-eto-bleh-anime.gif)

</details>


</details>

<details>
<summary>Known Bugs</summary>
Current bugs that are being investigated

- `music.overworld.badlands` won't trigger
    - Workaround applied:  using event trigger `music.overworld.badlands` inside `music.overworld.desert`
- Basalt Deltas plays `music.overworld.deep_dark` music

</details>

[Ambient Sounds]: https://modrinth.com/mod/ambientsounds
[Endless Music]: https://modrinth.com/mod/endless-music
[Presence Footsteps]: https://modrinth.com/mod/presence-footsteps
[Mod Menu]: https://modrinth.com/mod/modmenu
[Large Biomes]: https://minecraft.fandom.com/wiki/Large_Biomes
[Tectonic]: https://modrinth.com/datapack/tectonic
[Terralith]: https://modrinth.com/mod/terralith
[GitHub]: https://github.com/miwafoxl/sounds-of-hydro/releases
