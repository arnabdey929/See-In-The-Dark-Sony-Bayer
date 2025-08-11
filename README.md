# See-In-The-Dark-Sony-Bayer
A U-Net based model that directly takes in RAW sensor data to enhance extreme low light photos.
<img width="990" height="252" alt="Comparison Plot" src="https://github.com/user-attachments/assets/58feba8f-70cd-4014-ba47-3ec0e904aad8" />
This repo contains the pytorch implementation of the paper \textit{"Learning to see in the Dark"} : https://arxiv.org/abs/1805.01934

I trained a model for 10 epochs on the whole dataset, and converted the pyTorch model to a CoreML model. The XCode build files are provided in the Apple XCode Folder.
