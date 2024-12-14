# mPLUG: Effective and Efficient Vision-Language Learning by Cross-modal Skip-connections.

[https://arxiv.org/abs/2205.12005](https://arxiv.org/abs/2205.12005)
                            
# Image Captioning
The COCO Caption dataset can be downloaded from its original websites.
Unzip the provided dataset json files which are bucket.dat and bucket.tar.
Get language evalution tool(language_evalution) free.
In the configs/caption_mplug_base.yaml set the paths for the json files as well as the image paths.

# Visual Grounding
Click on the web links to download RefCOCO datasets for further use.
The original data needed for this analysis is in json format, the first step involves downloading and unarchiving of these files.
In configs/grounding_mplug_large.yaml, we define the path to the json and the image path. Data preparation can follow TransVG or it can follow the path as shown below.
