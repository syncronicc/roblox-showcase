# UI Kit #1

A Roblox UI kit using modular components along with lifecycle-based windows and physics-based animations. A central module loader that contains all modules is used; each UI window is considered a module with the following life cycle states:

- Startup: post-game loading
- Entered: UI activation
- Exited: UI deactivation 

This guarantees proper isolation and consistent transitions between UI states. Animations are performed using a physics model using springs rather than tweens.

https://github.com/user-attachments/assets/7c15db8f-09e5-490b-934a-e6a728f57b6b
