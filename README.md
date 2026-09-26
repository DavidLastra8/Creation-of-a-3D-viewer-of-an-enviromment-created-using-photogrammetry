# Photogrammetry 3D Viewer

This project is about the creation of a 3D viewer of an environment built entirely with photogrammetry inside Unreal Engine 5. The environment was captured and processed following a specific pipeline, which is documented step by step inside this guide: [Photogrammetry Indoor Guide](https://github.com/DavidLastra8/Photogrammetry-indoor-guide).

The goal of the viewer is to let users explore a real space that has been entirely digitized, and to show the results that can be achieved by following the pipeline described in the guide.
## Viewing Modes

When launching the application, a menu lets you choose between two ways of exploring the environment:

- **Desktop Mode:** it was designed for users who can't afford to use a VR headset. It offers a standard first-person experience and it is controlled using keyboard and mouse.
- **VR Mode:** it was designed for users who want a more immersive experience. It lets you explore the environment in a deeper and more personal way with the help of a VR headset, moving around the scene by teleporting around the scene.

### VR Requirements

To use VR Mode, a PC VR headset must be connected before launching the application (for example, a Meta Quest through Quest Link / Air Link, or any headset compatible with SteamVR), with its OpenXR runtime set as active inside the settings.

## Controls

### VR Mode (Meta Quest / PC VR headsets)

| Action | Control used |
|---|---|
| Teleport | Push the right thumbstick forward, aim and release |
| Turn | Right thumbstick left / right (45° snap turns) |
| Menu | Left controller menu button |

### Desktop Mode

| Action | Control used |
|---|---|
| Move | W A S D Keys |
| Look around | Mouse |
| Menu | Esc Key |
