# Common alignment problems and fixes

Photo time lapses are not video: frames can be minutes, days or months apart, light changes, and objects move. Video stabilizers expect smooth motion between neighbouring frames; still sequences need alignment on what does not move.

| Problem | Cause | Suggested approach |
|---|---|---|
| Fast jitter | Wind, traffic, light tripod | Shift only; alignment area on a fixed foreground/ridgeline |
| Everything off after one frame | Tripod bumped | Straight; check the frames around the jump in the filmstrip |
| Offsets after each visit | Battery swap, camera re-mounted | Perspective |
| Handheld series (days/seasons) | Different viewpoint each time | Perspective; manual alignment for rare failures |
| Slow drift over weeks | Mount sagging or shifting with temperature | Alignment area on stable features |
| Moving clouds/sky fool the alignment | Sky changes between frames | Exclude the sky with a mask or alignment area |
| Cranes, cars, people disturb alignment | Moving elements | Mask them |
| Frame will not align | Blur, bad exposure, too little detail | Check blur detection, align by hand, or remove the frame |
| Nothing to lock onto (eclipse, moon) | Low-texture image | Set an alignment area on the subject; use low-texture handling |
| Flicker between frames | Exposure changes | Use blending between images; shoot in manual exposure next time |

## Before you export

- Browse the whole sequence in the filmstrip (sorted by date).
- Play it in the viewer.
- Check the image shape (original, 16:9, 4:3, square, vertical) so framing is not cropped unexpectedly.
- Save aligned images if you need to analyse them elsewhere (science, measurements).
