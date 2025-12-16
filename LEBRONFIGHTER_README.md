# LeBron Fighter 🏀👑

A 2D fighting game that combines Street Fighter-style combat with LeBron James basketball theme.

## Overview

**LeBron Fighter** is a browser-based fighting game where you control LeBron James (Lakers purple/gold vs Heat red/black) in intense 2D combat on a basketball court. Battle against CPU or a friend in this fast-paced fighting experience!

## Features

### Game Modes
- **1 Player vs CPU**: Fight against an AI-controlled opponent
- **2 Player Mode**: Local multiplayer - battle a friend on the same device

### Core Mechanics
- **Round System**: Best of 3 rounds - first to win 2 rounds wins the match
- **Health Bars**: Track damage for both players with gradient health displays
- **Special Meter**: Build up by dealing/taking damage to unleash powerful moves
- **Timer**: 90 seconds per round - win by KO or have more health when time expires
- **Combo System**: Chain attacks together for combo multipliers

### Controls

#### Desktop Controls

**Player 1 (Lakers LeBron)**
- `W` - Jump
- `A` - Move Left  
- `S` - Crouch/Block
- `D` - Move Right
- `F` - Punch (5 damage)
- `G` - Kick (8 damage)
- `H` - Special Move / Ultimate

**Player 2 (Heat LeBron)**
- `↑` - Jump
- `←` - Move Left
- `↓` - Crouch/Block
- `→` - Move Right
- `J` - Punch (5 damage)
- `K` - Kick (8 damage)
- `L` - Special Move / Ultimate

#### Mobile/Tablet Controls
Touch devices automatically show on-screen virtual controls:
- **Left D-Pad**: Movement and jumping
- **Right Buttons**: Attack actions (Punch, Kick, Special)

### Special Moves

1. **Heat Check** (Projectile)
   - Cost: 30 special meter
   - Launches a basketball projectile
   - Damage: 15
   - Great for zoning and keeping distance

2. **The Decision** (Ultimate)
   - Cost: 100 special meter (full)
   - Devastating close-range attack
   - Damage: 25
   - Massive screen shake effect

3. **Block** (Defensive)
   - Hold block button to reduce incoming damage by 70%
   - Cannot attack while blocking
   - Perfect for defending against rushes

### Visual Effects
- Screen shake on heavy hits
- Flash effects when taking damage
- Combo counter display
- Particle effects for special moves
- Basketball court arena with 3-point lines
- Character sprites with crowns and #23 jerseys

## Game Flow

1. **Start Screen**: Choose 1P vs CPU or 2P mode
2. **Round Start**: "ROUND X - FIGHT!" announcement
3. **Combat**: Battle until health depletes or timer runs out
4. **Round End**: Winner determined, advance to next round
5. **Match End**: Final winner announced with score display
6. **Replay**: Option to play again or return home

## Technical Details

- Built with vanilla JavaScript (no frameworks)
- HTML5 Canvas for rendering
- 60 FPS game loop
- Responsive design for desktop, tablet, and mobile
- Touch controls with virtual buttons
- Collision detection for attacks and projectiles
- State machine for character states (idle, walking, jumping, attacking, blocking, hit, KO)
- Physics system with gravity

## Tips & Strategies

- **Mix up attacks**: Combine punches, kicks, and special moves
- **Block strategically**: Reduces damage but prevents attacking
- **Manage special meter**: Save for ultimate or use smaller specials
- **Control spacing**: Use projectiles for distance, close in for heavy damage
- **Jump timing**: Avoid projectiles and approach safely
- **Watch the timer**: Play defensively when ahead on health
- **Build combos**: Land multiple hits quickly to maximize damage

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support with touch controls

## Files

- `lebronfighter.html` - Main game file
- `lebronfighter-info.html` - Game information and instructions page

## Integration

The game integrates with the CoolBronGames Firebase leaderboard system to track high scores across all players.

## Credits

Part of **CoolBronGames** - A collection of LeBron James-themed browser games.

Not affiliated with LeBron James, the NBA, or any official entities. Created for entertainment purposes.
