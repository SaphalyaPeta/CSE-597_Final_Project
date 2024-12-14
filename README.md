# mPLUG: Effective and Efficient Vision-Language Learning by Cross-modal Skip-connections.

[https://arxiv.org/abs/2205.12005](https://arxiv.org/abs/2205.12005)

                                          
### Image Captioning
                                                                                 
1. Download COCO Caption dataset from the original websites.
2. Download and extract the provided dataset json files.
3. Download language evalution tool([language_evalution](https://alice-open.oss-cn-zhangjiakou.aliyuncs.com/mPLUG/language_evaluation.tar)).
4. In configs/caption_mplug_base.yaml, set the paths for the json files and the image paths.
5. Finetune the pre-trained mplug_base or large model using 8 A100 GPUs:
<pre>sh scripts/caption_mplug_base.sh</pre> 
<pre>sh scripts/caption_mplug_large.sh</pre>  
                                                                                        
### Visual Grounding
1. Download RefCOCO datasets from the original websites.
2. Download and extract the provided dataset json files.
3. In configs/grounding_mplug_large.yaml, set the paths for the json files and the image path. Data preparation can follow [TransVG](https://github.com/djiajunustc/TransVG)
4. Finetune the pre-trained checkpoint using 8 A100 GPUs:
<pre> sh scripts/grounding_mplug_base.sh </pre>
