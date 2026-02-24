## 🚀 Engineering & Projects

### 🕹️ The Sonic Engine Lineage (True 360 Physics)
I am a **Classic Sonic** developer. I focus on momentum, physics-based platforming, and the original 16-bit feel. If it doesn't have a rolling physics loop, I'm probably not building it.

All my Sonic engines are built on **True 360-Degree Physics**. Instead of basic platforming logic, I developed custom collision systems to calculate slope angles in real-time.

* [**🦔 Gvbvdxx Sonic Engine (Pure JS)**](https://github.com/gvbvdxx/gvbsonic)
    * **Logic:** Ported my 360° concepts out of block-coding and into pure JavaScript, allowing for much faster execution of slope calculations, classic-accurate momentum, wall-running, and loop-de-loop support.
* [**Scratch Sonic Engine (SSE)**](https://drive.google.com/file/d/1rIjphhkFid3A3dyaucXDVd3cql_XRoAu/view?usp=drive_link)
    * **The "Pixel Probe" Logic:** To calculate 360° slopes in Scratch, the collision sprite is literally just a single pixel. When on a slope, it saves its position, moves 12 steps out, and rotates until it clears the ground. It repeats this on both sides to perfectly calculate the ground angle!
* [**Delta Sonic 360 Framework**](https://drive.google.com/drive/folders/1l0u70F4CqF_ndKYMYE6lb1rSgkNHILKb)
    * **Technical Achievement:** Includes a **Bounce Back** system that restores horizontal velocity if you run off a curved wall onto flat ground, using a hitbox-based layout instead of the single-pixel method.

### 🌐 Networking & Web Ports
* [**Sonic Robo Blast 2 Web**](https://gvbvdxxalt2.github.io/SRB2web/)
    * **Tech:** SRB2 2.2.15 ported via **Emscripten**.
    * **Feature:** Integrated **WebRTC** for P2P LAN support. This was my direct response to ISPs blocking ports.
* [**🎤 FNF vs Gvbvdxx**](https://github.com/gvbvdxx/FNFVsGvbvdxxEngine)
    * **The "Duct-Tape" Fix:** Implemented a forced preloading sequence on the Haxe "Blue Screen" to ensure `inst` and `voices` load correctly on lower-end hardware.

---
[**⬅️ Back to profile**](./README.md)
