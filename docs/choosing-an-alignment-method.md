# Choosing an alignment method

Futura Time Lapse offers three methods. Pick the one matching how your camera moved, and switch at any time to compare in the viewer.

| Method | What it corrects | Typical situation |
|---|---|---|
| **Shift only** | Up/down/left/right movement | Solid tripod shaken by wind or traffic. Fastest. |
| **Straight** | Shift + slight rotation | Tripod bumped or re-levelled. |
| **Perspective** | Shift + rotation + change of viewing angle | Camera re-mounted between visits, or handheld shots from roughly the same spot. |

## Quick decision guide

1. Camera never touched, only vibrating? Start with **Shift only**.
2. Horizon looks tilted in some frames? Try **Straight**.
3. Viewpoint visibly changed (parallax, different angle)? Use **Perspective**.
4. Subject has little texture or contrast, as in a solar eclipse? See [Low-texture subjects](#low-texture-subjects).
5. Still one stubborn frame? Align that frame by hand.

## Low-texture subjects

For a solar eclipse or a similar subject against a dark sky, ordinary scene details may be too scarce to align on. Futura Time Lapse can align low-contrast images:

1. Set the **alignment area** around the subject.
2. Start with **Shift only** if the main movement is drift, then compare the result in the viewer.
3. Check the sequence frame by frame and align any stubborn frames by hand.

This is an approach for low-texture images, not a separate alignment method.

## Tips

- For landscapes and other scenes with a fixed foreground, choose an **alignment area** on stable features (ridgeline, neighbouring buildings, roads) and exclude the moving sky.
- Use a **mask** for cranes, traffic, people or any moving element.
- Compare methods in the viewer before exporting.

> Community contributions welcome: add your own before/after cases in [CONTRIBUTING.md](../CONTRIBUTING.md).
