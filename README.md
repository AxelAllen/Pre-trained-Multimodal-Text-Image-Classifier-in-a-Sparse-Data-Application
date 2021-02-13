# Pre-Trained Multi-Modal Text and Image Classification in Sparse Medical Data Application

TODO:

* image submodule documentation
* run instructions and yaml files
* make MMBT importable as modules
* train/eval functions as imported modules

## This Directory File Organization

This project repository is organized as follows:

* **Pre-Trained Multi-Modal Text and Image Classifier in Sparse Data Application**: the parent project directory
* **data**: contains data files subdirectories and data preparation scripts
* **MMBT**: contains MMBT model src codes and related utility functions
* **runs**: saved Tensorboards for displaying models' performance 
* run_mmbt.py
* run_text_only.py

## Supervised Multimodal BiTransformers for Classifying Images and Text (MMBT)

In our project, we are experimenting with the Supervised Multimodal BiTransformers for Classifying Images and Text
(MMBT) presented by Kiela et al. (2020). This is a BERT-based model that can accommodate multi-modal inputs.
The model aims to fuse the multiple modalities as the input data are introduced to the Transformers
architecture so that the model's attention mechanism can be applied to the multimodal inputs. For more information
regarding the model, please refer to the documentation in the **MMBT** directory.

## Bibliography

>Kiela, D., Bhooshan, S., Firooz, H., Perez, E., & Testuggine, D. (2020).     
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Supervised Multimodal Bitransformers for Classifying Images and Text. ArXiv:1909.02950.  
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;http://arxiv.org/abs/1909.02950  