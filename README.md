📅 Daily Work Log
Day 1
Set up basic HTML and CSS structure.

Implemented pixel-style font and retro UI layout.

Added initial asset placeholders (clouds, road, car, hero).

Day 2
Created Line and Car class structures in JS.

Programmed map generator logic with curves and elevation.

Integrated static objects (trees, finish line).

Day 3
Implemented game loop and player controls (left, right, accelerate, brake).

Added countdown start mechanic with sound feedback.

Set up HUD: speed (tachometer), time, score, lap.

Day 4
Added AI cars and basic collision detection.

Implemented speed penalties upon off-road and collision.

Introduced finish line logic and victory condition.

Day 5
Audio: background music and sound effects (engine, honk, beep).

Developed cloud parallax and dynamic road rendering.

Completed game UI polish and highscore tracking.

💡 Ideas Implemented
🎮 Gameplay Mechanics
Lane-Based AI Traffic: Inspired by OutRun and Rad Racer, enemy cars spawn in pre-set lanes with randomized positions and speeds.

Curved Roads and Elevation: Using a procedural segment-based approach, curves and hills were randomly generated to mimic classic 2.5D racers.

Insert Coin + Countdown: Reflecting arcade culture, game start requires a 'C' key press and initiates a nostalgic 3-2-1 countdown.

Lap Timer and Tachometer: Real-time tracking of speed and lap time inspired by arcade racing dashboards.

🎨 Visual/Audio Design
Retro pixel-art style consistent with 80s arcade games.

Dynamic parallax clouds for depth.

Chiptune soundtrack and synth-style SFX.

⚠️ Problems Faced
1. Curve Projection & Scaling
Issue: Getting the correct perspective distortion for roads on curve transitions.

Solution: Fine-tuned scaling formulas using fixed depth (camD) and horizontal offset adjustments.

2. AudioContext Autoplay Restrictions
Issue: Some browsers blocked autoplay of sounds.

Solution: Delayed initialization until user interaction (pressing ‘C’).

3. Collision Accuracy
Issue: Collisions sometimes didn’t register at high speeds.

Solution: Applied offset tolerance and adjusted isCollide() radius sensitivity.

4. Performance
Issue: Rendering too many elements caused lag.

Solution: Limited number of lines (N = 70) and used requestAnimationFrame throttle for 25 fps.

🚀 Future Implementation Ideas
✅ Improvements
Smoother transition animations for curve changes.

Add gear system and drifting mechanics.

Improve collision physics with bounce-back animation.

🌐 Features to Add
Leaderboard integration using backend or localStorage.

Multiplayer mode using WebRTC or WebSocket.

Mobile controls (touchscreen accelerometer or virtual buttons).

🎨 Polish
Add environment variety (day/night cycle, snow/rain).

Introduce character selection and car upgrades.

Animated sprites for cheering crowd or roadside signs.
