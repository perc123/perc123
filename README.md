## Fanis Gioles

Audio and software engineer based in Berlin.

Currently Systems Engineer / QA at sedna GmbH, working on audiovisual hardware with multichannel Dante audio. Background: B.Sc. Informatik (HTW Berlin), Master of Music and Staatsexamen (HfMT Hamburg). Previously XR developer at Fraunhofer IPK, building interactive applications in Unity / C# across major HMD platforms.

I work on real-time interactive audio systems — DSP, spatial audio, neural audio, plugin internals, validation engineering, XR — across C++, Rust, C#, Python, Web Audio, and Max/MSP. My bachelor thesis combined a Unity XR interface with a Max/MSP spatial audio engine (IRCAM spat5), driving binaural rendering in real time over OSC.

### Selected work

- **[AudioFilterLib](https://github.com/perc123/AudioFilterLib)** — High-performance C++17 library for real-time audio filtering. IIR (Butterworth, Chebyshev) and FIR (windowed sinc) designs with a full validation suite — coefficient checks, frequency-response sweeps, stability tests.
- **[spatial-audio-xr-toolkit](https://github.com/perc123/spatial-audio-xr-toolkit)** — Bachelor thesis: a Unity XR ↔ Max/MSP system with IRCAM spat5, real-time binaural rendering, and a novel inverse source transformation that gives a fixed-listener engine effective head tracking.
- **[vocal-coach-prototype](https://github.com/perc123/vocal-coach-prototype)** — Real-time pitch (YIN) and onset (spectral flux) detection in Web Audio. Live demo and algorithm write-up in the README.
- **[rave-multilingual-poc](https://github.com/perc123/rave-multilingual-poc)** — Real-time neural audio autoencoder (IRCAM RAVE) trained locally on multilingual voice data; exported TorchScript model deployable in Max/MSP (`nn~`), SuperCollider and PureData.
- **[RhythmHero](https://github.com/perc123/RhythmHero)** — Three.js rhythm game in the browser, with tempo-driven note spawning and collision-based hit detection.
- **[AudioObjectManager](https://github.com/perc123/AudioObjectManager)** — C++17 manager for 3D audio objects with undo / redo; originally a technical exercise for a Berlin spatial audio company.

### Links

- Portfolio — [fanisgioles.com](https://www.fanisgioles.com/)
- LinkedIn — [linkedin.com/in/fanis-gioles](https://linkedin.com/in/fanis-gioles)
- Email — fanis.gioles@gmail.com
