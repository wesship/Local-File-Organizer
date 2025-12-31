> [!NOTE]
> This project is a fork of [QiuYannnn/Local-File-Organizer](https://github.com/QiuYannnn/Local-File-Organizer). The original project and its contributors can be found there.

# Local File Organizer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![CI/CD Status](https://github.com/wesship/Local-File-Organizer/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/Local-File-Organizer/actions/workflows/ci.yml)

> An AI-powered file management tool that ensures privacy by organizing local texts and images. Using Llama3.2 3B and Llava v1.6 models with the Nexa SDK, it intuitively scans, restructures, and organizes files for quick, seamless access and easy retrieval.

---

## ✨ Features

- **AI-Powered Organization**: Uses Llama3.2 3B and LLaVA v1.6 to understand and categorize your files.
- **Privacy-Focused**: All processing is done locally, so your files never leave your computer.
- **Multi-Format Support**: Organizes images, documents, spreadsheets, presentations, and PDFs.
- **Customizable Sorting**: Sort by content, date, or file type.
- **Dry Run Mode**: Preview changes before they are made.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12
- Conda (Anaconda or Miniconda)
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wesship/Local-File-Organizer.git
   cd Local-File-Organizer
   ```
2. Create and activate a Conda environment:
   ```bash
   conda create --name local_file_organizer python=3.12
   conda activate local_file_organizer
   ```
3. Install the Nexa SDK (CPU version):
   ```bash
   pip install nexaai --prefer-binary --index-url https://nexaai.github.io/nexa-sdk/whl/cpu --extra-index-url https://pypi.org/simple --no-cache-dir
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

```bash
python main.py
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [Nexa SDK](https://github.com/NexaAI/nexa-sdk)
- [Llama3.2 3B](https://nexaai.com/meta/Llama3.2-3B-Instruct/gguf-q3_K_M/file)
- [LLaVA-v1.6](https://nexaai.com/liuhaotian/llava-v1.6-vicuna-7b/gguf-q4_0/file)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is dual-licensed under the MIT and Apache 2.0 Licenses - see the [LICENSE-MIT](LICENSE-MIT) and [LICENSE-APACHE](LICENSE-APACHE) files for details.
