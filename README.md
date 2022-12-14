# Diffusion-Models
We present an implementation of "Denoising Diffusion Probabilistic Models" presented in NeurIPS 2020. The paper was implemented using a simplified version of U-Net trained on 64x64 CelebA dataset consisting of over 200k colored images of celebrities. <br />
<br />
Original Paper link: https://arxiv.org/abs/2006.11239<br />
<br />
Sample Result after 7 epochs -<br />
![Alt text](/Results/image12.png?raw=true "Image Generated after 7 epochs")
<br />

The dataset can be downloaded from Kaggle: https://www.kaggle.com/datasets/jessicali9530/celeba-dataset <br />

Experiments run on Anaconda using Jupyter Notebook. Use the following commands in the Anaconda command prompt after activating your environment:<br />
```
conda install -c pytorch pytorch
conda install -c conda-forge matplotlib
conda install -c anaconda pandas
conda install -c conda-forge einops
conda install -c anaconda numpy
```
<br />

Our trained model can be found here: https://drive.google.com/drive/folders/1NcRZPVq8WpLVjEH40XdN_gDpaMOpLvks?usp=share_link 
<br />
The model can be directly used after running the model definition in the `Block 9` of the Notebook using `torch.load('attention_model_newhead.pth')`
<br />
<br />
Details on architecture can be found here: https://drive.google.com/file/d/1grWzPINot13U4QXnJpZYW9eKyX62zywf/view?usp=share_link<br />
<br />
More result samples are in `Results/` subdirectory. <br />
