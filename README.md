# Talk-Head-Generation
Something about Talking Head Generation

## Video driven
| Pub |  Title  |Links|
|:--------:| :-------------|:-------------:|
|CVPR(2021) | PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering|[PDF](https://arxiv.org/pdf/2109.08379)/[code](https://github.com/RenYurui/PIRender) |
|CVPR(2022) | StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pre-trained StyleGAN|[PDF](https://arxiv.org/pdf/2203.04036.pdf)/[code](https://github.com/FeiiYin/StyleHEAT) |
|CVPR(2022) | Depth-Aware Generative Adversarial Network for Talking Head Video Generation|[PDF](https://arxiv.org/pdf/2203.06605)/[code](https://github.com/harlanhong/CVPR2022-DaGAN) |
| ICLR(2022)|Latent Image Animator: Learning to Animate Images via Latent Space Navigation |[PDF](https://arxiv.org/pdf/2203.09043)/[code](https://github.com/wyhsirius/LIA) |
|ECCV(2022) |Face2Face:Real-Time High-Resolution One-Shot Face Reenactment |[PDF](https://github.com/NetEase-GameAI/Face2FaceRHO/blob/master/paper.pdf)/[code](https://github.com/NetEase-GameAI/Face2FaceRHO) |
|WACV(2023) |Audio-Visual Face Reenactment |[PDF](http://cvit.iiit.ac.in/images/Projects/avfr/paper.pdf)/[code](https://github.com/mdv3101/AVFR-Gan) |


## Audio driven
| Pub |  Title  |Links| Notes|
|:--------:| :-------------|:-------------:|:-------------|
|CoRR(2020)|Audio-driven Talking Face Video Generation with Learning-based Personalized Head Pose|[PDF](http://arxiv.org/abs/2002.10137)/[code](https://github.com/yiranran/Audio-driven-TalkingFace-HeadPose) |Audio to 3D face mapping|
|IJCAI(2021)| Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion |[PDF](https://arxiv.org/pdf/2107.09293)/[code](https://github.com/wangsuzhen/Audio2Head) | |
|CVPR(2021)| Flow-guided One-shot Talking Face Generation with a High-resolutionAudio-visual Dataset|[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Flow-Guided_One-Shot_Talking_Face_Generation_With_a_High-Resolution_Audio-Visual_Dataset_CVPR_2021_paper.pdf)/[code](https://github.com/MRzzm/HDTF) | |
|CVPR(2021)| Audio-Driven Emotional Video Portraits |[PDF](https://arxiv.org/abs/2104.07452)/[code](https://github.com/jixinya/EVP) |
|CVPR(2021)|Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation |[PDF](https://arxiv.org/abs/2104.11116)/[code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS) | |
|ICCV(2021)|FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning |[PDF](https://arxiv.org/pdf/2108.07938.pdf)/[code](https://github.com/zhangchenxu528/FACIAL) | |
|arXiv(2021)|One-shot Talking Face Generation from Single-speaker Audio-Visual Correlation Learning|[PDF](https://arxiv.org/pdf/2112.02749.pdf)| |
|InterSpeech(2021)|Speech2Video: Cross-Modal Distillation for Speech to Video Generation |[PDF](https://arxiv.org/pdf/2107.04806v1)| |
|ACM MM(2022)|Talking Head from Speech Audio using a Pre-trained Image Generator | [PDF](https://dl.acm.org/doi/10.1145/3503161.3548101)/[code](https://github.com/MohammedAlghamdi/talking-heads-acm-mm) | |
|AAAI(2022) | SyncTalkFace: Talking Face Generation with Precise Lip-syncing via Audio-Lip Memory| [PDF](https://link.zhihu.com/?target=https%3A//www.aaai.org/AAAI22Papers/AAAI-7528.ParkS.pdf)| |
|arXiv(2022)|DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering|[PDF](https://arxiv.org/pdf/2201.00791.pdf)|
|arXiv(2022)| Perceptual Conversational Head Generation with Regularized Driver and Enhanced Renderer|[PDF](https://arxiv.org/abs/2206.12837)/[code](https://github.com/megvii-research/MM2022-ViCoPerceptualHeadGeneration) | |
|arXiv(2022)|Synthesizing Photorealistic Virtual Humans Through Cross-modal Disentanglement|[PDF](https://arxiv.org/pdf/2209.01320.pdf)| |
|WACV(2023) |Audio-Visual Face Reenactment |[PDF](http://cvit.iiit.ac.in/images/Projects/avfr/paper.pdf)/[code](https://github.com/mdv3101/AVFR-Gan) | |

## Text driven
| Pub |  Title  |Links|
|:--------:| :-------------|:-------------:|
|AAAI(2021)|Write-a-speaker: Text-based Emotional and Rhythmic Talking-head Generation|[PDF](https://arxiv.org/abs/2104.07995)/[code](https://github.com/FuxiVirtualHuman/Write-a-Speaker)|

## Dataset
| Name |  Source  |Statistics|Description|
|:--------:| :-------------:|:-------------:|:-------------|
|HDTF|https://github.com/MRzzm/HDTF |<img src="https://github.com/LTT-O/Talk-Head-Generation/blob/main/Image/HDTF.png" width="120%" height="120%" /> |High-resolution Audio-visual Dataset|
|CelebV-HQ|https://celebv-hq.github.io/ |<img src="https://github.com/LTT-O/Talk-Head-Generation/blob/main/Image/CelebV.png" width="120%" height="120%" /> |High-quality talking head dataset|
|TalkingHead-1KH|https://github.com/deepimagination/TalkingHead-1KH |	500k video clips, of which about 80k are greater than 512x512 resolution|Talking-head dataset consisting of YouTube videos|
| LRS3|https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html | <img src="https://github.com/LTT-O/Talk-Head-Generation/blob/main/Image/LRS3.png" width="120%" height="120%" />| Lip-reading recognition, including video and corresponding text|
| LRW|https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html | <img src="https://github.com/LTT-O/Talk-Head-Generation/blob/main/Image/LRW.png" width="120%" height="120%" />| Lip Reading in the Wild|
|MEAD|https://github.com/uniBruce/Mead|<img src="https://github.com/LTT-O/Talk-Head-Generation/blob/main/Image/MEAD.png" width="120%" height="120%" />|Talking Head dataset with emotion labels and intensity labels|


