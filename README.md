# Dilara Dinç

Computer Engineering student at Muğla Sıtkı Koçman University, building real-time embedded and AI systems.

I work across the whole stack of an embedded system: FreeRTOS firmware and inter-core communication, Embedded Linux applications, computer vision and acoustic signal processing, and the AI models in between.

## Featured projects

### [Tactical Detection System](https://github.com/dilara-dinc/tactical-detection-system)
Acoustic- and vision-cued target tracking turret on STM32MP157F. Linux on the Cortex-A7 runs a multithreaded OpenCV pipeline (detection, IoU tracking, threat scoring) and a touch operator console; FreeRTOS on the Cortex-M4 runs 4-microphone TDoA bearing estimation and pan-tilt control. The cores talk over a custom RPMsg protocol with handshake and heartbeat, and safety interlocks cut the laser on link or target loss.

`C++` `OpenCV` `FreeRTOS` `OpenAMP/RPMsg` `GTK3/Wayland` `STM32MP157F`

### [DroneSense](https://github.com/dilara-dinc/dronesense)
Real-time acoustic drone detection and direction finding for multichannel microphone arrays: a 72k-parameter CNN on log-mel spectrograms, harmonic-weighted SRP-PHAT direction-of-arrival estimation and an alpha-beta bearing tracker.
- Retraining on real recordings cut false alarms on held-out real sounds from 48% to 6% (AUC 0.65 → 0.82).
- On held-out real flights with GPS ground truth: 12° median bearing error, 75% detection within 25 m.

`Python` `PyTorch` `SRP-PHAT` `NumPy/SciPy`

## Experience

**Software Engineer Intern, HAUS Centrifuge Technologies** (Jun – Jul 2026)
Full software stack for a decanter centrifuge on STM32MP157F: safety-critical control on the Cortex-M4 (FreeRTOS), Modbus RTU master for drives and I/O, Linux touch HMI, Yocto images and U-Boot device tree changes.

**MSKU Racing, VCU Software Team** (2026 – Present)
CAN-based Vehicle Control Unit software for the team's Formula Student 2027 car.

**TÜBİTAK 1001 Scholarship Researcher** (2026 – Present)
SLM-AdaptRAG: conflict-aware modular RAG for small language models.

## Tech

**Embedded:** C, C++, STM32 HAL/LL, FreeRTOS, OpenAMP/RPMsg, ADC, PWM, UART, CAN, Modbus RTU
**Embedded Linux:** Yocto/OpenSTLinux, Device Tree, U-Boot, C++ multithreading, GTK3, Wayland
**AI & signal processing:** Python, PyTorch, OpenCV, multi-object tracking, mel spectrograms, TDoA, SRP-PHAT

## Contact

[LinkedIn](https://linkedin.com/in/dilara-dinc)
