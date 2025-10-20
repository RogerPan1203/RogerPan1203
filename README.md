<!-- prettier-ignore-start -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFFF,50:00CED1,100:0D1117&height=200&section=header&text=ROGER%20PAN&fontSize=70&fontColor=FFFFFF&animation=twinkling&fontAlignY=35&desc=ROBOTICS%20%26%20COMPUTER%20VISION%20ENGINEER&descSize=20&descAlignY=55" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00FFFF&center=true&vCenter=true&width=600&lines=Building+Intelligent+Mechatronic+Systems;4%2B+Years+%7C+6+Major+Projects+%7C+Physics+%E2%86%92+Code;Open+to+2026+Robotics%2FML+Engineer+Roles" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-●%20Online-00FF41?style=for-the-badge&labelColor=000000&color=000000" alt="Status" />
  <img src="https://img.shields.io/badge/LOCATION-San%20Jose%2C%20CA-00FFFF?style=for-the-badge&labelColor=000000&color=000000" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=RogerPan1203&color=00FFFF&style=for-the-badge&label=VISITORS" alt="Visitors" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

## ⚡ CORE_SYSTEMS

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Focus Areas
```yaml
robotics:
  - Motion Control & PID
  - Embedded Firmware
  - Hardware Integration
  
computer_vision:
  - Real-time Processing
  - ML Model Deployment
  - Signal Processing (FFT/DSP)
  
mechatronics:
  - CAD/CAM Design
  - Motor Control Systems
  - Precision Manufacturing
```

</td>
<td width="50%" valign="top">

### 💻 Tech Stack
```python
stack = {
  "languages": ["Python", "C++", "Swift", "Java"],
  "robotics": ["ROS", "PID", "Motor Drivers"],
  "vision_ml": ["OpenCV", "PyTorch", "PaddlePaddle", "CoreML"],
  "mechanical": ["SolidWorks", "Fusion360", "GRBL", "Marlin"],
  "embedded": ["Arduino", "Raspberry Pi", "Firmware"],
  "ios": ["Swift", "SwiftUI", "CoreAudio", "AVFoundation"]
}
```

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

## 🔬 DEPLOYED_PROJECTS

<details open>
<summary><b>🎾 TensionVision</b> — iOS App for Tennis String Tension Analysis</summary>

<br>

**Challenge**: Professional tension gauges cost $200+; manual tuning is time-consuming  
**Solution**: FFT analysis of string vibration frequency mapped to tension via calibration curves  
**Tech Stack**: `Swift` · `SwiftUI` · `CoreAudio` · `CoreML` · `vDSP`  
**Performance**: 
- ±2.7% accuracy after calibration (N=120 tests)
- 60Hz real-time sampling
- <50ms processing latency

```swift
// Core FFT processing pipeline
func analyzeTension(audioBuffer: AVAudioPCMBuffer) -> Double {
    let fft = vDSP.FFT(length: bufferSize)
    let frequency = detectPeakFrequency(fft)
    return calibrationModel.predict(frequency)
}
```

</details>

<details>
<summary><b>🔍 OCR Engine</b> — PaddlePaddle CNN Handwriting Recognition</summary>

<br>

**Challenge**: Accurate handwritten digit recognition with minimal preprocessing  
**Solution**: Custom CNN architecture with optimized data augmentation pipeline  
**Tech Stack**: `Python` · `PaddlePaddle` · `OpenCV` · `NumPy`  
**Achievement**: 
- 🏆 **2nd Prize** — Jiangsu Province AI Competition
- 99.2% accuracy on validation set
- 2.1ms inference time per image

```python
# Model architecture
model = Sequential([
    Conv2D(32, (3,3), activation='relu'),
    MaxPooling2D((2,2)),
    Conv2D(64, (3,3), activation='relu'),
    Dense(128, activation='relu'),
    Dense(10, activation='softmax')
])
```

</details>

<details>
<summary><b>✍️ Handwriting Robot</b> — Human-like Writing via Trajectory Planning</summary>

<br>

**Challenge**: Robotic motion looks mechanical; achieving smooth curves at varying speeds  
**Solution**: Bezier curve trajectory generation + adaptive PID control with feedforward  
**Tech Stack**: `C++` · `ROS` · `Stepper Motors` · `Trajectory Planning`  
**Performance**:
- 0.3mm RMS path tracking error
- Variable speed control (20-80 mm/s)
- Human evaluators rated 7.8/10 for realism

```cpp
// PID control loop (1kHz)
void controlLoop() {
    error = target_pos - current_pos;
    output = Kp*error + Ki*integral + Kd*derivative;
    stepper.setSpeed(output);
}
```

</details>

<details>
<summary><b>🖨️ Custom 3D Printer</b> — High-Precision Modular Design</summary>

<br>

