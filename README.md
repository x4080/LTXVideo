<div align="center">

# LTX-Video

This is the official repository for LTX-Video.

[Website](https://www.lightricks.com/ltxv) |
[Github](https://github.com/Lightricks/LTX-Video) |
[Model](https://huggingface.co/Lightricks/LTX-Video) |
[Demo](https://fal.ai/models/fal-ai/ltx-video) |
[Paper (Soon)](https://github.com/Lightricks/LTX-Video)

</div>


# Windows installation
 - https://youtu.be/nur4_b4yzM0

# Additional info
https://www.youtube.com/watch?v=nur4_b4yzM0

Step 1: Clone the repository
    
    git clone https://github.com/newgenai79/LTXVideo

Step 2: Navigate inside the cloned repository
    
    cd LTXVideo

Step 3: Create virtual environment
    
    conda create -n LTXVideo python==3.10.11 -y

Step 4: Activate virtual environment
    
    conda activate LTXVideo

Step 5: Install wheel package

    pip install wheel

Step 6: Install requirements

    pip install -r requirements.txt

Step 7: Instal torchao

    pip install --pre torchao --index-url https://download.pytorch.org/whl/nightly/cpu

Step 8: Download models

    git clone https://huggingface.co/PixArt-alpha/PixArt-XL-2-1024-MS PixArt-alpha/PixArt-XL-2-1024-MS
    
    git clone https://huggingface.co/Lightricks/LTX-Video Lightricks/LTX-Video
    
Step 9: Inference (Update config.yaml)

    conda activate LTXVideo
    
    python inference.py
