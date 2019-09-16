# FM
This Progressive Web App is a noisy FM synthesizer featuring Web-GL fluid-simulation visuals. The fluid simulation was created by [PavelDoGreat](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation). It was modified by Michael Bauchert into an experimental, FM synthesizer.

Each finger a user places onto the screen activates, then controls the amplitude and frequency of an oscillator. Each oscillator modulates the frequency of the next, creating complex sounds when multiple fingers are on the screen. One finger or a mouse acts more like a theremin as only a single oscillator is active.

The splash screen is not without purpose either; it activates Web Audio via a touch or click event. I think it looks nice too. It's encapsulated in a Web Component.

## Files of Interest
- [script.js]()
- - You can find my modifications by searching for comments starting with //MB
- [index.html]()
- [manifest.json]()
