<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Poppins&size=22&pause=1200&color=6366F1&center=true&vCenter=true&width=640&lines=K.+Siva+Srinivas;Electronics+%26+Communication+Engineering;Embedded+Systems+%2B+DSP;2+IEEE+Papers+In+Progress" alt="Typing SVG" />

<p>
Second-year ECE engineer building embedded systems and signal-processing pipelines that hold up under real constraints — noisy channels, limited compute, field deployment.
</p>

<a href="mailto:sivasrinivasccvv@email.com"><img src="https://img.shields.io/badge/Email-6366F1?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/REPLACE_ME"><img src="https://img.shields.io/badge/LinkedIn-6366F1?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/krss-94"><img src="https://img.shields.io/badge/GitHub-6366F1?style=flat-square&logo=github&logoColor=white" /></a>

</div>

<br/>

## Research

<table width="100%">
<tr>
<td width="50%" valign="top">

**PAIRS**
<br/>
<sub>Phase Artifact Reduction Using Interpolation and Re-Sampling</sub>

Multirate phase vocoder pitch-shifting algorithm reducing transient pre-echo artifacts vs. standard phase vocoder baselines. MATLAB → C, ported to TMS320C6748.

<img src="https://img.shields.io/badge/IEEE-Under%20Review-6366F1?style=flat-square&labelColor=24292f"/>

[View repository →](https://github.com/krss-94/PAIRS-Phase-Artifact-Reduction-Using-Interpolation-And-Resampling)

</td>
<td width="50%" valign="top">

**RPW Sentinel**
<br/>
<sub>Acoustic Red Palm Weevil Detection System</sub>

5-stage TKEO-based acoustic detection pipeline on ESP32 with adaptive thresholding and LoRa multi-node communication. Optimized to ₹252/tree.

<img src="https://img.shields.io/badge/IEEE-In%20Progress-6366F1?style=flat-square&labelColor=24292f"/>

[View repository →](https://github.com/krss-94/Red-Palm-Weevil-Detection-Using-Acoustic-Sensing)

</td>
</tr>
</table>

<br/>

## Currently building

**AQ_Mesh — Secure Distributed Air Quality Monitoring Cluster**

Multi-node ESP-NOW mesh network with distinct sensor, relay, and coordinator firmware roles. Packet validation and multi-hop relay forwarding maintain data integrity across the cluster without a central access point.

`ESP32` `ESP8266` `ESP-NOW` `C++`

[View repository →](https://github.com/krss-94/AQ_Mesh)

<br/>

## Selected projects

<table width="100%">
<tr>
<td width="50%" valign="top">

**ZeroTrust-IoT-Auth**

Zero-trust HMAC-SHA256 authentication framework for ESP32 industrial IoT mesh networks. Challenge-response protocol, replay prevention, per-packet integrity, attack simulation tooling.

`Python` · MIT License

[View repository →](https://github.com/krss-94/ZeroTrust-IoT-Auth)

</td>
<td width="50%" valign="top">

**HIL-Servo-Control-Testbed**

Hardware-in-the-loop control systems testbed using ESP32 and Arduino for real-time evaluation of On/Off, P, PI, and PID controllers across multiple plant models with fault injection.

`Python` · MIT License

[View repository →](https://github.com/krss-94/HIL-Servo-Control-Testbed)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Automated Street Light Monitoring & Energy Saving System**

ESP32-based IoT system for adaptive street lighting, energy monitoring, fault detection, and Blynk cloud dashboards.

`Python` · MIT License

[View repository →](https://github.com/krss-94/-Automated-Street-Light-Monitoring-And-Energy-Saving-System)

</td>
<td width="50%" valign="top">

**Smart Waste Segregation & Recycling System**

AI-powered waste classification combining ESP32-CAM image classification, sensor fusion, and servo-based sorting with IoT dashboard monitoring.

`Python` · MIT License

[View repository →](https://github.com/krss-94/Smart-Waste-Segregation-And-Recycling-System)

</td>
</tr>
</table>

<br/>

## Toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,python,arduino,raspberrypi,git,github" />

<br/><br/>

<img src="https://img.shields.io/badge/MATLAB-6366F1?style=flat-square&logo=mathworks&logoColor=white"/>
<img src="https://img.shields.io/badge/ESP32-6366F1?style=flat-square&logo=espressif&logoColor=white"/>
<img src="https://img.shields.io/badge/ESP--NOW-6366F1?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/LoRa-6366F1?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/TMS320C6748-6366F1?style=flat-square&logoColor=white"/>

</div>

<br/>

## Activity

<table width="100%">
<tr>
<td width="55%" valign="top">

<img src="https://github-readme-stats.vercel.app/api?username=krss-94&show_icons=true&bg_color=ffffff&title_color=6366F1&icon_color=6366F1&text_color=24292f&border_color=6366F1&include_all_commits=true" width="100%"/>

</td>
<td width="45%" valign="top">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=krss-94&layout=compact&bg_color=ffffff&title_color=6366F1&text_color=24292f&border_color=6366F1" width="100%"/>

</td>
</tr>
</table>

<div align="center">
<img src="https://streak-stats.demolab.com/?user=krss-94&background=ffffff&ring=6366F1&fire=6366F1&currStreakLabel=6366F1&border=6366F1" />
</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=krss-94&theme=flat&no-bg=true&margin-w=8&column=4" />
</div>

<details>
<summary><sub>Enable animated contribution graph</sub></summary>

<br/>

<div align="center">
<img src="https://raw.githubusercontent.com/krss-94/krss-94/output/snake.svg" alt="contribution snake" />
</div>

<br/>

Add this as `.github/workflows/snake.yml` in `krss-94/krss-94`, then push and let it run once:

```yaml
name: snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch: {}
  push:
    branches: [ main ]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: krss-94
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

<br/>

## Get in touch

<div align="center">

<a href="mailto:sivasrinivasccvv@email.com"><img src="https://img.shields.io/badge/Email-6366F1?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/REPLACE_ME"><img src="https://img.shields.io/badge/LinkedIn-6366F1?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/krss-94"><img src="https://img.shields.io/badge/GitHub-6366F1?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>
