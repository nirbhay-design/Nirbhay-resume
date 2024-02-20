<!-- <div class='head__title'> <span> <a href="https://github.com/nirbhay-design"> Github </a> </span> <span class="name__"> Nirbhay Sharma </span> <span> <a href="https://www.linkedin.com/in/nirbhay-sharma-a2b846204/"> LinkedIn </a> </span> </div>
<div class='head__title'> <span> <a href="mailto:sharma.59@iitj.ac.in"> Email </a> </span> <span> 9369630713 </span> <span> <a href='https://nirbhay-sharma.vercel.app'> Portfolio</a> </span> </span> </div> -->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div>
<span class="name__"> Nirbhay Sharma </span> | <span> +91 9369630713 </span> | <span> <a href="mailto:sharma.59@iitj.ac.in"> <i class="fa fa-envelope" style='font-size:12px;'></i> sharma.59@iitj.ac.in </a> </span> | <span> <a href="https://github.com/nirbhay-design"> <i class="fa fa-github"></i> Github </a> </span> | <span> <a href='https://nirbhay-sharma.vercel.app'> <i class="fa fa-address-book-o"></i> Portfolio </a> </span> |  <span> <a href="https://www.linkedin.com/in/nirbhay-sharma-a2b846204/"> <i class="fa fa-linkedin-square"></i> LinkedIn </a> </span> 
</div>

<!-- <div class='head__title'> <span> <h3 style='display:inline;'>Education -</h3> <strong>B.Tech</strong>, CSE | Indian Institute of Technology (IIT) Jodhpur | CGPA: <strong>8.97</strong>/10 </span> <span class="duration">Aug'19-May'23</span> </div> -->

<h3> Education </h3>

---

<div class='head__title'> <span> <strong>B.Tech</strong>, CSE | Indian Institute of Technology (IIT) Jodhpur | CGPA: <strong>8.97</strong>/10 </span> <span class="duration">Aug'19-May'23</span> </div>


<h3>Technical Skills</h3>

---

<div> <span><strong>Languages:</strong> </span> <span> Python, C/C++, HTML/CSS, Javascript, Haskell, Prolog</span> </div>
<div> <span><strong>Tools and Frameworks:</strong> </span> <span>Pytorch, Django, Flask, Docker, AWS Lambda, Regex, Heroku, Git, Github, Firebase, MySql</span> </div>
<!-- <div> <span><strong>Familiar with:</strong> </span> <span>Tensorflow, Java, React, Nodejs, ejs, Google Colab, OpenCV</span> </div> -->

<h3>Publications</h3>

---

***Nirbhay Sharma***, *Gautam Kumar*, *Dr. Angshuman Paul*, "**An Extremely Lightweight CNN Model For the Diagnosis of Chest Radiographs in Resource-constrained Environments**". "International Journal of Medical Physics" 2023 | <a href="https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.16722"> Paper </a>

<h3>Research / Industry Experience</h3>

---

<div class="head__title"><span>  <strong> Faaya Astu </strong> India | <strong> Full Time </strong> (ML Engineer) | Pytorch, Diffusion, ControlNet, LoRA </span> <span class="duration"> Jun'23-Present </span> </div>

- Worked on **SOTA Stable Diffusion**, **ControlNet** and **LoRA** models for text to print, and content generation  
<!-- - Trained **GALIP**, a **GAN** based model for **Text to Print generation** on **AWS** instance on custom dataset -->
- Trained **Stable Diffusion ControlNet** architecture on **Lineart** and **Colorbox** control on **VastAI** GPU instance to provide more flexibility and control on print generation
- Trained **Low Rank Adaptation (LoRA)** models in **Kohya_SS** for controlled background and face generation 
- Containerized **Stable Diffusion WebUI** and **ControlNet** using **Docker** and deployed them as **Serverless Endpoints** on **RunPod** for **inference**
- Exposed the serverless endpoint APIs to **AWS Lambda** and used **AWS API Gateway** to create **APIs for APP**

<div class="head__title"><span> <strong> ExaWizards </strong> India | <strong> Intern </strong> (ML Engineer) | <strong> Split Neural Networks </strong> | Pytorch, Jetson Nano, PySyft </span> <span class="duration"> Jun'22-July'22 </span> </div>

- Splitted **Mask-RCNN, FCN_Resnet50, YOLOv5** for **Instance segmentation, segmentation, face detection** tasks
- Used **Pysyft** for latent feature transfer from **Jetson Nano** edge device to GPU server
- Implemented **Encoder-Decoder** architecture with **MSE Loss** for efficient **image compression to latent space**
- Reduced considerable **inference time** using **split learning** and **latent image compression**  

