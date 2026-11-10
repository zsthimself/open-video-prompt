# Open Video Prompt Dataset (94 Cinema-Grade AI Video Prompts)

Curated, camera-calibrated prompt blueprints for **Kling**, **MiniMax Hailuo H3**, **Luma Ray-2**, and **Tencent Hunyuan Video** — maintained by [OpenVideoGenerator](https://openvideogenerator.com/).

## Categories Included

- **cinematic**: 15 structured blueprints
- **anime**: 13 structured blueprints
- **commercial**: 13 structured blueprints
- **shorts**: 13 structured blueprints
- **aerial**: 10 structured blueprints
- **scifi**: 10 structured blueprints
- **portrait**: 10 structured blueprints
- **nature**: 10 structured blueprints

## Sample Blueprints

| Title | Category | Recommended Engine | Camera Movement |
| :-- | :-- | :-- | :-- |
| [Dune Arrakis Spice Harvester Massive Sandstorm](https://openvideogenerator.com/prompts/dune-spice-harvester-sandstorm-imax) | cinematic | hunyuan | Extreme Wide Low-Altitude Trucking Shot with Parallax Scale |
| [1940s Film Noir Detective Wet Alley Silhouette](https://openvideogenerator.com/prompts/film-noir-detective-rain-silhouette) | cinematic | minimax | Slow Dutch Angle Push-In at Low Chest Level |
| [Medieval Fortress Siege Burning Trebuchet Launch](https://openvideogenerator.com/prompts/medieval-siege-catapult-fireball-slowmo) | cinematic | kling | Fast Tracking Arc Shot following the Fireball Trajectory |
| [Makoto Shinkai Train Platform Sunset Farewell](https://openvideogenerator.com/prompts/makoto-shinkai-train-platform-sunset-farewell) | anime | minimax | Slow Lateral Dolly with Atmospheric Depth Parallax |
| [Ufotable Demon Slayer Style Flame Katana Slash](https://openvideogenerator.com/prompts/ufotable-fiery-dragon-katana-strike) | anime | kling | Dynamic 360 Orbit Spiral with Impact Kinetic Snap-Zoom |
| [1980s Retro City Pop Tokyo Highway Night Drive](https://openvideogenerator.com/prompts/retro-80s-city-pop-highway-night-drive) | anime | minimax | Low-Slung Car-Mounted Tracking Rig along Rear Bumper |
| [Apple-Style Minimalist Titanium Gadget Exploded View](https://openvideogenerator.com/prompts/apple-titanium-gadget-exploded-macro) | commercial | kling | Slow 360 Degree Macro Orbit with Smooth Axial Tilt |
| [Luxury Sports Car Wet Hairpin Drift Automotive Commercial](https://openvideogenerator.com/prompts/porsche-911-rainy-hairpin-drift-ad) | commercial | luma | Low-Angle Chase Arm sweeping from front fender to rear three-quarters |
| [Haute Horlogerie Skeleton Tourbillon Mechanical Macro](https://openvideogenerator.com/prompts/swiss-horology-tourbillon-gear-macro) | commercial | kling | Probe Lens Slow Push-Through past Balance Spring into Escapement |
| [Viral Street Food Giant Cheese Wheel Pasta Flambé](https://openvideogenerator.com/prompts/viral-street-food-cheese-wheel-pasta-flame) | shorts | minimax | Dynamic Overhead Drop-Down to Tight 45° Hero Angle |
| [Satisfying Rainbow Kinetic Sand ASMR Knife Slice](https://openvideogenerator.com/prompts/satisfying-rainbow-kinetic-sand-knife-slice) | shorts | kling | Locked-Off Macro Side Profile with Smooth Vertical Tilt |
| [Adrenaline First-Person POV Rooftop Gap Parkour Jump](https://openvideogenerator.com/prompts/parkour-rooftop-gap-jump-first-person-pov) | shorts | luma | Head-Mounted POV with Natural Horizon-Leveling and Body Sway |

## Run Prompts Online or via Developer MCP

- **Web Studio**: Try any prompt interactively at [OpenVideoGenerator](https://openvideogenerator.com/prompts) (50 free welcome credits on Google sign-in).
- **Developer MCP Server**: Connect Cursor, Claude Code, or Antigravity directly to `https://openvideogenerator.com/api/mcp`.

## Dataset Schema (`prompts.json`)

Each record contains `slug`, `title`, `category`, `recommendedModel`, `aspectRatio`, `cameraMovement`, `lighting`, `fps`, `prompt`, `negativePrompt`, and `liveUrl`.

## License

CC0 1.0 Universal (Public Domain Dedication) — free for commercial, research, and generative training workflows with attribution link back to [openvideogenerator.com](https://openvideogenerator.com/).
