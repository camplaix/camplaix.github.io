# camplaix

Independent research on real-time audio performance: low-latency DSP, CPU scheduling and how hardware behaves under load in Ableton Live 12.

## Articles

### [Beyond P-Cores: How Apple's 3-Tier Silicon (M5/M6) Impacts Low-Latency DSP Buffer Scaling and Core Allocation](https://camplaix.github.io/beyond-p-cores-apple-m6-ableton-live-12/)

Ableton Live 12 multi-core scaling on the Mac mini M6 (2 Super + 4 P-cores) vs. the Intel Core Ultra 7 270K Plus. Covers Super-to-P-core spillover, unpredictable core placement on macOS, and a buffer inversion effect where raising the buffer cuts single-track headroom.

<sub>*macOS · Windows 11 · RME Babyface Pro FS / HDSPe AIO Pro · Waves L4 and Ableton Echo* · [Files on GitHub](https://github.com/camplaix/beyond-p-cores-apple-m6-ableton-live-12)</sub>

### [RME PCIe, USB and Graphics low-latency performance](https://camplaix.github.io/rme-pcie-usb-graphics-low-latency-ableton-live-12/)

Ableton Live 12 at high CPU load on Windows 11: RME HDSPe AIO Pro (PCIe) vs. Babyface Pro FS (USB 2.0), AMD vs. NVIDIA vs. Intel UHD graphics, DPC latency, MMCSS and CPU affinity, with audio recordings of each test.

<sub>*Windows 11 25H2 · Intel i7 8700K · Ableton Echo* · [Files on GitHub](https://github.com/camplaix/rme-pcie-usb-graphics-low-latency-ableton-live-12)</sub>
