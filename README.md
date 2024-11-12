# GeoChat-KD
Official code for 'Lightweight Remote Sensing Multimodal Large Language Model Based on Knowledge Distillation'
## Install

1. Clone this repository and navigate to GeoChat-KD folder
```bash
git clone https://github.com/I3ab/GeoChat-KD.git
cd GeoChat-KD
```

2. Install Package
```Shell
conda create -n geochat-kd python=3.10 -y
conda activate geochat-kd
pip install --upgrade pip  # enable PEP 660 support
pip install -r environment.txt
```

3. Install additional packages for training cases
```
pip install ninja
pip install flash-attn --no-build-isolation
```


## Gradio demo(Web UI)
Download the lightweight model from [`GeoChat-KD`](https://huggingface.co/Oreowo/GeoChat-KD/tree/main). After loading the model, run this command by giving the model path to launch the gradio demo.

```Shell
python geochat_demo.py --model-path /path/to/model 
```
