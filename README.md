# Yolov7-train
The method to install Yolov7  
cd C:\yolov7
conda create -n yolov7 python=3.9
pip install -r requirements.txt
pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
python
import torch
torch.cuda.is_available()
pip install numpy==1.23.1
