# AI Camera with LLama Server and SmolVLM

This project demonstrates a real AI Camera in action using **llama-server** and the **Small Vision Language Model (SmolVLM)**.

---

## 🚀 Steps to Run

1. **Install llama.cpp**  
   Follow the instructions from the official repo:  
   👉 https://github.com/ggml-org/llama.cpp/blob/master/docs/build.md

2. **System Requirements**  
   I used:
   - Ubuntu Desktop with GPU
   - CUDA Toolkit installed

3. **Build llama.cpp**
   ```bash
   cmake -B build -DLLAMA_CURL=ON -DGGML_CUDA=ON
   cmake --build build --config Release
   
4.  **Run the llama server**

   /build/bin/llama-server -hf ggml-org/SmolVLM-500M-Instruct-GGUF

5. **Install curl if needed**

   sudo apt update
   sudo apt install libcurl4-openssl-dev

Open the web interface
Open index.html in your browser.
