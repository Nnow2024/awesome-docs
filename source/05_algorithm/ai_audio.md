# Audio 类算法

本页列出已在爱芯 NPU 平台完成适配的语音/音频模型。所有模型可通过 [AXERA 模型仓库](https://huggingface.co/AXERA-TECH) 下载预编译 axmodel。

运行示例与上板命令见 [示例展示](samples_board.md)。

## ASR（语音识别）

- [SenseVoice](https://huggingface.co/AXERA-TECH/SenseVoice)：多语种语音识别（中/英/日/粤/韩），AX650 / AX630C
- [Whisper](https://huggingface.co/AXERA-TECH/Whisper)：OpenAI Whisper 多语种语音识别，AX650 / AX630C
- [FireRedASR-AED](https://huggingface.co/AXERA-TECH/FireRedASR-AED)：端到端语音识别，AX650
- [WeNet](https://huggingface.co/AXERA-TECH/WeNet)：WeNet 流式/非流式语音识别，AX650
- [Qwen3-ASR-0.6B](https://huggingface.co/AXERA-TECH/Qwen3-ASR-0.6B-AX650-C64-P448-CTX2047)：Qwen3 语音识别 0.6B，AX650
- [Zipformer.axera](https://huggingface.co/AXERA-TECH/Zipformer.axera)：Zipformer 流式识别，AX650 / AX630C

## 说话人识别 / 会议转录

- [3D-Speaker](https://huggingface.co/AXERA-TECH/3D-Speaker)：说话人识别与验证，AX650
- [3D-Speaker-Meeting-Summary](https://huggingface.co/AXERA-TECH/3D-Speaker-Meeting-Summary)：会议音频摘要，AX650
- [3D-Speaker-MT.Axera](https://huggingface.co/AXERA-TECH/3D-Speaker-MT.Axera)：会议音频转录（含 Web UI），AX650

## TTS（语音合成）

- [kokoro.axera](https://huggingface.co/AXERA-TECH/kokoro.axera)：Kokoro 多语种 TTS（中/英/日），AX650 / AX630C
- [MeloTTS](https://huggingface.co/AXERA-TECH/MeloTTS)：MeloTTS 多语种合成，AX650 / AX630C
- [CosyVoice2](https://huggingface.co/AXERA-TECH/CosyVoice2)：CosyVoice 2 语音克隆与合成，AX650
- [CosyVoice3](https://huggingface.co/AXERA-TECH/CosyVoice3)：CosyVoice 3，AX650
- [Qwen3-TTS-12Hz-0.6B-Base-AX650](https://huggingface.co/AXERA-TECH/Qwen3-TTS-12Hz-0.6B-Base-AX650)：Qwen3 TTS 0.6B，AX650
- [Qwen3-TTS-12Hz-1.7B-VoiceDesign-AX650](https://huggingface.co/AXERA-TECH/Qwen3-TTS-12Hz-1.7B-VoiceDesign-AX650)：Qwen3 TTS 1.7B 声音设计，AX650
- [MOSS-TTS-Nano.AXERA](https://huggingface.co/AXERA-TECH/MOSS-TTS-Nano.AXERA)：MOSS TTS 超轻量合成，AX650
- [ZipVoice.AXERA](https://huggingface.co/AXERA-TECH/ZipVoice.AXERA)：ZipVoice 低延迟合成，AX650
- [VoxCPM](https://huggingface.co/AXERA-TECH/VoxCPM)：VoxCPM 语音合成，AX650

## VAD / 降噪

- [SileroVAD](https://huggingface.co/AXERA-TECH/SileroVAD)：语音活动检测，AX650
- [gtcrn.axera](https://huggingface.co/AXERA-TECH/gtcrn.axera)：实时降噪，AX650 / AX630C
- [Lightweight-Speech-Denoising.axera](https://huggingface.co/AXERA-TECH/Lightweight-Speech-Denoising.axera)：轻量降噪，AX650 / AX630C / AX620Q / AX620L / AX637 / AX525
- [mel_band_roformer](https://huggingface.co/AXERA-TECH/mel_band_roformer)：音乐/人声分离，AX650

## Embedding / 翻译

- [jina-embeddings-v5-omni-small](https://huggingface.co/AXERA-TECH/jina-embeddings-v5-omni-small)：多模态 Embedding（含音频），AX650
- [Speech-Translation.axera](https://huggingface.co/AXERA-TECH/Speech-Translation.axera)：语音翻译方案，AX650
- [Spoken-Communication.axera](https://huggingface.co/AXERA-TECH/Spoken-Communication.axera)：口语交互方案，AX650
