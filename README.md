# Ice Boat Racer

Minecraft ice-boat racing in the browser with OpenBoatUtils physics, BoatCam and 2D/3D views.

This repository is the public website. It is updated automatically when a track is published from the private dev build.

- `index.html` - the game (play mode)
- `tracks/index.json` - published track list
- `tracks/<id>.json` - track data (blocks, regions, OpenBoatUtils settings)

## Link parameters

- `?track=<id>` open a track
- `&mode=RALLY_BLUE` apply an OpenBoatUtils mode (name or 0-24); repeatable
- `&exclusive=BA` reset to vanilla, then apply a mode
- `&obu=defaultslipperiness 0.98;blockslipperiness 0.989 packed_ice` run OpenBoatUtils commands
- `&slip= &yaw= &fwd= &back= &turn= &lateral= &brake= &maxspeed= &maxres= &stack=1` set values
- `&vanilla=1` ignore the track's OpenBoatUtils settings
