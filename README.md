---

# Hyundaye Demo

This repository provides a demo for the `hyundaye` project using a single PDF file processed with the `ollama` model and a local vector storage for efficient querying. The demo is deployed using Gradio with `app.py` as the main application file.

## Getting Started

### Prerequisites

- **Docker** - Make sure Docker is installed and running on your system.
- **Python 3.x** - Required to run the Gradio demo.
- **Gradio** - Install Gradio using pip.

### Installation

1. **Pull Docker Image**
   ```bash
   docker pull kunalgawande/hyundaye:0.1
   ```


2. **Navigate to the Project Directory**
   ```bash
   cd /hyundaye
   ```

3. **Run the Gradio Application**
   ```bash
   python3 app.py
   ```

### Usage

The application loads a single PDF file and uses a local vector store for indexing and querying content. This demo shows how to interact with the `ollama` model and provides a simple interface via Gradio.

### Notes

- **PDF File**: Place the PDF you want to use in the appropriate directory as specified in `app.py`.
- **Local Vector Storage**: The app uses local vector storage to index the PDF file for efficient querying.

---
