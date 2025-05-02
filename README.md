# edge.ai.rknn.model.zoo.testing.ACP-3588
About [ACP-3588](https://www.avalue.com/tw/product/Industrial-Embedded-Motherboard/ARM-based-SBC/ACP-3588 "ACP-3588") [RKNN Model Zoo](https://github.com/airockchip/rknn_model_zoo "RKNN Model Zoo") Testing Result.
This repository contains Avalue Technology Inc., ACP-3588 with Debian 11 runing RKNN Model Zoo Testing result.

# Hardware Requirement
Please build and deploy RKNN Model Zoo sample code to the ACP-3588 with Debian 11 Firmware.

---

# LPRNet
**Usage:**
````bash
./rknn_LPRNet_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_LPRNet_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_LPRNet_demo.01.JPG "rknn_LPRNet_demo.01.JPG")
![rknn_LPRNet_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_LPRNet_demo.02.JPG "rknn_LPRNet_demo.02.JPG")

**Reference.** [RKNN Model Zoo > LPRNet](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/LPRNet "LPRNet")

# RetinaFace
**Usage:**
````bash
./rknn_retinaface_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_retinaface_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_retinaface_demo.01.JPG "rknn_retinaface_demo.01.JPG")
![rknn_retinaface_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_retinaface_demo.02.JPG "rknn_retinaface_demo.02.JPG")

**Reference.** [RKNN Model Zoo > RetinaFace](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/RetinaFace "RetinaFace")

# clip
**Usage:**
````bash
./rknn_clip_demo <image_model_path> <image_path> <text_model_path> <text_path>
````
**Testing Result.**
![rknn_clip_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_clip_demo.01.JPG "rknn_clip_demo.01.JPG")

**Reference.** [RKNN Model Zoo > clip](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/clip "clip")

# lite_transformer
**Usage:**
````bash
./rknn_lite_transformer_demo <encoder_path> <decoder_path> <sentence>
````
**Testing Result.**
![rknn_lite_transformer_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_lite_transformer_demo.01.JPG "rknn_lite_transformer_demo.01.JPG")

**Reference.** [RKNN Model Zoo > lite_transformer](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/lite_transformer "lite_transformer")

# mms_tts
**Usage:**
````bash
./rknn_mms_tts_demo <encoder_path> <decoder_path> <input_text>
````
**Testing Result.**
![rknn_mms_tts_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_mms_tts_demo.01.JPG "rknn_mms_tts_demo.01.JPG")
![rknn_mms_tts_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_mms_tts_demo.02.JPG "rknn_mms_tts_demo.02.JPG")

**Reference.** [RKNN Model Zoo > mms_tts](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/mms_tts "mms_tts")

# mobilenet
**Usage:**
````bash
./rknn_mobilenet_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_mobilenet_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_mobilenet_demo.01.JPG "rknn_mobilenet_demo.01.JPG")

**Reference.** [RKNN Model Zoo > mobilenet](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/mobilenet "mobilenet")

# mobilesam
**Usage:**
````bash
./rknn_mobilesam_demo <encoder_model_path> <image_path> <decoder_model_path>  <point_coords_path> <point_labels_path>
````
**Testing Result.**
![rknn_mobilesam_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_mobilesam_demo.01.JPG "rknn_mobilesam_demo.01.JPG")
![rknn_mobilesam_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_mobilesam_demo.02.JPG "rknn_mobilesam_demo.02.JPG")

**Reference.** [RKNN Model Zoo > mobilesam](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/mobilesam "mobilesam")

# ppseg
**Usage:**
````bash
./rknn_ppseg_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_ppseg_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_ppseg_demo.01.JPG "rknn_ppseg_demo.01.JPG")
![rknn_ppseg_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_ppseg_demo.02.JPG "rknn_ppseg_demo.02.JPG")

**Reference.** [RKNN Model Zoo > ppseg](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/ppseg "ppseg")

# ppyoloe
**Usage:**
````bash
./rknn_ppyoloe_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_ppyoloe_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_ppyoloe_demo.01.JPG "rknn_ppyoloe_demo.01.JPG")
![rknn_ppyoloe_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_ppyoloe_demo.02.JPG "rknn_ppyoloe_demo.02.JPG")

**Reference.** [RKNN Model Zoo > ppyoloe](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/ppyoloe "ppyoloe")

# resnet
**Usage:**
````bash
./rknn_resnet_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_resnet_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_resnet_demo.01.JPG "rknn_resnet_demo.01.JPG")

**Reference.** [RKNN Model Zoo > resnet](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/resnet "resnet")

# wav2vec2
**Usage:**
````bash
./rknn_wavvec2_demo <model_path> <audio_path>
````
**Testing Result.**
![rknn_wav2vec2_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_wav2vec2_demo.01.JPG "rknn_wav2vec2_demo.01.JPG")

**Reference.** [RKNN Model Zoo > wav2vec2](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/wav2vec2 "wav2vec2")

# whisper
**Usage:**
````bash
./rknn_whisper_demo <encoder_path> <decoder_path> <task> <audio_path>
````
**Testing Result.**
![rknn_whisper_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_whisper_demo.01.JPG "rknn_whisper_demo.01.JPG")

**Reference.** [RKNN Model Zoo > whisper](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/whisper "whisper")

