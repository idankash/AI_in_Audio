# AI in audio
Final Project Report in AI in Audio Course (Reichman University)
by Idan Kashtan

<img src="Unet_architecture.jpg" alt="Unet architecture" width="400"/>

Audio Source Separation is the problem of recovering or reconstructing one or more
source signals that have been mixed with other signals through some linear or convolutive process. 
The field has many practical applications including speech denoising and enhancement, music remixing, 
spatial audio, and remastering. In the context of music production, it is sometimes referred to as unmixing or demixing.
In this project, I use a U-NET-like architecture to separate vocals from music recordings. I use
10 the MUSDB18 dataset

This repository includes the following:
* The report document with my analysis and innovations (pdf)
* One notebook with my implementation, testing, and results

## Results
Detailed results can be found in the report under:
* "Experiments and Results"

## Running the notebooks
* The notebook is already configured with the best default hyperparameters for the dataset.

### For the dataset
Inside the notebook, there is a section called "Download Dataset". From there, you can download the MuseDB dataset. 
