# peace.github.io

## ⏩ Quick Start
<details open>
<summary>Installation</summary>

 - Step1: Clone GeoMap-Agent code repository
```
git clone https://github.com/microsoft/PEACE.git
cd PEACE
```

 - Step2: Clone GeoMap-Bench dataset repository
```
git lfs install
git lfs clone https://huggingface.co/datasets/microsoft/PEACE data
```

 - Step3: Download layout detection models
```
pip install gdown
gdown https://drive.google.com/uc?id=1f7dUdfA_W8He9czG6SoYQBmUsSPrA6MZ
unzip models.zip -d dependencies
```

 - Step4: Install dependencies
```
pip install -r requirements.txt
```

 - Step5: Configure LLMs API endpoint and key in utils/api.py

</details>
