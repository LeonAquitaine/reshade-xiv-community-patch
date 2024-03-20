# GPosingway

![GPosingway Mascot](https://github.com/GPosingway/GPosingway/assets/18711130/c919c030-dff2-47e8-905d-f52d098aaa45)

This is a drop-in package for Final Fantasy XIV containing a stable collection of shaders, textures, and presets gathered from the community and beyond. GPosingway aims to ensure that presets will work as intended by its creators by avoiding conflicts, mismatches and missing files, giving users a consistent experience.

---

**GPosingway version**: Release 5  
**Currently supported ReShade version**: 6.0.1 with add-on support

<a href='https://github.com/gposingway/gposingway/releases/latest'>![download](https://github.com/gposingway/gposingway/assets/18711130/e29bc268-09d3-4b00-9d80-a5d6f964c5de)</a>

---

## Features

- **Stable Baseline:** GPosingway offers a carefully curated collection of distributable shaders and textures, providing a stable foundation for your ReShade setup. This baseline helps avoid compatibility issues across different preset collections, ensuring a consistent and reliable experience.

- **Community Contributions:** GPosingway integrates presets, shaders, and fixes contributed by the FFXIV community; the patch contains a comprehensive package that reflects the diverse preferences and styles of preset creators.

- **Easy Integration:** Installing GPosingway is a breeze. Donload, unzip, drop it into your existing FFXIV installation, and you're ready to go. No complex configurations or manual tweaks required.

## Q&A

### How does it work?

The package contains all the necessary elements for the majority of preset collections to work as intended by their respective creators in the most common usage scenarios; some community contributions like `FFKeepUI` were added, while some default ReShade shaders were renamed or removed to avoid conflicts.

### I have ReShade (or other ReShade-based injectors like GShade) already installed. How should I proceed?

You can rename your pre-existing `reshade-shaders` and `reshade-presets` folders to something else prior to deploying GPosingway; this way you can switch between GPosingway and your previous collection. There are **no guarantees** that GPosingway will work with different ReShade versions, however.

### Can I use `[Insert preset collection name here]` with GPosingway?

Absoutely! The only thing to keep in mind is that *you don't need to use bundled shaders anymore*, so just ignore any instructions to copy `.fx` and `.fxh` files to the `reshade-shaders\shaders` folder; GPosingway should have everything that most presets need to avoid conflicts.

### Help! I can't find the `[Insert shader collection name here]` shaders!

Redistribution is strictly forbidden for some shader collections, like [iMMERSE](https://github.com/martymcmodding/iMMERSE/blob/main/LICENSE); in most cases you can download and install these with minimal issues, but YMMV.

### Are there plans to support newer ReShade versions in the future?

Yes, the plan is to support newer ReShade versions in future updates, but in a different format fully compatible with the ReShade installation tool; this version is meant as a starting point.
  
## Contribution Guidelines

We welcome contributions from the FFXIV community. If you have a preset collection, shader, or fix that you believe would benefit GPosingway users, feel free to submit a pull request!
  
Before contributing, please review our [contribution guidelines](md/contributing.md) to ensure a smooth collaboration process.

## Support and Feedback

If you encounter issues, have suggestions, or simply want to connect with other GPosingway users, visit the [Sights of Eorzea Discord server](https://discord.com/servers/sights-of-eorzea-1124828911700811957). We value your feedback and strive to create an inclusive and vibrant community.

## Included Preset collections

| Collection | Creator | License | Notes | Suggested Hashtag |
| --- | --- | --- | --- | --- |
| AcerolaFX | [Garrett Gunnell](https://github.com/GarrettGunnell) | MIT - [License](https://github.com/GarrettGunnell/AcerolaFX?tab=MIT-1-ov-file) | [Download](https://github.com/GarrettGunnell/AcerolaFX/archive/refs/heads/main.zip)  | `#AcerolaFX` |
| IpsuShade | [Ipsusu](https://twitter.com/ipsusu) | [License](https://github.com/ipsusu/IpsuShade/blob/master/LICENSE.md) | [Download Page](https://github.com/ipsusu/IpsuShade)  | `#IpsuShade` |
| WiFi | [Wi-Fi ₍ᐢ.ˬ.ᐢ₎ 黒うさぎ](https://twitter.com/wifi_photospire) | MIT | [Download Page](https://potatoworshiper.wixsite.com/jagaimo-no-sekai/wifi-presets)  | `#WifiPresets` |
| Witch's Presets | [Mana](https://github.com/WitchMana) | WTFPL | [Repository](https://github.com/WitchMana/WitchsPresetsReshade)  | `#witchspresets` |
| Yomigami Okami | [Yomy](https://twitter.com/Yomigammy) | MIT - [License](https://github.com/MeynanAneytha/YomigamiOkami-reshade-shaders/blob/main/LICENSE) | Original [ReShade port](https://github.com/MeynanAneytha/YomigamiOkami-reshade-shaders#yomigamiokami-reshade-560-port) by [Meynan Aneytha](https://twitter.com/meynan_ffxiv) | `#okamishader` |

You can find a list of all included shader collections and their respective licenses [here](md/shader_licenses.md).

---

[GPosingway · a ReShade / XIV Community Patch](https://github.com/GPosingway/GPosingway/tree/main) is [licensed](license.md) under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1) 
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1">
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1">

Individual work elements (e.g. presets, shaders, textures) may have distinct distribution terms; check the list of included works above for their respective licenses.
