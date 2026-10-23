# Web Haptics at TPAC 2027

An approximately 15-minute HTML slide deck introducing semantic Web Haptics to
the Devices and Sensors Working Group.

## Present

Open `index.html` directly in a modern browser. The deck is self-contained and
does not require a build step or network connection.

Controls:

- Arrow keys, Page Up, Page Down, or Space navigate between slides.
- `F` toggles fullscreen.
- `P` pauses or resumes animation.
- Swipe left or right on a touch screen.
- Use the on-screen controls for navigation, fullscreen, and animation pause.

The two scenario slides have replay buttons. In an environment where
`navigator.playHaptics()` is available, those buttons also request the
corresponding semantic effect.

Print from the browser in landscape mode to export a static PDF.

## Sources

- [Web Haptics explainer](https://github.com/WICG/web-haptics/blob/main/readme.md)
- [Current CSS model comparison](https://github.com/WICG/web-haptics/tree/liminzhu-option-b-fragment#comparison)
- [DevTrial instructions](https://github.com/WICG/web-haptics/blob/main/HOWTO.md)

The deck intentionally focuses on the current API story and the live CSS design
decision. It does not cover the historical Alternatives Considered matrix.
