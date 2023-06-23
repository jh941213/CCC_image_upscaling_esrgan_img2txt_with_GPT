# CCC_image_upscaling_esrgan_img2txt_with_GPT
# Concept
## A.I with PICO
- AIOT with the latest AI technology  
- A realistic alternative to AI task
  
# AI Teams 
[김재현](http://github.com/jh941213) |[정유석](https://github.com/dbtjr1103) |
------|------|
Team Member|Team Member|
<img src="https://user-images.githubusercontent.com/112835087/214769736-c6880568-a4f9-42f7-b5d9-3ef466b6a997.jpeg" width="100" height="100">|<img src ="https://user-images.githubusercontent.com/112835087/227434260-00788b7e-16ec-4d71-b2a5-2fa5fff37e6b.png" width="100" height="100">
  
# Computer Environment
비고| LocalPC | Google Colab | Kaggle Notebook |
-----|-------|-------|-------|
GPU | rtx4090 | T4 | P100
RAM | 64GB |13~52GB|13GB|
Storage | 1TB |166GB|73GB| 

# Technology
 - [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN.git): Training Real-World Blind Super-Resolution with Pure Synthetic Data  
 - [vit-gpt2-image-captioning](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)img to text with ChatGPT hugging face model  

# Preparation  
LocalPC(GPU cuda setting) , Pico, LAN, Camera Module  

# PipeLine
<img width="166" alt="2" src="https://github.com/WiznetAI/CCC_image_upscaling_esrgan_img2txt_with_GPT/assets/132982685/d2dfca23-f9ca-41af-97d3-5252bb8387b7">


**how to run?**


```python
#esrgan
!git clone https://github.com/xinntao/Real-ESRGAN.git
```  
**Just git clone and slowly pick up the tutorials file.**
![l2fZCU97](https://github.com/WiznetAI/CCC_image_upscaling_esrgan_img2txt_with_GPT/assets/132982685/14257d0f-bd93-4037-8a5e-373a0a2ddfb0)
