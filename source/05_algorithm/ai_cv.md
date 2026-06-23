# CV 类算法

本页列出已在爱芯 NPU 平台完成适配的计算机视觉模型。所有模型可通过 [AXERA 模型仓库](https://huggingface.co/AXERA-TECH) 下载预编译 axmodel。

运行示例与上板命令见 [示例展示](samples_board.md)。

## 目标检测

### YOLO 系列

- [YOLOv5](https://huggingface.co/AXERA-TECH/YOLOv5)：检测，AX650 / AX630C
- [YOLOv5-Seg](https://huggingface.co/AXERA-TECH/YOLOv5-Seg)：实例分割，AX650 / AX630C
- [YOLOv7-Face](https://huggingface.co/AXERA-TECH/YOLOv7-Face)：人脸检测，AX650
- [YOLOv8](https://huggingface.co/AXERA-TECH/YOLOv8)：检测，AX650 / AX630C
- [YOLOv8-Seg](https://huggingface.co/AXERA-TECH/YOLOv8-Seg)：实例分割，AX650 / AX630C
- [YOLOv8-Pose](https://huggingface.co/AXERA-TECH/YOLOv8-Pose)：姿态估计，AX650 / AX630C
- [YOLOv8-Aquarium](https://huggingface.co/AXERA-TECH/YOLOv8-Aquarium)：水族馆检测，AX650
- [YOLO11](https://huggingface.co/AXERA-TECH/YOLO11)：检测，AX650 / AX630C
- [YOLO11-Seg](https://huggingface.co/AXERA-TECH/YOLO11-Seg)：实例分割，AX650 / AX630C
- [YOLO11-Pose](https://huggingface.co/AXERA-TECH/YOLO11-Pose)：姿态估计，AX650 / AX630C
- [yolo11-obb](https://huggingface.co/AXERA-TECH/yolo11-obb)：旋转框检测，AX650 / AX8850 / AX637
- [yolo26](https://huggingface.co/AXERA-TECH/yolo26)：检测，AX650 / AX8850 / AX630C / AX637 / AX615
- [yolo26-seg](https://huggingface.co/AXERA-TECH/yolo26-seg)：实例分割，AX650 / AX8850 / AX630C / AX615 / AX637
- [yolo26-pose](https://huggingface.co/AXERA-TECH/yolo26-pose)：姿态估计，AX650 / AX8850 / AX630C / AX615 / AX637
- [yolo26-obb](https://huggingface.co/AXERA-TECH/yolo26-obb)：旋转框检测，AX650 / AX8850 / AX630C / AX615 / AX637

### 开放词汇 / Transformer 检测

- [YOLO-World-V2](https://huggingface.co/AXERA-TECH/YOLO-World-V2)：开放词汇检测，AX650 / AX630C
- [RT-DETR](https://huggingface.co/AXERA-TECH/RT-DETR)：实时端到端检测，AX650
- [DEIMv2](https://huggingface.co/AXERA-TECH/DEIMv2)：端到端检测，AX650
- [Deformable-Detr](https://huggingface.co/AXERA-TECH/Deformable-Detr)：Deformable DETR，AX650
- [OWLViT2](https://huggingface.co/AXERA-TECH/OWLViT2)：开放词汇视觉检测，AX650

### 行业场景检测

- [Helmet-axera](https://huggingface.co/AXERA-TECH/Helmet-axera)：安全帽检测
- [Gesture-axera](https://huggingface.co/AXERA-TECH/Gesture-axera)：手势识别
- [E_bike-axera](https://huggingface.co/AXERA-TECH/E_bike-axera)：电动车检测
- [Package-axera](https://huggingface.co/AXERA-TECH/Package-axera)：包裹检测
- [Plate-axera](https://huggingface.co/AXERA-TECH/Plate-axera)：车牌检测
- [Pet-axera](https://huggingface.co/AXERA-TECH/Pet-axera)：宠物检测
- [Fall-axera](https://huggingface.co/AXERA-TECH/Fall-axera)：跌倒检测
- [Drone-axera](https://huggingface.co/AXERA-TECH/Drone-axera)：无人机检测
- [Cow-axera](https://huggingface.co/AXERA-TECH/Cow-axera)：牛只检测
- [Person_car-axera](https://huggingface.co/AXERA-TECH/Person_car-axera)：人车检测
- [QRCode-axera](https://huggingface.co/AXERA-TECH/QRCode-axera)：二维码检测
- [Bird-Species-Classification](https://huggingface.co/AXERA-TECH/Bird-Species-Classification)：鸟类分类
- [pp-nsfw_Inspector](https://huggingface.co/AXERA-TECH/pp-nsfw_Inspector)：内容安全审核

## 分割

- [MobileSAM](https://huggingface.co/AXERA-TECH/MobileSAM)：轻量 Segment Anything，AX650 / AX630C / AX620E
- [EdgeTAM](https://huggingface.co/AXERA-TECH/EdgeTAM)：边缘端 Track Anything，AX650
- [DeepLabv3Plus](https://huggingface.co/AXERA-TECH/DeepLabv3Plus)：语义分割，AX650

## 人脸

- [Insightface](https://huggingface.co/AXERA-TECH/Insightface)：人脸检测 / 识别 / 关键点，AX650

## 深度估计

- [Depth-Anything-V2](https://huggingface.co/AXERA-TECH/Depth-Anything-V2)：单目深度估计，AX650 / AX630C
- [Depth-Anything-3](https://huggingface.co/AXERA-TECH/Depth-Anything-3)：单目深度估计 v3，AX650 / AX637
- [IGEV-plusplus](https://huggingface.co/AXERA-TECH/IGEV-plusplus)：双目立体匹配，AX650
- [RAFT-stereo](https://huggingface.co/AXERA-TECH/RAFT-stereo)：双目立体匹配，AX650

## 图像增强 / 超分 / 修复

- [Real-ESRGAN](https://huggingface.co/AXERA-TECH/Real-ESRGAN)：真实世界超分辨率，AX650 / AX630C
- [Real-ESRGAN.axera](https://huggingface.co/AXERA-TECH/Real-ESRGAN.axera)：Real-ESRGAN 方案包，AX650
- [CodeFormer](https://huggingface.co/AXERA-TECH/CodeFormer)：人脸修复，AX650
- [DeOldify](https://huggingface.co/AXERA-TECH/DeOldify)：黑白上色，AX650
- [SuperResolution](https://huggingface.co/AXERA-TECH/SuperResolution)：通用超分，AX650
- [Z-Image-Turbo](https://huggingface.co/AXERA-TECH/Z-Image-Turbo)：图像增强，AX650
- [RIFE.axera](https://huggingface.co/AXERA-TECH/RIFE.axera)：视频插帧，AX650
- [RMBG-1.4](https://huggingface.co/AXERA-TECH/RMBG-1.4)：背景移除，AX650

## 跟踪

- [MixFormerV2](https://huggingface.co/AXERA-TECH/MixFormerV2)：单目标跟踪，AX650 / AX630C

## CLIP / 图文对齐

- [clip](https://huggingface.co/AXERA-TECH/clip)：OpenAI CLIP，AX650
- [FG-CLIP](https://huggingface.co/AXERA-TECH/FG-CLIP)：细粒度 CLIP，AX650
- [MobileCLIP](https://huggingface.co/AXERA-TECH/MobileCLIP)：轻量 CLIP，AX650
- [LibCLIP](https://huggingface.co/AXERA-TECH/LibCLIP)：CLIP 推理库，AX650
- [jina-clip-v2](https://huggingface.co/AXERA-TECH/jina-clip-v2)：Jina CLIP v2，AX650
- [siglip-so400m-patch14-384](https://huggingface.co/AXERA-TECH/siglip-so400m-patch14-384)：SigLIP，AX650
- [siglip2-base-patch16-224](https://huggingface.co/AXERA-TECH/siglip2-base-patch16-224)：SigLIP2，AX650
- [cnclip](https://huggingface.co/AXERA-TECH/cnclip)：中文 CLIP，AX650
- [ViT-L-14-336__axera](https://huggingface.co/AXERA-TECH/ViT-L-14-336__axera)：ViT-L/14 CLIP，AX650
- [ViT-L-14-336-CN__axera](https://huggingface.co/AXERA-TECH/ViT-L-14-336-CN__axera)：ViT-L/14 中文 CLIP，AX650
- [dinov3_vits_pretrain_lvd1689m](https://huggingface.co/AXERA-TECH/dinov3_vits_pretrain_lvd1689m)：DINOv3 ViT-S，AX650
- [immich](https://huggingface.co/AXERA-TECH/immich)：Immich 图像分类模型，AX650

## 姿态 / 关键点

- [superpoint](https://huggingface.co/AXERA-TECH/superpoint)：特征点检测与描述，AX650 / AX637
- [RTMPose](https://huggingface.co/AXERA-TECH/RTMPose)：实时人体姿态估计，AX650 / AX8850

## 生成

- [lcm-lora-sdv1-5](https://huggingface.co/AXERA-TECH/lcm-lora-sdv1-5)：Stable Diffusion 1.5 + LCM-LoRA，AX650
- [lcm-lora-sdv1-5-ax620e](https://huggingface.co/AXERA-TECH/lcm-lora-sdv1-5-ax620e)：Stable Diffusion 1.5，AX620E
- [LivePortrait](https://huggingface.co/AXERA-TECH/LivePortrait)：肖像动画驱动，AX650 / AX8850

## OCR

- [PPOCR_v5](https://huggingface.co/AXERA-TECH/PPOCR_v5)：PaddleOCR v5 检测+识别，AX650 / AX630C / AX615
- [satrn](https://huggingface.co/AXERA-TECH/satrn)：场景文本识别，AX650
- [OCR_RAG-AX650N](https://huggingface.co/AXERA-TECH/OCR_RAG-AX650N)：OCR + RAG 方案，AX650

## 3D / BEV

- [bevformer](https://huggingface.co/AXERA-TECH/bevformer)：BEV 感知，AX650
- [centerpoint](https://huggingface.co/AXERA-TECH/centerpoint)：3D 目标检测，AX650
