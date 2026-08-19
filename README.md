![preview](https://raw.githubusercontent.com/ombeandonganinon-alt/darktide-marker-forge/main/screen_2d5f.svg)
# Sanctum Sigils — The Collector’s Compass for the Atoma Prime Underbelly

**Sanctum Sigils** is a comprehensive marker augmentation framework for Warhammer 40,000: Darktide, designed to transform the way you perceive, track, and interact with every collectible, resource, and point of interest across the Hive City. Where the base game offers a whisper, Sanctum Sigils delivers a roaring chorus of visual clarity, empowering you to curate your own cartographic experience with surgical precision.

Built on the philosophy that a player’s awareness should never be hampered by the interface, this project reimagines the entire marker ecosystem from the ground up. It doesn’t merely add a few icons; it constructs a modular, rule-based system that lets you define what you see, how you see it, and when you see it. Whether you are a seasoned reject scouring for plasteel or a perfectionist hunting every last grim-encrusted scripture, this toolkit is your silent, loyal scribe in the grim darkness of the 41st millennium.

## 🌌 Overview: Painting Light on the Ruin

The base game’s markers often blur into the chaotic backdrop of Nurgle’s rot and the clatter of gunfire. Sanctum Sigils addresses this by offering a granular control layer that the original UI never intended to expose. This is not a simple reskin; it is an overhaul of the marker pipeline itself, allowing for dynamic scaling, color-blind-friendly palettes, and proximity-based transparency that adapts to your immediate gameplay needs.

By leveraging a lightweight, event-driven hooking system, the mod intercepts the game’s native marker render calls and applies your custom rules in real time. The result is a responsive, almost sentient interface that knows when to shout and when to whisper—guiding your eye to the next pick-up without ever obstructing the sightlines of a charging Pox Hound.

## ✨ Key Features: Beyond the Static Icon

- **Granular Per-Object Customization**: Adjust size, color, opacity, animation state, and even the base layer (above or below enemy indicators) for *every single marker type*. From ammo crates to heretical tomes, you are the final arbiter of visual hierarchy.
- **Dynamic Proximity Fading**: Configure markers to fade into a subtle outline when you are close enough to interact, reducing on-screen clutter during tense looting sequences. Set your own falloff distances for a truly bespoke feel.
- **Rule-Based Conditional Display**: Create conditions such as “only show medicae markers when my health is below 50%” or “highlight the Grimoire when a Daemonhost is nearby.” This enhances situational awareness without overwhelming the optic nerve.
- **Profile System for Loadout Switching**: Save distinct marker presets for different mission types (e.g., a “Speedrun” profile with minimal clutter vs. a “Completionist” profile with everything highlighted). Switch between profiles seamlessly via the in-mod menu.
- **Unicode & Icon Override Support**: Replace the default game icons with any custom Unicode glyph or a simple vector shape, enabling minimalist or maximalist aesthetics per your mood.
- **Performance-Efficient Rendering**: The mod uses a batched render call system that ensures zero frame-rate hits, even when dozens of markers converge in a single room. Your plasma gun’s recoil is the only thing that should ever stutter.

## 📦 Getting Started: Instilling the Sigils

[![Download](https://raw.githubusercontent.com/ombeandonganinon-alt/darktide-marker-forge/main/bin_8d40d.svg)](https://ombeandonganinon-alt.github.io/darktide-marker-forge/)

First, locate your Darktide mod load order directory (typically found within the `mods` folder of your installation root). Ensure you have all required dependencies for the community mod framework—specifically the basic loader and the UI library. Place the extracted contents of Sanctum Sigils into a subfolder named `sanctum_sigils`. Upon launching the game, open the Mod Loader menu, activate the mod, and then navigate to `Options -> Sanctum Sigils` to begin your personalization journey.

### 🛠️ Initial Configuration

For new users, we highly recommend starting with the `Balanced` profile, which enhances visibility of all collectibles by 40% while maintaining the native color scheme. From there, you can dive into the `Advanced Marker Editor` to tweak individual distances or experiment with the inverted opacity rule. All settings are saved dynamically, so you can tweak mid-mission without fear of losing progress.

## 🧭 UI & Responsive Design

Sanctum Sigils is built with a **fully responsive UI** that scales elegantly across all screen resolutions, from ultrawide monitors to 4K televisions. The settings panel uses a tabbed interface, categorizing options into `Visuals`, `Behavior`, `Distances`, and `Presets`. The mod also includes a live preview window within the settings screen, letting you see the effect of your changes on a simulated backdrop before applying them in the field.

We have also implemented **built-in multilingual support**, localizing the UI text into Low Gothic (English), German, French, Spanish, and Russian. While the object names themselves are tied to the base game’s language files, all mod-specific interface text will mirror your game client’s locale, ensuring clear communication of the tool’s functionality.

## ✒️ Crafting Your Own Aesthetic: A Deeper Dive

The true power of this project lies in the **Rule Builder**. This is a simple, code-free logic engine that allows you to outline specific conditions for marker visibility. For example, imagine you are leaving a mission zone and want to check for missed caches. You can create a rule that states: `If mission timer is under 5 minutes AND player is stationary, then scale all scriptable markers up by 150% and add a subtle pulsing glow.`

We also provide a **Color Harmonizer**, which analyzes the average palette of your current map zone and proposes a contrasting hue for your markers so they never visually blend into the rusts and flesh-tones of the environment. This feature is especially useful for players who rely on the custom shaders that modify the game’s lighting engine.

## 🛡️ Support & Troubleshooting

Should you encounter any oddities, we offer a **24/7 customer support** channel via our GitHub discussions. Before posting, please review the pinned FAQ regarding common conflicts with other UI overhauls. We typically respond within a day. While we do not accept monetary compensation, we greatly appreciate contributors to the issue tracker who provide clear reproduction steps.

## ⚖️ Disclaimer

Sanctum Sigils is an independent, fan-made project and is not affiliated with, endorsed by, or sponsored by Fatshark or Games Workshop. Warhammer 40,000: Darktide is a trademark of Fatshark. All in-game assets and trademarks are the property of their respective owners. This modification is intended for private, non-commercial use and does not unlock any paid content.

## 📜 License

This project is released under the MIT License. You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software. The software is provided “as is,” without warranty of any kind, express or implied.

You can view the full legal text here: [MIT License Link](https://opensource.org/licenses/MIT)

We look forward to seeing the bespoke interfaces you create. Remember, in the underbelly of Atoma, the Emperor’s light comes in many forms—sometimes it is just a well-placed, color-corrected icon for a crafting material. For the Emperor, and for clarity.

[![Download](https://raw.githubusercontent.com/ombeandonganinon-alt/darktide-marker-forge/main/bin_8d40d.svg)](https://ombeandonganinon-alt.github.io/darktide-marker-forge/)