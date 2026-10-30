BACKROOMS — CAPTAIN CLARK / SPAWN BUTTON

Run in this folder:
  python -m http.server 8000

Then visit:
  http://localhost:8000

CONTROLS
  WASD / ARROWS : move
  Mouse         : look
  Shift         : sprint
  B             : spawn / reposition Captain Clark 4.5 meters in front of you
  Escape        : pause (use the SPAWN CAPTAIN CLARK button on the pause menu)
  M             : mute

CAPTAIN CLARK
  He starts unspawned; choose when the threat appears.
  After spawn he faces the player, waits two seconds, then hunts normally.
  Subsequent B presses reposition the same monster without spawning clones.
  If the space ahead is blocked, the game tries a closer, nearby opening;
  if none is safe, he does not teleport into a wall.

MONSTER HEARING
  window.backroomsPlayer.noiseLevel : 0 still, 1 walking, 5 sprinting

Requires internet for the Three.js CDN, plus the included model and animation files.
