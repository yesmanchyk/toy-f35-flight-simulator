# ✈️ Toy F-35 Flight Simulator (WebXR for Meta Quest & 2D)

An interactive 3D WebGL flight simulator and stylized toy F-35 Lightning II jet with full **Meta Quest WebXR VR** support, vanilla WebGL rendering, procedural Web Audio sound synthesis, and real-time aerodynamics.

## 🎮 Live Demo
Play the flight simulator online via GitHub Pages:
https://yesmanchyk.github.io/toy-f35-flight-simulator/

## 🥽 Meta Quest VR Features
- **Immersive WebXR**: Seamless one-click VR entry in Meta Quest Browser (Quest 2, 3, 3S, and Pro).
- **Dual VR Camera Modes**:
  - **VR Chase View (Default)**: Comfortable stereoscopic third-person view floating behind the jet with zero motion sickness.
  - **VR Cockpit View**: 6DOF head-tracked interior cockpit view with glare shield, dashboard MFD, and glass HUD combiner plate.
  - Quick camera toggle using the **Left Controller Grip** or **Y Button**.
- **Touch Controller Mapping**:
  - **Right Stick**: Flight stick pitch (pull to climb, push to dive) & banking roll (left/right).
  - **Left Stick**: Rudder yaw (left/right) & throttle (forward/back).
  - **Right Trigger**: Afterburner boost with roaring engine audio and fire plumes.
  - **Left Trigger**: Airbrake deceleration.
  - **A / X Buttons**: Quick flight reset back to the carrier catapult deck.

## 🕹️ Desktop & Mobile 2D Controls
- **Pitch Up / Down**: `S` / `W` (or Down / Up Arrow keys)
- **Bank Left / Right**: `A` / `D` (or Left / Right Arrow keys)
- **Rudder Yaw**: `Q` / `E`
- **Throttle**: `Shift` (accelerate) / `Ctrl` (decelerate)
- **Afterburner Boost**: `Space` (maximum thrust + animated fire plume)
- **Pitch Mode**: `I` key (toggle between Flight Stick and Arcade)
- **Camera Views**: `C` key (Chase Cam, Cockpit HUD, Flyby Cam)
- **Time of Day**: `T` key (Noon ☀️, Sunset 🌅, Night 🌙)
- **Audio**: `M` key (toggle engine sound effects)
- **Reset**: `R` key

## 🚢 World & Environment
- **Aircraft Carrier**: Catapult flight deck with launch tracks, deck edge lines, and command tower island.
- **Island Archipelago**: Four lush tropical atolls with sandy beaches and mountain summits.
- **Aerobatic Course**: 12 glowing neon waypoint rings to thread through for high scores.

## 📦 3D Model Assets
- `toy_f35_jet.stl`: Stand-free 3D printable model for slicers (Cura, Bambu Studio, PrusaSlicer).
- `toy_f35_jet.obj` & `toy_f35_jet.mtl`: 3D mesh for Blender, Unity, or Unreal Engine.
- `toy_f35_viewer.html`: Standalone interactive 3D model inspection viewer.
