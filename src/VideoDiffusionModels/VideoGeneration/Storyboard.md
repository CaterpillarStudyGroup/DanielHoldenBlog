P108 
# 2.5 Storyboard
 
P109  
![](../../assets/08-109.png) 

P110 
## What is a storyboard?

> &#x2705; 难点：保持内容的一致性。   

P111

A concept in film production

![](../../assets/08-111.png) 

 - Rough sketches/drawings with notes    
 - Example: Inception by Christopher Nola   

Storyboard image from deviantart.com.    


P112 

## How to generate such a storyboard?    

 - As humans, over the years, we have acquired such “visual prior” about object location, object shape, relation, etc.   

 - Can LLM model such visual prio？      

P113   

|ID|Year|Name|Note|Tags|Link|
|---|---|---|---|---|---|
|61|2023|Xie et al., “VisorGPT: Learning Visual Prior via Generative Pre-Training,”|A “diffusion over diffusion” architecture for very long video generation ||[link](https://caterpillarstudygroup.github.io/ReadPapers/61.html)|
||2023|Lin et al., “VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning,”|Use storyboard as condition to generate video<br> &#x2705; Control Net，把文本转为 Pixel 图片。|![](../../assets/08-121.png) ![](../../assets/08-122.png) |
||2024|Xie et al., “Learning Long-form Video Prior via Generative Pre-Training,”|GPT can be trained to learn better long-form video prior (e.g., object position, relative size, human interaction)<br> &#x2705; 用 GPT-4 In-context learning 机制生成结构化文本<br> &#x2705; GPT 缺少一些视觉上的 commen sense 主要是缺少相关数据集。 <br> &#x2705; 因此这里提供了一个数据集**Storyboard20K**。 |![](../../assets/08-124.png) |[dataset](<https://github.com/showlab/Long-form-Video-Prior>)   |
|41|2024|STORYDIFFUSION: CONSISTENT SELF-ATTENTION FOR LONG-RANGE IMAGE AND VIDEO GENERATION|先生成一致的关键帧，再插帧成中间图像||[link](https://caterpillarstudygroup.github.io/ReadPapers/41.html)|

|||
|--|--|
|  ![](../../assets/08-125-1.png) | **Dysen-VDM** (Fei et al.)<br>Storyboard through scene graphs<br>“Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models,” arXiv 2023. |
| ![](../../assets/08-125-2.png)  | **DirectT2V** (Hong et al.) <br> Storyboard through bounding boxes <br> “Large Language Models are Frame-level Directors for Zero-shot Text-to-Video Generation,” arXiv 2023. |
|  ![](../../assets/08-125-3.png)  | **Free-Bloom** (Huang et al.)<br>Storyboard through detailed text prompts<br> “Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator,” NeurIPS 2023. |
|  ![](../../assets/08-125-4.png) | **LLM-Grounded Video Diffusion Models** (Lian et al.) <br> Storyboard through foreground bounding boxes <br> “LLM-grounded Video Diffusion Models,” arXiv 2023. |


---------------------------------------
> 本文出自CaterpillarStudyGroup，转载请注明出处。
>
> https://caterpillarstudygroup.github.io/ImportantArticles/