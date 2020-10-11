```
swipe:
  3:
    up:
      command: "xdotool key ctrl+alt+Down" # Switch to next workspace
    down:
      command: "xdotool key ctrl+alt+Up" # Switch to previous workspace
pinch:
  in:
    command: "xdotool keydown ctrl click 5 keyup ctrl" # Zoom in
  out:
    command: "xdotool keydown ctrl click 4 keyup ctrl" # Zoom out
```
