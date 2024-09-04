# install-comfyui

--> Clone thư mục Comfyui từ git
git clone git@github.com:comfyanonymous/ComfyUI.git

--> Di chuyển tới thư mục comfyui chạy lênh -> Để cài đặt các phần cần thiết
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu124

--> If you get the "Torch not compiled with CUDA enabled" error, uninstall torch with:
pip uninstall torch

--> Install the dependencies by opening your terminal inside the ComfyUI folder and:

pip install -r requirements.txt