<div align="center">
	<br>
	<br>
	<div>
		<img src="media/logo.png" alt="Awesome Whisper">
		<br>
	</div>
	<br>
	<p>
		<a href="https://openai.com/research/whisper">Whisper</a> is an open-source AI-powered speech recognition system developed by <a href="https://openai.com">OpenAI</a>
	</p>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<br>
	<br>
	<br>
	<br>
	<br>
</div>

## Contents

* [Official](#official)
* [Model variants](#model-variants)
* [Apps](#apps)
* [Web apps](#web-apps)
* [CLI tools](#cli-tools)
* [Playgrounds](#playgrounds)
* [Packages](#packages)
* [Articles](#articles)
* [Videos](#videos)
* [Community](#community)
* [Third-party APIs](#third-party-apis)
* [Related lists](#related-lists)

## Official

* [Introduction](https://openai.com/research/whisper)
* [Source code](https://github.com/openai/whisper) ⭐ 94,444 | 🐛 114 | 🌐 Python | 📅 2025-12-15
* [White paper](https://cdn.openai.com/papers/whisper.pdf)

## Model variants

* [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) ⭐ 46,632 | 🐛 1,123 | 🌐 C++ | 📅 2026-02-09 - Port of Whisper in C++.
  * [Bindings for many languages](https://github.com/ggerganov/whisper.cpp#bindings) ⭐ 46,632 | 🐛 1,123 | 🌐 C++ | 📅 2026-02-09
* [faster-whisper](https://github.com/guillaumekln/faster-whisper) ⭐ 20,891 | 🐛 303 | 🌐 Python | 📅 2025-11-19 - Faster reimplementation of Whisper using CTranslate2.
* [WhisperX](https://github.com/m-bain/whisperX) ⭐ 20,085 | 🐛 282 | 🌐 Python | 📅 2026-02-10 - Adds fast automatic speaker recognition with word-level timestamps and speaker diarization.
* [Whisper JAX](https://github.com/sanchit-gandhi/whisper-jax) ⭐ 4,681 | 🐛 139 | 🌐 Jupyter Notebook | 📅 2024-04-03 - JAX implementation of Whisper for up to 70x speed-up on TPU.
* [whisper-timestamped](https://github.com/linto-ai/whisper-timestamped) ⭐ 2,759 | 🐛 49 | 🌐 Python | 📅 2025-09-09 - Adds word-level timestamps and confidence scores.
* [Whisper-AT](https://github.com/YuanGongND/whisper-at) ⭐ 413 | 🐛 28 | 🌐 Python | 📅 2024-02-21 - Whisper that can recognize non-speech audio events in addition to speech.
* [whisper-openvino](https://github.com/zhuzilin/whisper-openvino) ⭐ 182 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-11-06 - Whisper running on OpenVINO.
* [whisper.tflite](https://github.com/usefulsensors/openai-whisper) ⚠️ Archived - Whisper running on TensorFlow Lite.
* [Whisper variants](https://huggingface.co/models?other=whisper) - Various Whisper variants on Hugging Faces.

## Apps

* [Buzz](https://github.com/chidiwilliams/Buzz) ⭐ 17,781 | 🐛 16 | 🌐 Python | 📅 2026-02-08 - Audio transcription and translation macOS app.
* [VoiceInk](https://github.com/Beingpax/VoiceInk) ⭐ 3,669 | 🐛 179 | 🌐 Swift | 📅 2026-02-10 - Dictation and transcription macOS app. (FOSS)
* [Speech Note](https://github.com/mkiol/dsnote) ⭐ 1,349 | 🐛 123 | 🌐 C++ | 📅 2026-01-31 - Audio transcription Linux app.
* [OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper) ⭐ 619 | 🐛 37 | 🌐 Swift | 📅 2026-02-10 - Dictation app for macOS (FOSS).
* [Ito AI](https://github.com/heyito/ito) ⚠️ Archived - AI voice dictation for Mac. (FOSS)
* [Whisper](https://github.com/woheller69/whisperIME) ⭐ 520 | 🐛 18 | 🌐 Java | 📅 2026-02-07 - Android app for transcription and translation. (FOSS)
* [Aiko](https://sindresorhus.com/aiko) - Audio transcription iOS and macOS app.
* [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) - Audio transcription macOS app. (Freemium)
* [Whisper Memos](https://apps.apple.com/app/id6443658039) - Audio transcription iOS app. (Freemium)
* [FourYou](https://apps.apple.com/app/id1671616134) - Audio journal iOS app.
* [Jojo Transcribe](https://apps.apple.com/app/id1659864300) - Audio transcription macOS app.
* [WhisperScript](https://store.getwavery.com/l/whisperscript) - Audio transcription macOS app. (Freemium · Electron)
* [Audio Podium](https://apps.apple.com/app/id6449008295) - Audio/video management macOS app.
* [superwhisper](https://superwhisper.com) - Global audio transcription macOS menu bar app.
* [FridayGPT](https://www.fridaygpt.app) - Dictation macOS app powered by OpenAI API.
* [EasyWhisper](https://easywhisper.io) - Windows and macOS app for audio transcription and speaker diarization. (Freemium)
* [Audio Note](https://audionote.app) - Real-time audio transcription on macOS and Windows. (Freemium · Electron)

## Web apps

<!-- ### Hosted and self-hosted -->

### Hosted

* [bigWav](https://bigwav.app) - Audio transcription and annotation tool.
* [Free Podcast Transcription](https://freepodcasttranscription.com) - Runs locally in your browser.
* [Gladia](https://www.gladia.io) - Transcription with real-time processing.

### Self-hosted

* [WaaS](https://github.com/schibsted/WAAS) ⭐ 2,029 | 🐛 28 | 🌐 JavaScript | 📅 2026-01-08 - GUI and API for Whisper.
* [Subs AI](https://github.com/abdeladim-s/subsai) ⭐ 1,638 | 🐛 72 | 🌐 Python | 📅 2025-09-09 - Subtitle generation.
* [writeout.ai](https://github.com/beyondcode/writeout.ai) ⭐ 1,525 | 🐛 7 | 🌐 PHP | 📅 2023-03-14 - Laravel app to transcribe and translate audio files.
* [Meeper](https://github.com/pas1ko/meeper) ⭐ 81 | 🐛 1 | 🌐 TypeScript | 📅 2025-04-27 - Transcriptions, summary and more for meetings and any browser tab. (Chrome app)

## CLI tools

* [whisper-diarization](https://github.com/MahmoudAshraf97/whisper-diarization) ⭐ 5,357 | 🐛 39 | 🌐 Jupyter Notebook | 📅 2025-11-26 - Automatic speech recognition with speaker diarization.
* [whisper-standalone-win](https://github.com/Purfview/whisper-standalone-win) ⭐ 2,849 | 🐛 3 | 📅 2025-11-07 - Standalone Windows executable for Whisper and Faster Whisper.
* [yt-whisper](https://github.com/m1guelpf/yt-whisper) ⭐ 1,423 | 🐛 22 | 🌐 Python | 📅 2024-01-16 - YouTube subtitle generation.
* [whisper-ctranslate2](https://github.com/Softcatala/whisper-ctranslate2) ⭐ 1,212 | 🐛 10 | 🌐 Python | 📅 2026-02-08 - Whisper command-line tool based on CTranslate2, compatible with the original.
* [insanely-fast-whisper-cli](https://github.com/ochen1/insanely-fast-whisper-cli) ⭐ 385 | 🐛 6 | 🌐 Python | 📅 2024-06-08 - Achieve transcription speeds near 30x real-time with several optimizations.
* [hns](https://github.com/primaprashant/hns) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2025-12-04 - On-device speech-to-text CLI using faster-whisper with automatic clipboard copy.
* [phonix](https://github.com/platisd/phonix) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2025-03-28 - Generate captions for videos.

## Playgrounds

* [Monster API](https://whisperui.monsterapi.ai) - Whisper demo running on Monster API. ([Source](https://github.com/saharmor/whisper-playground) ⭐ 833 | 🐛 16 | 🌐 Python | 📅 2025-09-12)
* [YouTube Video Transcription](https://github.com/ArthurFDLR/whisper-youtube) ⭐ 414 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-04-23 - Running on Colab.
* [Hugging Faces](https://huggingface.co/spaces/openai/whisper) - Whisper demo running on Hugging Faces. ([Source](https://huggingface.co/spaces/openai/whisper/tree/main))
* [Web Whisper](https://whisper.r3d.red) - Whisper demo by Pluja. ([Source](https://codeberg.org/pluja/web-whisper))

## Packages

### JavaScript

* [use-whisper](https://github.com/chengsokdara/use-whisper) ⭐ 786 | 🐛 35 | 🌐 TypeScript | 📅 2024-04-30 - React hook.

## Articles

* [Whispers of A.I.'s Modular Future](https://www.newyorker.com/tech/annals-of-technology/whispers-of-ais-modular-future) - The future of machine learning lies in adaptable and accessible open-source speech-transcription programs.
* [How to Run Whisper Speech Recognition Model](https://www.assemblyai.com/blog/how-to-run-openais-whisper-speech-recognition-model/) - Explains how to install and run the model, as well as providing a performance analysis comparing Whisper to other models.
* [Create your own speech to text app using Flask](https://blog.paperspace.com/whisper-openai-flask-application-deployment/) - The tutorial demonstrates Whisper's speech-to-text model, with a demo on running it in a Gradient Notebook and a guide for setting up a Flask app with Gradient Deployments.
* [Convert Podcasts to Text](https://betterprogramming.pub/openais-whisper-tutorial-42140dd696ee) - Tutorial on the Whisper API with Python for speech-to-text transcription, showcasing GPU's faster transcription and advanced technology.

## Videos

* [Open AI's Whisper is Amazing!](https://www.youtube.com/watch?v=OCBZtgQGt1I) - Introduction to Whisper.
* [How to do Free Speech-to-Text Transcription Better Than Google Premium API](https://www.youtube.com/watch?v=msj3wuYf3d8) - Tutorial.
* [Multilingual AI Speech Recognition Live App](https://www.youtube.com/watch?v=ywIyc8l1K1Q) - Tutorial.

## Community

* [Discussions](https://github.com/openai/whisper/discussions) ⭐ 94,444 | 🐛 114 | 🌐 Python | 📅 2025-12-15
* [Discord](https://discord.com/invite/openai)

## Third-party APIs

*APIs that use Whisper.*

* [Whisper+](https://www.oneai.com/speech-to-text) - Extension of the Whisper model which adds powerful features such as speaker identification custom vocabulary, summarization, and chapter generation.
* [Replicate](https://replicate.com/openai/whisper) - Use Whisper running on Replicate.

## Related lists

* [awesome-chatgpt](https://github.com/sindresorhus/awesome-chatgpt) ⭐ 6,083 | 🐛 7 | 📅 2026-01-04 - ChatGPT resources.
