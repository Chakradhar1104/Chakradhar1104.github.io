# Chakradhar · Game Developer Portfolio

A portfolio that plays like a game: a loading screen, a title screen ("press any key"), a main menu, a gallery of games with looping highlight reels, and a full page for each game.

**Live site:** https://chakradhar1104.github.io (also at https://chakradhar-portfolio-iota.vercel.app)

## Games

| Game | Engine | What it is |
|---|---|---|
| **Gravity Architect** | Unity 6 (URP), C# | Space-rescue puzzle platformer for PC and Android: spend a limited supply of platforms on energy bridges to reach the rescue shuttle. |
| **Science Quest VR** | Unity 6, OpenXR | Educational science game playable in a VR headset or with keyboard and mouse: three labs (recycling, planets, molecules) with quizzes. |
| **Obstacle Assault** | Unreal Engine 5, C++ | Third-person sky-high obstacle course with moving, rotating and collapsing platforms built from a custom C++ platform actor. |

## Download the games

Playable builds are in the [Game builds release](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/tag/builds-v1).

| Game | Download | How to run |
|---|---|---|
| Gravity Architect | [Windows (zip, 89 MB)](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/GravityArchitect-Windows.zip) · [Android (APK, 58 MB)](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/GravityArchitect-Android.apk) | Unzip and run `GravityArchitect.exe`, or install the APK on an Android phone. |
| Science Quest VR | [Windows / PC VR (zip, 43 MB)](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ScienceQuestVR-Windows.zip) | Unzip and run `ScienceQuestVR.exe`. For VR, start Quest Link or SteamVR first. |
| Obstacle Assault | [Part 1](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part1.rar) · [Part 2](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part2.rar) · [Part 3](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part3.rar) · [Part 4](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part4.rar) · [Part 5](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part5.rar) · [Part 6](https://github.com/Chakradhar1104/Chakradhar1104.github.io/releases/download/builds-v1/ObstacleAssault-Windows.part6.rar) (2.4 GB total) | Download all 6 parts to one folder, extract part 1 with WinRAR or 7-Zip, run `ObstacleAssault.exe`. |

The builds are unsigned, so Windows SmartScreen may warn: choose **More info**, then **Run anyway**.

## How the site is built

- One self-contained `index.html` (HTML, CSS and vanilla JavaScript, no framework or build step).
- Original desert-citadel art drawn in code: a parallax skyline on canvas, an animated hourglass that turns over when its sand runs out, and rotating star rings.
- Light and Shadow themes, optional sound effects (Web Audio), keyboard navigation, and small achievements ("trials").
- Highlight reels are H.264 MP4s that autoplay muted in the gallery.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Contact

- Email: chakradharguvalla11@gmail.com
- LinkedIn: https://www.linkedin.com/in/chakradhar-guvalla-23571a41a
- GitHub: https://github.com/Chakradhar1104
