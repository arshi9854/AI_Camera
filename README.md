# AI_Camera
This Project is to show the real AI Camera in action using llama server and Small Vision Language model(SmolVLM)
steps:
-> Install LLama.cpp from https://github.com/ggml-org/llama.cpp/blob/master/docs/build.md and build it. I am using Ubantu desktop with GPU and I also used CUDA toolkit to build kit
-> Run cmake -B build -DLLAMA_CURL=ON -DGGML_CUDA=ON and cmake --build build --config Release
-> Run llama-server -hf ggml-org/SmolVLM-500M-Instruct-GGUF(install curl to do this)
-> To install curl ->sudo apt update and sudo apt install libcurl4-openssl-dev
-> Open index.html in web browser
