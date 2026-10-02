# camplaix

Independent research on real-time audio performance: low-latency DSP, CPU scheduling and how hardware behaves under load in Ableton Live 12.

## Articles

### [Beyond P-Cores: How Apple's 3-Tier Silicon (M5/M6) Impacts Low-Latency DSP Buffer Scaling and Core Allocation](https://camplaix.github.io/beyond-p-cores-apple-m6-ableton-live-12/)

Ableton Live 12 multi-core scaling on the Mac mini M6 (2 Super + 4 P-cores) vs. the Intel Core Ultra 7 270K Plus. Covers Super-to-P-core spillover, unpredictable core placement on macOS, and a buffer inversion effect where raising the buffer cuts single-track headroom.

<sub>*macOS · Windows 11 · RME Babyface Pro FS / HDSPe AIO Pro · Waves L4 and Ableton Echo* · [Files on GitHub](https://github.com/camplaix/beyond-p-cores-apple-m6-ableton-live-12)</sub>

### [RME PCIe, USB and Graphics low-latency performance](https://camplaix.github.io/rme-pcie-usb-graphics-low-latency-ableton-live-12/)

Ableton Live 12 at high CPU load on Windows 11: RME HDSPe AIO Pro (PCIe) vs. Babyface Pro FS (USB 2.0), AMD vs. NVIDIA vs. Intel UHD graphics, DPC latency, MMCSS and CPU affinity, with audio recordings of each test.

<sub>*Windows 11 25H2 · Intel i7 8700K · Ableton Echo* · [Files on GitHub](https://github.com/camplaix/rme-pcie-usb-graphics-low-latency-ableton-live-12)</sub>

### [State of Things: DAW Low Latency, C-States and Discrete vs. Integrated Graphics](https://camplaix.github.io/c-states-integrated-graphics-ableton-live/)

Ableton Live 10 and Studio One 4 at 64 samples on an i7 8700K: how C-States, Ableton's `-_ForceGdiBackend` flag and Intel UHD 630 vs. AMD vs. NVIDIA graphics affect the real-time meter and audible glitches across light and heavy projects.

<sub>*Windows 10 1909 · Intel i7 8700K · RME Babyface Pro FS · Ableton Live 10 and Studio One 4* · [Files on GitHub](https://github.com/camplaix/c-states-integrated-graphics-ableton-live)</sub>

## Studio gear

### [Madlib's Studio Gear, circa 2005](https://camplaix.github.io/madlib-gear-2005/)

Identifying the equipment in Madlib's mid-2000s home studio from the *Behind the Beat* photo book, NRK's 2005 Stones Throw special and session photos: two Boss SP-303s, the Akai MPC 4000, and a wall of digital multitrack recorders from Akai, Korg, Roland, Fostex and Tascam.

<sub>*Photo research · Boss SP-303 · Akai MPC 4000 · Tascam Portastudio 488* · [Files on GitHub](https://github.com/camplaix/madlib-gear-2005)</sub>
