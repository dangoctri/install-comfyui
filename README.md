# install-comfyui

--> Clone thư mục Comfyui từ git
git clone git@github.com:comfyanonymous/ComfyUI.git

--> Di chuyển tới thư mục comfyui chạy lênh -> Để cài đặt các phần cần thiết
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu124

--> If you get the "Torch not compiled with CUDA enabled" error, uninstall torch with:
pip uninstall torch

--> Install the dependencies by opening your terminal inside the ComfyUI folder and:

pip install -r requirements.txt


--> To install ComfyUI-Manager in addition to an existing installation of ComfyUI, you can follow the following steps:

 ---->goto ComfyUI/custom_nodes dir in terminal(cmd)

git clone https://github.com/ltdrdata/ComfyUI-Manager.git
Restart ComfyUI

Link hướng dẫn chi tiết chuẩn bị trước khi cài comfyui
https://tinhte.vn/thread/tong-hop-nhung-thu-can-cai-vao-pc-de-bat-dau-voc-ai-python-git-c-ffmpeg-cuda-pytorch.3769219/
