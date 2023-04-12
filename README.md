<img src="logo.jpg" alt="Paris" class="center">

# Awesome-ComposableAI
[![Awesome ComposableAI](https://img.shields.io/badge/Awesome-ComposableAI-blue)](https://github.com/topics/awesome)

A curated list of Composable AI methods: Building AI system by composing modules.

It includes *Composable-Model*, *Composable-Task*, *Composable-Gen*, *Composable-Agent*, and *Composable-X*, etc.

**Contributions are welcome!**



<p style="text-align: center;">𓏠𓏠𓏠𓏠𓏠𓏠𓏠𓏠𓏠
<b>Let's build AI as Lego!<b>
𓏠𓏠𓏠𓏠𓏠𓏠𓏠𓏠𓏠</p>

### Table of Content
- [Awesome-ComposableAI](#awesome-composableai)
    - [Table of Content](#table-of-content)
    - [Definition](#definition)
  - [Composable-Task](#composable-task)
    - [Projects \& Papers](#projects--papers)
    - [Project Only](#project-only)
  - [Composable-Model](#composable-model)
    - [Projects \& Papers](#projects--papers-1)
  - [Composable-Gen](#composable-gen)
    - [Projects \& Papers](#projects--papers-2)
  - [Composable-Agent](#composable-agent)
    - [Paper Only](#paper-only)
  - [Composable-Product](#composable-product)
  - [Composable-X](#composable-x)

### Definition

A paramount issue in AI is the **combinational challenge**: It is infeasible to enumerate all possibilities for an intelligent system.

**Composable AI** offers a solution to this challenge by emphasizing the creation of modular, flexible, and reusable AI components. These components can be assembled and reconfigured in various ways, enabling the construction of customized AI systems that are specifically tailored to individual tasks, domains, or applications.


## Composable-Task

### Projects & Papers
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace**](https://arxiv.org/abs/2303.17580) <br> *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* <br> Preprint'23 <br><br> [[**Jarvis (Project)**](https://github.com/microsoft/JARVIS)] |  <img  src="https://github.com/microsoft/JARVIS/raw/main/assets/overview.jpg"><img> | [[Github](https://github.com/microsoft/JARVIS)] <br> [[Demo](https://huggingface.co/spaces/microsoft/HuggingGPT)] |
| [**MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**](https://arxiv.org/abs/2303.17580) <br> *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang* <br> Preprint'23 <br><br> [[**MM-REACT (Project)**](https://github.com/microsoft/JARVIS)] |  ![intro](https://camo.githubusercontent.com/08c1e7f8dd9bab6777e7f5bd9b2cb5d7a610b77c53ed0bcf3a341c9d7afa2c4d/68747470733a2f2f6d756c74696d6f64616c2d72656163742e6769746875622e696f2f696d616765732f7465617365722e706e67) | [[Github](https://github.com/microsoft/MM-REACT)] <br> [[Page](https://multimodal-react.github.io)]<br>[[Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react)] |
| [**TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs**](https://arxiv.org/abs/2303.16434) <br> *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan* Preprint'23 | ![intro](https://github.com/microsoft/visual-chatgpt/raw/main/assets/overview.png) | [[Github](https://github.com/microsoft/visual-chatgpt/tree/main/TaskMatrix.AI)] |
| [**OpenAGI: When LLM Meets Domain Experts**](https://arxiv.org/pdf/2304.04370.pdf) <br> *Yingqiang Ge, Wenyue Hua, Jianchao Ji, Juntao Tan, Shuyuan Xu, Yongfeng Zhang* <br><br> [[**OpenAGI (Project)**](https://github.com/agiresearch/OpenAGI)] | ![intro](https://github.com/agiresearch/OpenAGI/raw/main/image/pipeline.png) | [Github](https://github.com/agiresearch/OpenAGI) |
| [**ChatGPT Asks, BLIP-2 Answers: Automatic Questioning Towards Enriched Visual Descriptions**](https://arxiv.org/abs/2303.06594) <br> *Deyao Zhu, Jun Chen, Kilichbek Haydarov, Xiaoqian Shen, Wenxuan Zhang, Mohamed Elhoseiny* <br>Preprint'23<br> [[**ChatCaptioner (Project)**](https://github.com/Vision-CAIR/ChatCaptioner)] | ![intro](https://github.com/Vision-CAIR/ChatCaptioner/raw/main/ChatCaptioner/demo_pic/demo1.gif) | [Github](https://github.com/Vision-CAIR/ChatCaptioner) |
| [**Visual Programming: Compositional visual reasoning without training**](https://arxiv.org/abs/2211.11559)<br> *Tanmay Gupta, Aniruddha Kembhavi* <br>CVPR'23<br> [**Visprog (Project)**](https://github.com/allenai/visprog)| ![intro](https://github.com/allenai/visprog/raw/main/assets/teaser2.png) | [[Github](https://github.com/allenai/visprog)] <br> [[Page](https://prior.allenai.org/projects/visprog)]|
| [**ViperGPT: Visual Inference via Python Execution for Reasoning**](https://arxiv.org/abs/2303.08128)<br> *Dídac Surís, Sachit Menon, Carl Vondrick* <br>CVPR'23<br> [**Viper (Project)**](https://github.com/cvlab-columbia/viper)| ![intro](https://github.com/cvlab-columbia/viper/raw/main/teaser.gif) | [[Github](https://github.com/cvlab-columbia/viper)] <br> [[Page](https://viper.cs.columbia.edu)]|

### Project Only
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
|  [**Grounded-SAM (Project)**](https://github.com/IDEA-Research/Grounded-Segment-Anything) <br>[**Grounding DINO + Segment-Anything + X**] <br> *Shilong Liu and Zhaoyang Zeng and Tianhe Ren and Feng Li and Hao Zhang and Jie Yang and Chunyuan Li and Jianwei Yang and Hang Su and Jun Zhu and Lei Zhang*  | ![intro](https://github.com/IDEA-Research/Grounded-Segment-Anything/raw/main/assets/grounded_sam_demo3_demo4.png) | [[Github](https://github.com/IDEA-Research/Grounded-Segment-Anything)] <br> [[Demo](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/zero-shot-object-detection-with-grounding-dino.ipynb)] |
| [**Semantic-Segment-Anything (Project)**](https://github.com/fudan-zvg/Semantic-Segment-Anything)<br> [**Close-set Segmenters + Open-vocabulary Models**]<br> *Jiaqi Chen, Zeyu Yang, Li Zhang*   | ![intro](https://github.com/fudan-zvg/Semantic-Segment-Anything/raw/main/figures/sa_225172_class_name.png) | [[Github](https://github.com/fudan-zvg/Semantic-Segment-Anything)] |
| [**Segment Anything and Name It (Project)**](https://github.com/Cheems-Seminar/segment-anything-and-name-it)<br>[**Visual ChatGPT + GLIP + Segment-Anything**]<br> *Peize Sun* and *Shoufa Chen* | ![intro](https://github.com/Cheems-Seminar/segment-anything-and-name-it/raw/main/assets/teaser.png) | [[Github](https://github.com/Cheems-Seminar/segment-anything-and-name-it)]
<!-- ### Papers -->
## Composable-Model
### Projects & Papers

| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [**AdapterHub: A Framework for Adapting Transformers**]() <br> *Álvaro Barbero Jiménez* <br> EMNLP'20 <br><br> [[**adapter-transformers (Project)**](https://github.com/adapter-hub/adapter-transformers)] | <img src="https://adapterhub.ml/static/adapter-bert.png" alt="Girl in a jacket" height="300">  | [[Github](https://github.com/adapter-hub/adapter-transformers)] <br> [[Page](https://adapterhub.ml)] |
| [**Deep Model Reassembly**](https://arxiv.org/abs/2210.17409) <br> *Xingyi Yang, Daquan Zhou, Songhua Liu, Jingwen Ye, Xinchao Wang* <br> NeurIPS'22 <br><br> [[**DeRy (Project)**](https://github.com/Adamdad/DeRy)] <br>  | ![intro](https://github.com/Adamdad/DeRy/raw/main/assets/pipeline.png) | [[Github](https://github.com/Adamdad/DeRy)] <br> [[Page](https://adamdad.github.io/dery/)] |
| [**Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer**](https://arxiv.org/abs/1701.06538) <br> *Noam Shazeer, Azalia Mirhoseini, Krzysztof Maziarz, Andy Davis, Quoc Le, Geoffrey Hinton, Jeff Dean* <br> ICLR'17 <br><br> [[**mixture-of-experts (Project)**](https://github.com/davidmrau/mixture-of-experts)] <br>  | ![intro](https://camo.githubusercontent.com/cfb90532a6c580f08068d554e529a5070286d9c62d5bc055295ff5cbb19517c6/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313030302f312a4161427a67704a637953654f315544764f515f436e512e706e67) | [[Github](https://github.com/davidmrau/mixture-of-experts)] |
## Composable-Gen
### Projects & Papers

| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [**Mixture of Diffusers for scene composition and high resolution image generation**](https://arxiv.org/abs/2302.02412) <br> *Álvaro Barbero Jiménez* <br> Preprint'23 <br><br> [[**Mixture-of-Diffusers (Project)**](https://github.com/albarji/mixture-of-diffusers)] |  ![](https://user-images.githubusercontent.com/9654655/195362341-bc7766c2-f5c6-40f2-b457-59277aa11027.png) | [[Github](https://github.com/albarji/mixture-of-diffusers)] <br> [[Demo](https://huggingface.co/spaces/albarji/mixture-of-diffusers)] |
| [**Compositional Visual Generation with Composable Diffusion Models**](https://arxiv.org/abs/2206.01714) <br> *Nan Liu, Shuang Li, Yilun Du, Antonio Torralba, Joshua B. Tenenbaum* <br> ECCV'22 <br><br> [[**Composable Diffusion (Project)**](https://github.com/energy-based-model/Compositional-Visual-Generation-with-Composable-Diffusion-Models-PyTorch)] |  ![intro](assets/glide.png) | [[Github](https://github.com/energy-based-model/Compositional-Visual-Generation-with-Composable-Diffusion-Models-PyTorch)] <br> [[Demo](https://huggingface.co/spaces/Shuang59/Composable-Diffusion)] <br> [[Page](https://energy-based-model.github.io/Compositional-Visual-Generation-with-Composable-Diffusion-Models/)]|
| [**Training-Free Structured Diffusion Guidance for Compositional Text-to-Image Synthesis**](https://arxiv.org/abs/2212.05032) <br> *Weixi Feng, Xuehai He, Tsu-Jui Fu, Varun Jampani, Arjun Akula, Pradyumna Narayana, Sugato Basu, Xin Eric Wang, William Yang Wang* <br> ICLR'23 <br><br> [[**Structured-Diffusion-Guidance (Project)**](https://github.com/weixi-feng/Structured-Diffusion-Guidance)] |  ![](https://weixi-feng.github.io/structure-diffusion-guidance/img/method.jpg) | [[Github](https://github.com/weixi-feng/Structured-Diffusion-Guidance)] <br> [[Page](https://weixi-feng.github.io/structure-diffusion-guidance/)] |
| [**Reduce, Reuse, Recycle: Compositional Generation with Energy-Based Diffusion Models and MCMC**](https://arxiv.org/abs/2212.05032) <br> *Yilun Du, Conor Durkan, Robin Strudel, Joshua B. Tenenbaum, Sander Dieleman, Rob Fergus, Jascha Sohl-Dickstein, Arnaud Doucet, Will Grathwohl* <br> Preprint'23 <br><br> [[**reduce_reuse_recycle (Project)**](https://github.com/yilundu/reduce_reuse_recycle)] |  ![intro](https://user-images.githubusercontent.com/5572232/220694796-cc599abc-086f-4030-857a-59c87468fa79.gif) | [[Github](https://github.com/yilundu/reduce_reuse_recycle)] <br> [[Page](https://energy-based-model.github.io/reduce-reuse-recycle/)] |
| [**Learning to Compose Visual Relations**](https://arxiv.org/abs/2111.09297) <br> *Nan Liu, Shuang Li, Yilun Du, Joshua B. Tenenbaum, Antonio Torralba* <br> NeurIPS'21 <br><br> [[**compose-visual-relations (Project)**](https://github.com/nanlliu/compose-visual-relations)] | ![intro](assets/model.gif) | [[Github](https://github.com/nanlliu/compose-visual-relations)] <br> [[Page](https://composevisualrelations.github.io/)] |

## Composable-Agent
### Paper Only
- MCP: Learning Composable Hierarchical Control with Multiplicative Compositional Policies 
  *Xue Bin Peng, Michael Chang, Grace Zhang, Pieter Abbeel, Sergey Levine*
  NeurIPS'19 [[Paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/95192c98732387165bf8e396c0f2dad2-Paper.pdf)]
- Composable Planning with Attributes
  *Amy Zhang, Sainbayar Sukhbaatar, Adam Lerer, Arthur Szlam, Rob Fergus*
  ICML'18 [[Paper](http://proceedings.mlr.press/v80/zhang18k/zhang18k.pdf)]

## Composable-Product

| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [**langchain (Project)**](https://github.com/hwchase17/langchain)<br> [**LLM + X**] | ![intro](assets/langchain.jpg) |[Github](https://github.com/hwchase17/langchain)|


## Composable-X

TO BE UPDATE