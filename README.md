# PHANTOM FIGHTER ⚡

A hand-controlled Galaga-style space shooter with MediaPipe gesture tracking. Control your fighter jet with hand gestures and fight waves of enemies in a retro 8-bit neon city.

## Live Demo

Play now: https://arrakistacos.github.io/phantom-fighter/

## Game Features

### Hand Gesture Controls
- **Fist** → Move your ship only
- **1 Finger (☝)** → Fire Vulcan Gun (unlimited bullets)
- **2 Fingers (✌)** → Fire Inferno Flamer (requires boost, 8s fuel)
- **3 Fingers (🤟)** → Fire Nova Bombs (requires boost, 3 max)

### Weapons
- **VULCAN**: Straight-fire bullets, 8 shots/second, 10 damage each
- **INFERNO**: Cone of particles, each hits for 2 damage/frame
- **NOVA**: Slow orb that explodes on contact, 200 damage radius

### Enemy Types
1. **GRUNT** (Level 1+): Green insect, kamikaze dive attacks
2. **SHOOTER** (Level 2+): Red diamond, fires bullets downward
3. **ZIGZAGGER** (Level 2+): Magenta arrowhead, erratic sine-wave movement
4. **LASER DRONE** (Level 3+): Cyan drone, charges then fires beam attacks
5. **TANK** (Level 4+): Heavy armored unit, spread fire pattern

### Power-ups
- **INFERNO BOOST** (orange): Unlock Inferno weapon
- **NOVA BOOST** (magenta): Unlock Nova bombs
- **SHIELD BOOST** (blue): +3 shield segments
- **LIFE UP** (red): Extra life (max 5)

### Gameplay
- 3 starting lives, 3 shield segments per life
- 5 progressive levels with increasing difficulty
- Procedurally scrolling neon city background
- Screen shake on hits, particle explosions
- Retro 8-bit pixel art aesthetic
- Web Audio API sound effects

## Technical Details

- **Pure HTML5 Canvas**: No frameworks, no build tools
- **MediaPipe Hands**: Real-time hand gesture recognition
- **Web Audio API**: Dynamic beep synthesis
- **Vanilla JavaScript**: Single-file implementation
- **Responsive Canvas**: 800×600 with scanline filter

## How to Play

1. Open https://arrakistacos.github.io/phantom-fighter/
2. Click "ALLOW CAMERA & START" to enable hand tracking
3. Position your hand in front of the camera
4. Move hand left/right to control your ship
5. Use finger gestures to fire weapons
6. Destroy all enemy waves to complete each level
7. Survive to reach the final victory screen

## Installation (Local)

```bash
# Clone the repository
git clone https://github.com/arrakistacos/phantom-fighter.git
cd phantom-fighter

# Open in browser (requires HTTPS for camera access)
python -m http.server 8000
# Navigate to https://localhost:8000
```

Note: Camera access requires HTTPS in production (GitHub Pages handles this automatically).

## Files

- `index.html` - Complete game in a single self-contained HTML file
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow
- `README.md` - This file

## Credits

Created with:
- MediaPipe Hands (Google) for gesture recognition
- Press Start 2P font (Google Fonts)
- Canvas API for graphics
- Web Audio API for sound

## License

This project is open source and available under the MIT License.

---

**Ready to become a Phantom Fighter? Take control and defend the neon city!**
