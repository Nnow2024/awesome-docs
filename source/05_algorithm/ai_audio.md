# Audio 类算法

本页列出已在爱芯 NPU 平台完成适配的语音/音频模型。所有模型可通过 AXERA 模型仓库（[Hugging Face](https://huggingface.co/AXERA-TECH) | [ModelScope](https://modelscope.cn/organization/AXERA-TECH)）下载预编译 axmodel。

运行示例与上板命令见 [示例展示](samples_board.md)。

## ASR（语音识别）

- SenseVoice：多语种语音识别（中/英/日/粤/韩），AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/SenseVoice) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SenseVoice)
- Whisper：OpenAI Whisper 多语种语音识别，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Whisper) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Whisper)
- FireRedASR-AED：端到端语音识别，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/FireRedASR-AED) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/FireRedASR-AED)
- WeNet：WeNet 流式/非流式语音识别，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/WeNet) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/WeNet)
- Qwen3-ASR-0.6B：Qwen3 语音识别 0.6B，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-ASR-0.6B-AX8850N-C64-P448-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-ASR-0.6B-AX8850N-C64-P448-CTX2047)
- Zipformer.axera：Zipformer 流式识别，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Zipformer.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Zipformer.axera)

## 说话人识别 / 会议转录

- 3D-Speaker：说话人识别与验证，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/3D-Speaker) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/3D-Speaker)
- 3D-Speaker-Meeting-Summary：会议音频摘要，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/3D-Speaker-Meeting-Summary) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/3D-Speaker-Meeting-Summary)
- 3D-Speaker-MT.Axera：会议音频转录（含 Web UI），AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/3D-Speaker-MT.Axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/3D-Speaker-MT.Axera)

## TTS（语音合成）

- kokoro.axera：Kokoro 多语种 TTS（中/英/日），AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/kokoro.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/kokoro.axera)
- MeloTTS：MeloTTS 多语种合成，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/MeloTTS) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MeloTTS)
- CosyVoice2：CosyVoice 2 语音克隆与合成，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/CosyVoice2) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/CosyVoice2)
- CosyVoice3：CosyVoice 3，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/CosyVoice3) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/CosyVoice3)
- Qwen3-TTS-12Hz-0.6B-Base-AX8850N：Qwen3 TTS 0.6B，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-TTS-12Hz-0.6B-Base-AX8850N) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-TTS-12Hz-0.6B-Base-AX8850N)
- Qwen3-TTS-12Hz-1.7B-VoiceDesign-AX8850N：Qwen3 TTS 1.7B 声音设计，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-TTS-12Hz-1.7B-VoiceDesign-AX8850N) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-TTS-12Hz-1.7B-VoiceDesign-AX8850N)
- MOSS-TTS-Nano.AXERA：MOSS TTS 超轻量合成，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/MOSS-TTS-Nano.AXERA) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MOSS-TTS-Nano.AXERA)
- ZipVoice.AXERA：ZipVoice 低延迟合成，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/ZipVoice.AXERA) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/ZipVoice.AXERA)
- VoxCPM：VoxCPM 语音合成，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/VoxCPM) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/VoxCPM)

## VAD / 降噪

- SileroVAD：语音活动检测，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/SileroVAD) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SileroVAD)
- gtcrn.axera：实时降噪，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/gtcrn.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/gtcrn.axera)
- Lightweight-Speech-Denoising.axera：轻量降噪，AX8850N / AX8910 | [HuggingFace](https://huggingface.co/AXERA-TECH/Lightweight-Speech-Denoising.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Lightweight-Speech-Denoising.axera)
- mel_band_roformer：音乐/人声分离，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/mel_band_roformer) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/mel_band_roformer)

## Embedding / 翻译

- jina-embeddings-v5-omni-small：多模态 Embedding（含音频），AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/jina-embeddings-v5-omni-small) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/jina-embeddings-v5-omni-small)
- Speech-Translation.axera：语音翻译方案，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Speech-Translation.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Speech-Translation.axera)
- Spoken-Communication.axera：口语交互方案，AX8850N | [HuggingFace](https://huggingface.co/AXERA-TECH/Spoken-Communication.axera) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Spoken-Communication.axera)
