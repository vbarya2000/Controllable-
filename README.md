\# Controllable Radish Growth Generation



A controllable image generation system for radish growth stages using:



\- Stable Diffusion

\- LoRA Fine-Tuning

\- ControlNet

\- Segmentation Masks



\## Project Structure



src/

dataset/

training/

generation/

evaluation/



\## Dataset



Custom radish growth dataset.



\## Training



python src/training/train\_lora.py



\## Generation



python src/generation/generate.py

## Main Notebook

The complete pipeline is implemented in:

```text
notebooks/generation.ipynb
