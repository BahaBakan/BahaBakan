## Muhammed Baha Bakan

**Computer Vision & Edge AI** — I build detection and tracking systems that
run on real hardware, and the services around them.

Computer Engineering graduate (Sakarya University, 2026). Most of what I know
came from putting models into things that have to keep working: cameras that
stream all day, phones without a network, APIs that fail halfway through.

---

### Selected work

**[edge-video-analytics](https://github.com/BahaBakan/edge-video-analytics)** · Python, YOLOv8, ByteTrack, FastAPI
Detects and tracks people, turns region crossings into events, and answers
questions about them in plain language using a local LLM.
Runs at **7–10 FPS on CPU**. Took text-to-SQL accuracy from **72% to 88%** on a
20-question evaluation set — and caught the model generating a `DELETE`
despite being told not to, which is why the application layer rejects
anything that is not a read.

**[call-processing-pipeline](https://github.com/BahaBakan/call-processing-pipeline)** · Python, PostgreSQL, Docker
Transcribes call recordings, masks the personal data, works out what the
caller asked for, and books it in a CRM — one that is slow, rate-limited and
sometimes commits a write before dropping the connection.
Built so **no recording is ever lost**: a Postgres-backed queue with parallel
workers, derived idempotency keys, and 41 tests.

**[SmartFridge](https://github.com/BahaBakan/SmartFridge)** · ESP32, YOLOv11, TensorFlow Lite, Kotlin
Recognises fridge contents on-device and builds a shopping list.
Trained to **mAP@50 of 0.935** after adapting the dataset to the camera's own
image quality, then converted to TFLite so it works with no server.

---

### Tools

Python · C++ · Kotlin · SQL
YOLO · PyTorch · OpenCV · TensorRT · ONNX Runtime · TensorFlow Lite
FastAPI · PostgreSQL · Redis Streams · Docker
NVIDIA Jetson · ESP32 · GStreamer · FFmpeg

---

📍 Fethiye, Türkiye · [LinkedIn](https://linkedin.com/in/baha-bakan-3848092b8) · bahabakan7@gmail.com
