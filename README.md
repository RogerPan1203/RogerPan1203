<!-- prettier-ignore-start -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:0E4D5C,100:00CED1&height=190&section=header&text=Roger%20Pan&fontSize=58&fontColor=FFFFFF&fontAlignY=36&desc=Robotics%20%C2%B7%20Embedded%20Systems%20%C2%B7%20Computer%20Vision&descSize=18&descAlignY=58" alt="Roger Pan — Robotics · Embedded Systems · Computer Vision" />
</p>

<p align="center">
  <b>I build machines end to end — from CAD and firmware to control loops, vision models and the app you hold.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Robotics%20%2F%20ML%20%2F%20Embedded%20roles-00CED1?style=flat-square&labelColor=0D1117" alt="Open to Robotics / ML / Embedded roles" />
  <img src="https://img.shields.io/badge/Languages-English%20%C2%B7%20%E4%B8%AD%E6%96%87%20%C2%B7%20%E6%97%A5%E6%9C%AC%E8%AA%9E-0E4D5C?style=flat-square&labelColor=0D1117" alt="Languages" />
</p>

---

### 👋 About

- **Full-stack hardware engineer.** I design the mechanism, write the firmware, tune the controller and ship the software on top.
- **5 self-built machines** — a handwriting robot, CNC mill, 3D printer, force-feedback racing sim and a tennis ball robot — plus iOS/macOS apps and ML models.
- **Results I can measure:** sub-millimetre motion accuracy, millisecond control loops, and a provincial AI competition award.
- Currently building **robots and vision systems for tennis** 🎾.

### 🏆 Highlights

| | |
|:--|:--|
| 🥈 **2nd Prize, Jiangsu Province AI Competition** | Handwriting recognition CNN — 99.2% validation accuracy, 2.1 ms / image |
| 🎯 **0.3 mm RMS tracking error** | Handwriting robot with Bézier trajectories + feed-forward PID |
| ⚡ **< 2 ms control loop @ 1 kHz** | Direct-drive force-feedback racing simulator, 10 Nm peak torque |
| 📱 **±2.7% accuracy from a phone mic** | iOS app measuring racket string tension via real-time FFT |

---

### 🔧 Featured Work

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 [CourtMotion](https://github.com/RogerPan1203/CourtMotion)
Tennis ball-machine robot. A Raspberry Pi drives two motors through a PCA9685, operated from a local web dashboard with confirm-to-start and emergency stop.

`Python` `Raspberry Pi` `PCA9685` `systemd`

</td>
<td width="50%" valign="top">

#### 🎾 [Tennis Match Recognition](https://github.com/RogerPan1203/Tennis-Recognization)
Analyses match video: court lines via Hough transform, players and balls via YOLOv8 plus colour filtering.

`Python` `YOLOv8` `OpenCV`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎻 TensionVision
iOS app that turns a string's vibration into tension — FFT on 60 Hz live audio, mapped through calibration curves. ±2.7% after calibration (N = 120), < 50 ms latency.

`Swift` `SwiftUI` `CoreAudio` `vDSP` `CoreML`

</td>
<td width="50%" valign="top">

#### ✍️ Handwriting Robot
Makes robot writing look human: Bézier trajectory generation with adaptive PID and feed-forward. 0.3 mm RMS error at 20–80 mm/s; rated 7.8 / 10 for realism.

`C++` `ROS` `Stepper control` `Trajectory planning`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⚙️ Compact CNC Mill
Desktop mill with modified GRBL firmware and Python CAM scripts. 0.02 mm repeatability; cuts aluminium at 200 mm/min.

`GRBL` `CAM` `Python` `Microcontrollers`

</td>
<td width="50%" valign="top">

#### 🏎️ Direct-Drive Racing Sim
Force-feedback wheel with torque control and IMU fusion for road feel. 1 kHz update, < 2 ms loop latency.

`Embedded C` `Motor control` `IMU fusion`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⌨️ [TypeTracer](https://github.com/RogerPan1203/TypeTracer) · ✋ [finger-count-macos](https://github.com/RogerPan1203/finger-count-macos)
Two shipped macOS apps: real-time keystroke analytics, and fully offline finger counting with Apple Vision.

`Swift` `SwiftUI` `Vision`

</td>
<td width="50%" valign="top">

#### 🖨️ Custom 3D Printer
Rebuilt for small precision parts: linear rails, direct-drive extruder, tuned Marlin. 0.05 mm layers, 1000+ hours of runtime.

`Marlin` `SolidWorks` `PID tuning`

</td>
</tr>
</table>

<sub>Most hardware projects live in private repositories — happy to walk through code, CAD and test data in an interview.</sub>

---

### 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,swift,java,pytorch,opencv,ros&theme=dark" alt="Languages and ML" /><br/>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,matlab,git,docker,xcode,blender&theme=dark" alt="Hardware and tools" />
</p>

| Area | Tools |
|:--|:--|
| **Control & Embedded** | PID / feed-forward, stepper & BLDC drivers, Arduino, Raspberry Pi, GRBL, Marlin |
| **Vision & ML** | PyTorch, PaddlePaddle, YOLOv8, OpenCV, CoreML, FFT / DSP |
| **Mechanical** | SolidWorks, Fusion 360, CAM, precision fabrication |
| **Apps** | Swift, SwiftUI, CoreAudio, AVFoundation, Apple Vision |

---

<p align="center">
  <a href="https://linkedin.com/in/YifanPan"><img src="https://img.shields.io/badge/Let's%20talk%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00CED1,45:0E4D5C,100:0D1117&height=90&section=footer" alt="" />
</p>

<!-- prettier-ignore-end -->
