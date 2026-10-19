# Hey, I'm Raghav 👋

I'm an AI/ML engineer based in Delta, BC, Canada. I build ML systems that run on real, messy, streaming data, mostly on GCP, plus the computer vision and LLM tooling around them.

## What I do day to day

At **Jaipur Robotics**, I work on monitoring waste-to-energy trucks:

- 🚛 **Streaming pipeline:** an Apache Beam pipeline that merges detection streams and dedups them into truck-session state (3K events/day, 4,800+ truck fleet, ~13 min end to end).
- 👁️ **Computer vision:** waste-area segmentation and alert-image processing, plus LiDAR volume measurement (8.6K scans/month).
- 🤖 **LLM automation:** Gemini-based alert tracking and LLM alert classification across 9 plant sites (3.2K tasks/month, about a minute each).
- 🎥 **Video platform:** an async timelapse-video service (FastAPI, Cloud Tasks, GCS) that attaches video to 99% of sessions.

## Research

- **Efficient Adaptation of Lightweight LLMs** (ICAAI 2025, Springer). First author. We compared T-Free and STELLA on SST-2, MultiNLI and SNLI using a single RTX 3060. T-Free cut embedding parameters by 74%, and a STELLA-tuned variant hit 0.784 on SST-2.

## Side projects

- [**American Sign Language Interpreter**](https://github.com/Raghav-Kochhar/AmericanSignLanguageInterpreter): real-time sign recognition (EfficientNetV2-S + LSTM)
- [**Traffic & Pedestrian Analyzer**](https://github.com/Raghav-Kochhar/TrafficPedestrianAnalyzer): YOLOv8x vehicle counting and pedestrian detection
- [**Speech Emotion Classifier**](https://github.com/Raghav-Kochhar/SpeechEmotionClassifier): LSTM on MFCC features across 4 corpora
- [**taurus**](https://github.com/Raghav-Kochhar/taurus): a torrent client written in Rust

## What I use

Python · PyTorch · Apache Beam · FastAPI · GCP (Cloud Run, Pub/Sub, AlloyDB) · OpenCV · LangChain · Docker

## Say hi

📫 raghavkochhar007@gmail.com · [LinkedIn](https://www.linkedin.com/in/raghavkochhar007) · [Resume](https://raghav-kochhar.github.io/Raghav-Kochhar/Raghav_Kochhar_Resume.pdf)
