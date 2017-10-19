# gait-cycle-transfer

Uses gait-cycle extractor method from Section 3.2. "Extraction of Walking Cycles" of the paper 
"IDNet: Smartphone-based Gait Recognition with Convolutional Neural Networks" [https://arxiv.org/abs/1606.03238] to extract gait cycles.

To transfer between gait cycles, I performed Neural Style Transfer [https://arxiv.org/abs/1508.06576] using the features from an IDNet [ArXiv:1606.03238] that I pre-trained on full IDNet dataset: http://signet.dei.unipd.it/human-sensing/


Data folder contains small data from 2 walks that was used for extracting 2 gate cycle templates

IDNet_dataset.csv is available at this link: https://drive.google.com/file/d/0Bz3fihKG133cOG13X2VXTXJqY1k/view 

IDNet_dataset.csv contains data that has been converted to csv from the log data contained in IDNet dataset at this URL: http://signet.dei.unipd.it/human-sensing/

###### Acknowledgements
- [@alexis-jacq](https://github.com/alexis-jacq)'s [Neural Style Transfer Tutorial](http://pytorch.org/tutorials/advanced/neural_style_tutorial.html)
