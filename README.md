```
███████╗     ██╗███████╗    █████╗ ██╗   ██╗██████╗ ██╗ ██████╗
██╔════╝     ██║██╔════╝   ██╔══██╗██║   ██║██╔══██╗██║██╔═══██╗
███████╗     ██║█████╗     ███████║██║   ██║██║  ██║██║██║   ██║
╚════██║██   ██║██╔══╝     ██╔══██║██║   ██║██║  ██║██║██║   ██║
███████║╚█████╔╝██║███████╗██║  ██║╚██████╔╝██████╔╝██║╚██████╔╝
╚══════╝ ╚════╝ ╚═╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝ ╚═════╝
```

# sjf_modchain

*sjf_modchain* is a flexible semi-modular multi-effects engine. Featuring a comprehensive suite of effect modules driven by an array of freely assignable modulators.

### Features
- Flexible Modulation Matrix: 6 multi-waveform LFOs and 2 dynamic Envelope Followers designed to be routed to any effect parameter across the plugin.
- 17+ FX Modules: A toolbox of spatial, dynamics, filter, and saturation processors—including Moog Ladder and SVF filters, bit-crushing, spectral manipulation, and stereo enhancement.
- Signal Architecture: Dedicated input/output gain staging, optional global oversampling for alias-free saturation, and a safety limiter at the end of the chain.

---
```
[ Audio Input ]
                                  |
               +------------------+------------------+
               |                                     |
       [ Control Path ]                       [ Audio Path ]
               |                                     |
       +---------------+                     +---------------+
       |  Modulators   |                     |  Input Gain   |
       |               |                     +---------------+
       |  • 6 LFOs     |                             |
       |  • 2 Envelope |                     +---------------+
       |    Followers  |                     |  FX Chain     |
       +-------+-------+                     | (Oversampled) |
               |                             |               |
               |                             |  • Saturator  |
               |                             |  • Delay      |
               |                             |  • Reverb     |
               |                             |  • Compressor |
               |                             |  • 2 State    |
               |                             |      Variable |
               |                             |      Filters  |
               |                             |  • Moog Ladder|
               |                             |      Filter   |
               |                             |  • Chorus     |
               | (User-Assignable            |  • Flanger    |
               |  Modulation Routing)        |  • Phaser     |
               +============================>|  • Exciter    |
                                             |  • Utility    |
                                             |  • Sample     |
                                             |      Reducer/ |
                                             |      Bit      |
                                             |      Crusher  |
                                             |  • Stereo     |
                                             |      Spreader |
                                             |  • Tremolo    |
                                             |  • Spectral   |
                                             |      Processor|
                                             |  • Noise Gate |
                                             +---------------+
                                                     |
                                             +---------------+
                                             |    Limiter    |
                                             +---------------+
                                                     |
                                             +---------------+
                                             |  Output Gain  |
                                             +---------------+
                                                     |
                                  +------------------+
                                  |
                          [ Audio Output ]

```

---

More effects and modulators still to come!!             

