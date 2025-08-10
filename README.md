# AI Book Reader 📚🤖

利用摄像头拍摄绘本书页，通过 OCR（文字识别）+ TTS（语音合成）实现自动朗读的 AI 阅读助手。  
本项目旨在帮助儿童和家长更方便地阅读纸质绘本，未来计划加入互动问答、情境音效、多语言等功能。

---

## ✨ 功能特性
- 📷 **实时拍照识别**：使用笔记本摄像头拍摄书页并识别文字  
- 🔤 **OCR 文字提取**：基于 PaddleOCR 支持中文和多语言  
- 🔊 **TTS 自然朗读**：本地语音引擎朗读识别结果  
- 🖥 **跨平台支持**：Windows / macOS / Linux

---

## 🚀 快速开始

### 1. 克隆仓库
```bash
git clone https://github.com/draco9/ai-book-reader.git
cd ai-book-reader
```

### 2. 安装依赖
建议使用 Python 3.10+，并新建虚拟环境：

```bash
python3 -m venv venv
source venv/bin/activate   # Mac / Linux
venv\Scripts\activate      # Windows

pip install -r requirements.txt
```

### 3. 运行程序
```bash
python app.py
```

- 按 `s` 键拍照并识别文字，随后朗读  
- 按 `q` 键退出程序

---

## 📦 依赖
- [OpenCV](https://opencv.org/) — 负责摄像头视频输入  
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) — 中文及多语言文字识别  
- [pyttsx3](https://pyttsx3.readthedocs.io/en/latest/) — 本地语音合成播放

---

## 🛠 计划功能
- 儿童化润色，提升朗读故事感  
- 支持多角色配音及情境音效  
- 多语言支持（中英双语等）  
- 互动问答模式

---

## 📄 许可证
本项目基于 [MIT License](LICENSE) 开源，欢迎自由使用与修改。

---

## 🤝 贡献指南
1. Fork 本仓库  
2. 新建功能分支 `git checkout -b feature/your-feature`  
3. 提交更改 `git commit -m 'Add some feature'`  
4. 推送分支 `git push origin feature/your-feature`  
5. 提交 Pull Request

---

## 📧 联系
如有疑问或建议，欢迎在 Issues 中提出或直接联系我。