**Noise Engineered Federated Distillation for Heterogeneous Settings** | Pytorch, Federated Learning, Data-Free KD

<div class="head__title"><span><strong> Research Project</strong> | Supervisor: <strong> Dr. Deepak Mishra</strong>  | IIT Jodhpur</span> <span class="duration"> Aug'22-May'23 </span> </div>

- **Proposed** a **novel** Federated Learning (FL) Framework to handle **model and data heterogeneity**
- Implemented **data-free KD** using **Gaussian Noise** at the **Server**, eliminating need of **proxy dataset** or **GAN's**
- Compared our algorithm with SOTA FL algorithms for **model heterogeneity** like **FedDF**, **FedMD**, **Kt-pfl**
- **Outperformed** all **baselines** in terms of **test accuracy** by a considerable margin on multiple datasets 

**Light Weight CNN Model for Chest Radiographs Classification** | Pytorch, Light Weight CNN Models

<div class="head__title"><span><strong> Research Project</strong> | Supervisor: <strong> Dr. Angshuman Paul</strong>  | IIT Jodhpur | <a href="https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.16722"> Paper </a></span> <span class="duration"> Jun'21-Mar'22 </span> </div>

- Designed a **Lightweight CNN model (ExLNet)** for the abnormal detection of **Chest Radiographs**
- Fused the concepts from **Squeezenet** and **Mobilenet** into a single architecture to make it **lightweight**
- **ExLNet** outperforms SOTA models like **MobileNet**, **ShuffleNet** on various medical datasets like **NIH**, **VINBIG**

<h3>Projects</h3>

---

**Image Captioning using Detection Transformer (DeTR)** | [Github](https://github.com/nirbhay-design/image-caption-detr) | Pytorch, DeTR, Transformer

- Implemented **DeTR** from **scratch** using **Pytorch** and modified it for **image captioning** task
- Trained **DeTR** on **Flickr30k** dataset for **500** epochs and evaluated on test dataset using **BLEU** score
- Achieved a **BLEU** score of **57.36** on **Flickr8k** dataset

**Regularizing Federated Learning (FL) via Adversarial Model Perturbations (AMP)** | [Github](https://github.com/nirbhay-design/DAI_Project) | [Report](https://github.com/nirbhay-design/DAI_Project/blob/main/B19EE031_B19CSE114_project_report.pdf) | Pytorch, FL

<!-- **Course Project** | Supervisor: **Dr. Richa Singh** | IIT Jodhpur -->

- Analyzed the effect of **Adversarial Model Perturbations (AMP)** on **4** SOTA Federated Learning (FL) algorithms 
- Implemented **FedAvg**, **FedProx**, **FedNTD**, **SCAFFOLD** from **scratch** and integrated **AMP** module at the **client**
- Observed a boost of **2-3%** accuracy on CIFAR10/100 dataset after integrating AMP in each of the algorithm 

<!-- **CNN Algorithms Comparison** | [Github](https://github.com/nirbhay-design/CNNAlgosComparison) | [Report](https://github.com/nirbhay-design/CNNAlgosComparison/blob/master/Dl_Project_Report.pdf) | Pytorch, Numpy, Matplotlib, PIL, Python

- Compared **7** deep **CNN** architectures on **Retinal Eye disease dataset**
- Implemented **Squeezenet**, **Mobilenet**, **Inceptionnet**, **Shufflenet**, **Googlenet**, **Resnet**, **Efficientnet** from **scratch**
- Performed a comparison study among the state-of-the-art deep CNN architectures -->

<style> 

@import url('https://fonts.googleapis.com/css2?family=Arvo&family=Lato&family=Lora&family=Open+Sans&family=Jost&display=swap');


table, th, td {
  border: 0.1px solid black;
  border-collapse: collapse;
}

h3 {
    margin-top:5px;
    color:#BD3147;
    font-size:16px;
    font-weight:650;
}

.head__title{
    display:flex;
    justify-content:space-between;
}

*{
    font-family: "Open Sans";
    font-size:13px;
    margin:0px;
}

.duration{
    color:#3b5998;
    font-weight:500;
}

.name__{
    color:#BD3147;
    font-size:22px;
    font-weight:650;
}

hr{
    margin-bottom:3px;
}

a{
    color:#3b5998;
    font-weight:600;
}

/* #3b5998 44556f */
</style>

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>