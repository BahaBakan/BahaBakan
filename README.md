<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Muhammed%20Baha%20Bakan&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Computer%20Vision%20%C2%B7%20Edge%20AI&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=600&lines=Detection+and+tracking+on+real+hardware;Models+that+keep+running+when+things+break;Measured%2C+not+guessed" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baha-bakan-3848092b8)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bahabakan7@gmail.com)
[![Location](https://img.shields.io/badge/Fethiye,%20T%C3%BCrkiye-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## About

Computer Engineering graduate (Sakarya University, 2026), working on computer
vision and edge AI.

Most of what I know came from putting models into things that have to keep
working — cameras that stream all day, phones with no network, APIs that fail
halfway through. I care about the part after the model: does it hold up, and
can you prove it.

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🎥 [edge-video-analytics](https://github.com/BahaBakan/edge-video-analytics)

Detects and tracks people, turns region crossings into events, and answers
questions about them in plain Turkish using a local LLM.

`7–10 FPS on CPU`
`text-to-SQL accuracy 72% → 88%`

Caught the model generating a `DELETE` despite being told not to — which is
why the application layer rejects anything that is not a read.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td width="50%" valign="top">

### 📞 [call-processing-pipeline](https://github.com/BahaBakan/call-processing-pipeline)

Transcribes calls, masks the personal data, works out what the caller asked
for, and books it in a CRM that is slow, rate-limited and sometimes commits a
write before dropping the connection.

`no recording is ever lost`
`41 tests`

A Postgres-backed queue with parallel workers and derived idempotency keys.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧊 [SmartFridge](https://github.com/BahaBakan/SmartFridge)

Recognises fridge contents on-device and builds a shopping list. No server
involved.

`mAP@50 of 0.935`

Trained after adapting the dataset to the camera's own image quality, then
converted to TensorFlow Lite.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![TFLite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔧 Previously

**ISERA** — multi-stream video analytics on edge hardware: GStreamer and
FFmpeg with NVDEC and VAAPI, YOLOv8 with TensorRT, events delivered through
Redis Streams with a local outbox so nothing is lost when the network drops.

**GlaucoT (İTÜ Magnet)** — supervised classification models for glaucoma
diagnosis, compared on held-out data.

</td>
</tr>
</table>

---

## Tools

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

![Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BahaBakan&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&langs_count=8" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
