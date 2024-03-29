<div class="outer__class">
<div class='skills__all'>
<div class='education'>
<h4>
Nirbhay Sharma
</h4>
<h3>
CSE'23 | IITJ | 8.97
</h3>
</div>
<div class='skills'>
</div>
</div>
<div class='projects__exp'>

</div>
</div>

<style> 

body {
    /* background-color:#CACCCE; */
}

.education {
    border:1px solid black;
    border-radius:10px;
    padding:10px;
    height:400px;

}

.outer__class {
    display:flex;
}

.skills__all {
    width:20%;
    background-color:white;
}

.projects__exp {
    width:80%;

}

.name_section {
    display:flex;
    align-items:center;
    justify-content: center;
    border:1px solid gray;
    border-radius:15px;
    padding:10px;
    width:50%;
    margin-left:auto;
    margin-right:auto;
}

h3 {
    margin-top:5px;
    color:#BD3147;
    font-size:16px;
    font-weight:500;
}

.head__title{
    display:flex;
    /* flex-direction:row; */
    justify-content:space-between;
}

*{
    /* font-family: "Verdana"; */
    font-family: "Helvetica";
    font-size:12.6px;
    margin:0px;
}

.duration{
    color:#3b5998;
    font-weight:500;
}

.name__{
    color:#BD3147;
    font-size:22px;
    font-weight:500;
}

hr{
    margin-bottom:3px;
}

a{
    color:#3b5998;
    font-weight:550;
}

/* #3b5998 44556f */
</style>

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>


<!-- <div class='head__title'> <span> <a href="https://github.com/nirbhay-design"> Github </a> </span> <span class="name__"> Nirbhay Sharma </span> <span> <a href="https://www.linkedin.com/in/nirbhay-sharma-a2b846204/"> LinkedIn </a> </span> </div>
<div class='head__title'> <span> <a href="mailto:sharma.59@iitj.ac.in"> Email </a> </span> <span style='margin-left:20px'> Uttar Pradesh, India </span> <span> 9369630713 </span> </span> </div>

<h3>Education</h3>

<div class='name_section'>
Nirbhay Sharma
</div>

---


<div class='head__title'> <span><strong>B.Tech</strong>, CSE | IIT Jodhpur </span> <span class="duration">Aug'19-May'23</span> </div>
<div> CGPA(Ongoing): <strong>8.9</strong>/10 </div>


<h3>Technical Skills</h3>

---

<div> <span><strong>Languages:</strong> </span> <span> Python, C/C++, HTML/CSS, Javascript, Haskell, Prolog</span> </div>
<div> <span><strong>Tools and Frameworks:</strong> </span> <span>Pytorch, Sklearn, Numpy, Pandas, Matplotlib, Seaborn, Flask, Django, Regex, Heroku, Git, Github, Firebase, Mongodb, Mysql</span> </div>
<div> <span><strong>Familiar with:</strong> </span> <span>Tensorflow, Java, React, Nodejs, ejs, Google Colab, OpenCV</span> </div>

<h3>Experience</h3>

---

**Split Neural Networks** | Pytorch, Python, Jetson Nano, PySyft

<div class="head__title"><span> <strong> Intern </strong> (ML Engineer) | <strong> ExaWizards </strong> India </span> <span class="duration"> Jun'22-July'22 </span> </div>

- Splitted **Mask-RCNN, FCN_Resnet50, YOLOv5** for **Instance segmentation, segmentation, face detection** tasks
- Utilized **Pysyft** and **Jetson Nano** for transferring features from one device to another
- Implemented **encoder-decoder** architecture for **tensor compression**
- Reduced **inference time** on Jetson nano device while preserving **data privacy**

<h3>Projects</h3>

---

**Noise Engineered Federated Distillation for Heterogeneous Settings** | Pytorch, FL, Python