**Challenge**: Off-the-shelf printers lack precision for small mechanical parts  
**Solution**: Custom kinematics with upgraded linear rails, direct drive extruder, PID-tuned hotend  
**Tech Stack**: `Marlin Firmware` · `SolidWorks` · `CAD` · `PID Tuning`  
**Specs**:
- 0.05mm layer height capability
- 98% first-layer adhesion success rate
- 1000+ hours runtime with <2% maintenance downtime

</details>

<details>
<summary><b>🏎️ Direct-Drive Racing Sim</b> — Force Feedback System</summary>

<br>

**Challenge**: Simulating realistic road feedback forces with minimal latency  
**Solution**: Direct-drive motor with torque control + IMU sensor fusion for road feel  
**Tech Stack**: `Embedded C` · `Motor Control` · `PID` · `IMU Fusion`  
**Performance**:
- <2ms control loop latency
- 10Nm peak torque output
- 1kHz update rate for smooth feedback

</details>

<details>
<summary><b>⚙️ Compact CNC Mill</b> — GRBL Firmware from Scratch</summary>

<br>

**Challenge**: Commercial CNCs too large/expensive for hobbyist precision work  
**Solution**: Custom compact design with GRBL firmware modifications for enhanced accuracy  
**Tech Stack**: `GRBL` · `CAM` · `Stepper Motors` · `Microcontroller`  
**Specs**:
- 0.02mm repeatability
- Aluminum cutting capable (200mm/min feed rate)
- Custom toolpath generation via Python CAM scripts

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

## 📊 GITHUB_ANALYTICS

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RogerPan1203&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FFFF&icon_color=00FF41&text_color=FFFFFF&ring_color=00FFFF" height="180" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RogerPan1203&theme=chartreuse-dark&hide_border=true&background=0D1117&ring=00FFFF&fire=00FF41&currStreakLabel=00FFFF&sideLabels=FFFFFF" height="180" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RogerPan1203&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FFFF&text_color=FFFFFF" height="180" alt="Top Languages" />
  <img src="https://github-profile-trophy.vercel.app/?username=RogerPan1203&theme=onestar&no-frame=true&column=3&row=2&margin-w=10&margin-h=10" height="180" alt="Trophies" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=RogerPan1203&theme=react-dark&bg_color=0D1117&color=00FFFF&line=00FF41&point=FFFFFF&hide_border=true&custom_title=Contribution%20Activity" alt="Activity Graph" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

## 🛰️ SKILL_MATRIX

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,swift,java,opencv,pytorch,ros,arduino,raspberrypi,git&theme=dark" alt="Skills Row 1" />
  <br>
  <img src="https://skillicons.dev/icons?i=linux,vscode,xcode,docker,github,bash,matlab,figma,blender,unity&theme=dark" alt="Skills Row 2" />
</p>

<table align="center">
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Python-8%2F10-00FF41?style=for-the-badge&logo=python&logoColor=white&labelColor=000000" /><br>
<sub>4+ years · 10k+ lines</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/C++-6%2F10-00FFFF?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=000000" /><br>
<sub>Embedded · ROS</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Swift-6%2F10-FF6B35?style=for-the-badge&logo=swift&logoColor=white&labelColor=000000" /><br>
<sub>iOS · CoreML</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/CAD-7%2F10-9B59B6?style=for-the-badge&logo=autodesk&logoColor=white&labelColor=000000" /><br>
<sub>SolidWorks · Fusion360</sub>
</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

## 📡 CONTACT_PROTOCOL

<p align="center">
  <a href="mailto:panyf200713@outlook.com">
    <img src="https://img.shields.io/badge/EMAIL-panyf200713@outlook.com-00FFFF?style=for-the-badge&logo=microsoft-outlook&logoColor=white&labelColor=000000" alt="Email" />
  </a>
  <a href="tel:+15303604994">
    <img src="https://img.shields.io/badge/PHONE-+1%20530%20360%204994-00FF41?style=for-the-badge&logo=phone&logoColor=white&labelColor=000000" alt="Phone" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/YifanPan">
    <img src="https://img.shields.io/badge/LinkedIn-YifanPan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000" alt="LinkedIn" />
  </a>
  <a href="https://github.com/RogerPan1203">
    <img src="https://img.shields.io/badge/GitHub-RogerPan1203-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=000000" alt="GitHub" />
  </a>
  <a href="YOUR_RESUME_PDF_LINK">
    <img src="https://img.shields.io/badge/RESUME-Download%20PDF-FF6B35?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=000000" alt="Resume" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LANGUAGES-中文%20%7C%20English%20%7C%20日本語-9B59B6?style=for-the-badge&labelColor=000000" alt="Languages" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00FFFF,100:0D1117&height=2&section=header" />

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:00CED1,100:00FFFF&height=120&section=footer&reversal=true" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=00FFFF&center=true&vCenter=true&width=600&lines=%E2%9A%99%EF%B8%8F+Building+machines+that+see+and+think;%F0%9F%93%A7+Open+to+collaboration+on+robotics+%26+ML+projects;%E2%9C%A8+Let's+turn+physics+into+code+together" alt="Footer Typing" />
</p>

<!-- prettier-ignore-end -->
