Write a complete, detailed, and self-contained JavaScript code using Three.js to create a 3D version of a classic Super Mario game. The game should run in a web browser, rendering a 3D scene with Mario as a controllable character in a platformer-style level. Include every aspect: scene setup, lighting, camera (orthographic for a 2D-like feel but with 3D depth), Mario's model and animations, level design with platforms, coins, enemies (like Goombas and Koopas), power-ups (mushrooms, fire flowers), collision detection, physics (gravity, jumping, running), keyboard controls, scoring system, lives, sound effects, and a simple HUD (heads-up display) for score and lives.

Key requirements:
- Use Three.js for all 3D rendering, including importing via CDN or assuming it's included.
- Mario should be a 3D model (you can use a simple rigged mesh or GLTF loader for a basic Mario model; if no external model, create a placeholder using basic geometries like boxes and spheres for body parts).
- Implement animations: idle, running, jumping, dying.
- Level: Create a simple Mario-like level with ground, question blocks (that release coins or power-ups when hit), bricks (breakable), pipes, and a flagpole at the end to complete the level.
- Enemies: Goombas that walk back and forth and can be stomped; Koopas that turn into shells when stomped.
- Power-ups: Mushrooms that make Mario grow (scale up), fire flowers that allow shooting fireballs.
- Physics: Realistic jumping with gravity, momentum for running, collision with platforms/enemies/items.
- Controls: Arrow keys or WASD for movement/jump, space for jump, Ctrl for fire (if powered up).
- Audio: Include background music and sound effects for jumps, coin collection, enemy stomp, etc. (use HTML5 Audio or Three.js AudioLoader; provide placeholder URLs or assume free assets).
- Game states: Start menu, playing, game over, level complete.
- Performance: Optimize for smooth 60 FPS, with requestAnimationFrame loop.
- Make the code modular: Separate functions for init, animate, handleInput, updatePhysics, etc.
- Include comments explaining each section.
- Output the full HTML file with embedded JavaScript, so it can be copy-pasted and run directly in a browser (include <script src="https://threejs.org/build/three.js"></script> or similar).
- Handle edge cases: Mario falling off the level (lose life), multiple lives (3 by default), respawn, win condition.

Ensure the code is error-free, tested in concept, and as close to a fully playable game as possible within Three.js constraints. If external assets are needed (models, textures, sounds), provide instructions on where to source them or use procedural generation as fallbacks.