<div class="head__title"><span><strong> Research Project</strong> | Supervisor: <strong> Dr. Deepak Mishra</strong>  | IIT Jodhpur</span> <span class="duration"> Aug'22-Present </span> </div>

- **Proposed** a **novel** Federated Learning Framework to handle **model heterogeneity** among clients
- Utilized the concept of **Data-free KD** for **knowledge transfer** from Client models to Server model 
- Solved the issue of requirement of **Generator or proxy dataset** at server end for KD
- Utilized **Gaussian Noise** samples for Distillation 
- Compared and **analyzed** our algorithm with state-of-the-art algorithms for **Model heterogeneity**
- **Outperformed** the **relevant baselines** in terms of **test accuracy** by a considerable margin

**Light Weight CNN Model for Chest Radiographs Classification** | Pytorch, Python, Torchvision, Numpy

<div class="head__title"><span><strong> Research Project</strong> | Supervisor: <strong> Dr. Angshuman Paul</strong>  | IIT Jodhpur</span> <span class="duration"> Jun'21-Mar'22 </span> </div>

- Designed a **Lightweight CNN model** for the abnormal detection of **Chest Radiographs**
- Combined the ideas from **Squeezenet** and **Mobilenet** to prepare a Light weight model
- Our Model Outperforms various light weight CNN architectures like **Squeezenet**, **Shufflenet**, **Mobilenet** on NIH dataset both on binary and multiclass classification

**Regularizing Federated Learning (FL) via Adversarial Model Perturbations (AMP)** | [Github](https://github.com/nirbhay-design/DAI_Project) | Pytorch, FL, Python

**Course Project** | Supervisor: **Dr. Richa Singh** | IIT Jodhpur

- Compared and analyzed the effect of **Adversarial Model Perturbations (AMP)** on **4** state-of-the-art Federated Learning algorithms 
- Implemented **FedAvg**, **FedProx**, **FedNTD**, **SCAFFOLD** from **scratch**
- Integrated the AMP module with aforementioned FL algorithms at client side
- Observed a boost of **2-3%** accuracy in each of the algorithm


**CNN Algorithms Comparison** | [Github](https://github.com/nirbhay-design/CNNAlgosComparison) | Pytorch, Numpy, Matplotlib, PIL, Python

**Course Project** | Supervisor: **Dr. Mayank Vatsa** | IIT Jodhpur

- Compared **7** deep **CNN** architectures on **Retinal Eye disease dataset**
- Implemented **Squeezenet**, **Mobilenet**, **Inceptionnet**, **Shufflenet**, **Googlenet**, **Resnet**, **Efficientnet** from **scratch**
- Performed a comparison study among the state-of-the-art deep CNN architectures -->

<!-- **Image Colorization** | [Github](https://github.com/nirbhay-design/dlops-project) | Pytorch, Numpy, Matplotlib, PIL, Python

**Course Project** | Supservisor: **Dr. Mayank Vatsa** | IIT Jodhpur

- Converted **grayscale image** to **colored image** using **GAN** architectures
- Implemented **pix2pix** GAN from scratch for the colorization task
- Performed colorization on **LAB** and **RGB** image format -->


<!-- 

**Mask-NoMask Detection** | [Github](https://github.com/nirbhay-design/mask-nomask-classification) | Pytorch, Numpy, PIL, Matplotlib, Python

- Detected **5300** images under masked and no masked category with an accuracy of **99.6%**
- Used transfer learning with **Mobilenet v2** for classification task
- Combined the trained model with **OpenCV** for real time classification


**PRA-Visualizer** | [Github](https://github.com/nirbhay-design/pra-visualizer) | [Url](https://pra-visualizer.web.app/) | React, Nodejs, HTML, CSS, Firebase

- Implemented a **Page replacement algorithm visualizer** which simulates various page replacement algorithms given **Frames** and **demand pages**
- Implemented **10** algorithms including **LRU**, **Working set**, **FIFO** etc. -->

<!-- --- -->

