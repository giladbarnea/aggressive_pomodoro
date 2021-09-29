# Create a process that is unkillable
- Kernel bound?
- Root permissions
- Handles SIG*
- Rewrites itself

# Block what exactly?
- keyboard / mouse input?
- Kill windows?
- [Modal?](https://github.com/paulbrodner/take-a-break)

# Interact with X
- [xkeysnail](https://github.com/mooz/xkeysnail)
  - xkeysnail is yet another keyboard remapping tool for X environment written in Python
  - runs in sudo
- [kinto](https://github.com/rbreaves/kinto)
  - low-level remapper of global shortcuts
  - gui
  - relies on xkeysnail
- [python-libxdo](https://github.com/rshk/python-libxdo/blob/master/xdo/xdo.py)
  - python implementation of libxdo (6y old)
  - libxdo is the lib behind xdotool
- [wmctrl-py](https://github.com/iyadahmed/wmctrl-py)
  - no deps, no subprocess calling
- [xlib docs](https://tronche.com/gui/x/xlib/)

# Compile to bin?
- Cython?
  - makes it easier to kill process by malicious user?

# Features
- Detect idle time and count towards breaks automatically
