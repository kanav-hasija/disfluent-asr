# disfluent-asr
Automated Speech Recognition (ASR) with speech disfluency and intensity tagging

## Overview
Most automated speech recognition (ASR) systems like OpenAI Whisper, Google Wavenet, Meta wav2vec are designed to *smooth over* speech disfluencies. This makes utilities like Siri, Alexa, or Hey Google more accessible for people who stutter, but it also removes critical information about **where, how, and with what intensity** disfluencies occur.

If we want to help people with speech disfluencies *reduce* their stutter, we first need to **accurately detect and tag** these disfluencies.

This project aims to fill that gap by building:
1. **An open-source ASR model** capable of detailed disfluency tagging.
2. **The largest open repository** of disfluency-tagged audio and transcript data for people who stutter.

---

## Why This Matters
- **Unmet Need:** Current ASR pipelines are optimized for fluency, not for understanding speech patterns in individuals with disfluencies.
- **Research Enablement:** Without large, openly available datasets, research and innovation in stuttering therapy tools remain limited.
- **Therapeutic Potential:** Tagged disfluency data can enable better speech therapy software, progress tracking tools, and real-time feedback applications.

---

## Project Goals
- **Collect & Share Data:** Build the largest open-source dataset of stuttered speech with detailed disfluency tagging.
- **Train & Release Models:** Develop ASR models capable of tagging:
  - Repetitions
  - Prolongations
  - Blocks
  - Fillers
  - Pauses
- **Enable Community Collaboration:** Provide a platform for researchers, speech therapists, and technologists to collaborate on tools for disfluency analysis.

---

## Features
- End-to-end ASR pipeline with disfluency tagging.
- Open training data in standardized formats (audio + aligned transcripts).
- Extensible tagging schema for multiple disfluency types.
- Benchmarks on existing speech datasets and newly collected data.

---

## Dataset
We are working towards releasing:
- Hundreds of hours of **speech audio from people who stutter**.
- Detailed **time-aligned disfluency tags**.
- Clear licensing for **open research and commercial use**.

If you would like to **contribute** or **help with model development, tagging, or app development**, please reach out to kanav.hasija@gmail.com

---