# yamnet
**Usage:**
````bash
./rknn_yamnet_demo <model_path> <audio_path>
````
**Testing Result.**
![rknn_yamnet_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yamnet_demo.01.JPG "rknn_yamnet_demo.01.JPG")

**Reference.** [RKNN Model Zoo > yamnet](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yamnet "yamnet")

# yolo11
**Usage:**
````bash
./rknn_yolo11_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolo11_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolo11_demo.01.JPG "rknn_yolo11_demo.01.JPG")
![rknn_yolo11_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolo11_demo.02.JPG "rknn_yolo11_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolo11](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolo11 "yolo11")

# yolo_world
**Usage:**
````bash
./rknn_yolo_world_demo <text_model_path> <yolo_world_model_path> <image_path>
````
**Testing Result.**
![rknn_yolo_world_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolo_world_demo.01.JPG "rknn_yolo_world_demo.01.JPG")
![rknn_yolo_world_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolo_world_demo.02.JPG "rknn_yolo_world_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolo_world](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolo_world "yolo_world")

# yolov10
**Usage:**
````bash
./rknn_yolov10_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov10_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov10_demo.01.JPG "rknn_yolov10_demo.01.JPG")
![rknn_yolov10_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov10_demo.02.JPG "rknn_yolov10_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov10](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov10 "yolov10")

# yolov5
**Usage:**
````bash
./rknn_yolov5_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov5_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov5_demo.01.JPG "rknn_yolov5_demo.01.JPG")
![rknn_yolov5_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov5_demo.02.JPG "rknn_yolov5_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov5](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov5 "yolov5")

# yolov5_seg
**Usage:**
````bash
./rknn_yolov5_seg_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov5_seg_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov5_seg_demo.01.JPG "rknn_yolov5_seg_demo.01.JPG")
![rknn_yolov5_seg_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov5_seg_demo.02.JPG "rknn_yolov5_seg_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov5_seg](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov5_seg "yolov5_seg")

# yolov6
**Usage:**
````bash
./rknn_yolov6_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov6_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov6_demo.01.JPG "rknn_yolov6_demo.01.JPG")
![rknn_yolov6_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov6_demo.02.JPG "rknn_yolov6_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov6](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov6 "yolov6")

# yolov7
**Usage:**
````bash
./rknn_yolov7_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov7_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov7_demo.01.JPG "rknn_yolov7_demo.01.JPG")
![rknn_yolov7_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov7_demo.02.JPG "rknn_yolov7_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov7](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov7 "yolov7")

# yolov8
**Usage:**
````bash
./rknn_yolov8_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov8_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_demo.01.JPG "rknn_yolov8_demo.01.JPG")
![rknn_yolov8_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_demo.02.JPG "rknn_yolov8_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov8](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov8 "yolov8")

# yolov8_obb
**Usage:**
````bash
./rknn_yolov8_obb_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov8_obb_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_obb_demo.01.JPG "rknn_yolov8_obb_demo.01.JPG")
![rknn_yolov8_obb_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_obb_demo.02.JPG "rknn_yolov8_obb_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov8_obb](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov8_obb "yolov8_obb")

# yolov8_pose
**Usage:**
````bash
./rknn_yolov8_pose_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov8_pose_demo.01.jpg](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_pose_demo.01.jpg "rknn_yolov8_pose_demo.01.jpg")
![rknn_yolov8_pose_demo.02.jpg](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_pose_demo.02.jpg "rknn_yolov8_pose_demo.02.jpg")

**Reference.** [RKNN Model Zoo > yolov8_pose](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov8_pose "yolov8_pose")

# yolov8_seg
**Usage:**
````bash
./rknn_yolov8_seg_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolov8_seg_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_seg_demo.01.JPG "rknn_yolov8_seg_demo.01.JPG")
![rknn_yolov8_seg_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolov8_seg_demo.02.JPG "rknn_yolov8_seg_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolov8_seg](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolov8_seg "yolov8_seg")

# yolox
**Usage:**
````bash
./rknn_yolox_demo <model_path> <image_path>
````
**Testing Result.**
![rknn_yolox_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolox_demo.01.JPG "rknn_yolox_demo.01.JPG")
![rknn_yolox_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_yolox_demo.02.JPG "rknn_yolox_demo.02.JPG")

**Reference.** [RKNN Model Zoo > yolox](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/yolox "yolox")

# zipformer
**Usage:**
````bash
./rknn_zipformer_demo <encoder_path> <decoder_path> <joiner_path> <audio_path>
````
**Testing Result.**
![rknn_zipformer_demo.01.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_zipformer_demo.01.JPG "rknn_zipformer_demo.01.JPG")
![rknn_zipformer_demo.02.JPG](https://raw.githubusercontent.com/Avalue-Technology/edge.ai.rknn.model.zoo.testing.ACP-3588/refs/heads/main/MarkdownDocumentImages/rknn_zipformer_demo.02.JPG "rknn_zipformer_demo.02.JPG")

**Reference.** [RKNN Model Zoo > zipformer](https://github.com/airockchip/rknn_model_zoo/tree/main/examples/zipformer "zipformer")
