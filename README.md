<h1 align="center"> Abstract generation of scientific publications using HuggingFace </h1>

<p align="center"> 
  <img src="doc/huggingface icon.png" alt="HuggingFace and NLP">
</p>


<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project"> ➤ About The Project</a></li>
    <li><a href="#documentation"> ➤ Documentation</a></li>
    <li><a href="#build-with"> ➤ Build With</a></li>
    <li><a href="#project-files-description"> ➤ Project Files Description</a></li>
    <li><a href="#getting-started"> ➤ Getting Started</a></li>
    <li><a href="#showcase"> ➤ Showcase</a></li>
    <li><a href="#contribution"> ➤ Contribution</a></li>
    <li><a href="#support"> ➤ Support </a></li>
    <li><a href="#license"> ➤ License </a></li>
    <li><a href="#credits"> ➤ Credits </a></li>
  </ol>
</details>


![-----------------------------------------------------](doc/rgb.png)


<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :pencil: About The Project</h2>

<p align="justify"> 
  Summarizing has always been an important utility for reading long documents. Research papers are unique in this regard, as they have a compulsory summary in the form of the abstract in the beginning of the document which gives the gist of the entire study often within a set upper limit for the word count. Writing the abstract to be sufficiently succinct while being descriptive enough is a hard task even for native English speakers. This study is the first step in generating abstracts for research papers in the mechanical and materials domain automatically.  
</p>

<p align="justify">
  Many journal and book publishers have AI-assisted abstract generation tools that they offer as a service. However, they mostly do a good job for science, medical and other domains. The state-of-the-art reveals that there is currently no good abstract writing tool for mechanical and other core engineering domains. The objetive of this project is to bridge this gap.
</p>


![-----------------------------------------------------](doc/rgb.png)


<!-- Documentation -->
<h2 id="documentation"> :bookmark: Documentation</h2>

Refer the following documents for better understanding of the dimensions of project.


<ul>
    <li><a href="INSERT LINK" target="_blank">High Level Documentation (HLD)</a></li>
    <li><a href="INSERT LINK" target="_blank">Low Level Documentation (LLD)</a></li>
    <li><a href="INSERT LINK" target="_blank">Architecture (ADD)</a></li>
    <li><a href="INSERT LINK" target="_blank">Detailed Project Report (DPR)</a></li>
    <li><a href="INSERT LINK" target="_blank">Wireframe</a></li>

</ul>


![-----------------------------------------------------](doc/rgb.png)


<!-- OVERVIEW -->
<h2 id="overview"> :cloud: Overview</h2>
<p align="justify"> 
  Text summarization is one of the main domains in Natural Language Processing (NLP) which has numerous use cases. There are two broad categories for this: extraction and abstraction. In extractive methods it uses existing words, phrases or sentences to form a summary. In contrast, abstractive methods follow a more complex mechanisms. First, a semanatic
representation of the content is built. Then natural language generation mechanisms are used to create the summary using the aforementioned representation. This research proposes a hybrid mechanism of text summarization to generate the abstract scientific papers with evaluating several paths for the proposed solution.
</p>

<p align="justify">
  The objective of this research is to reduce the burden on researchers by automatically generating the abstract section by using the sections of the paper that follows it. The researchers then may do minor adjustments to the generated section and publish, leading to lesser publication times.
</p>


![-----------------------------------------------------](doc/rgb.png)


<!-- BUILD WITH -->
<h2 id="build-with"> :hammer: Build With</h2>

<a href="https://www.python.org" target="_blank">
    <img align="left" src="doc/Python.png" alt="Python" height ="42px"/>
</a>

<a href="https://jupyter.org/" target="_blank">
    <img align="left" src="doc/jupyter icon.png" alt="Jupyter" height="42px"/> 
</a>

<a href="https://aws.amazon.com/sagemaker/" target="_blank">
    <img align="left" src="doc/aws sagemaker.png" alt="sagemaker" height="42px"/>
</a>

 <a href="https://git-scm.com/" target="_blank">
    <img align="left" src="doc/github icon.png" alt="git" height='42px'/>
</a>

<a href="https://streamlit.io/" target="_blank">
    <img align="left" src="doc/streamlit icon.jpg" alt="streamlit" height='42px'/>
</a>


![-----------------------------------------------------](doc/rgb.png)


<!-- PROJECT FILES DESCRIPTION -->
<h2 id="project-files-description"> :floppy_disk: Project Files Description</h2>

- **src folder** - The source code folder! However, in languages that use headers (or if you have a framework for your application) don’t put those files in here.
- **test folder** - Unit tests, integration tests… go here.
- **.config Folder** - It should contain local configuration related to setup on local machine.
- **.build Folder** - This folder should contain all scripts related to build process (PowerShell, Docker compose…).
- **dep folder** - This is the directory where all your dependencies should be stored.
- **res folder** - For all static resources in your project. For example, images.
- **samples folder** - Providing “Hello World” & Co code that supports the documentation.
- **templates** - Templates of flask app
  

![-----------------------------------------------------](doc/rgb.png)


<!-- GETTING STARTED -->
<h2 id="getting-started"> :pushpin: Getting Started</h2>

This is how you can set up your project locally. To get a local copy up and running follow these simple steps.

1. Clone the repo
<pre><code>$ git clone https://github.com/AbhijeetSrivastav/Jet-Engine-RUL-Prediction.git</code></pre>

2. Create conda environment
<pre><code>$ conda create -n jet-rul</code></pre>

3. Activate the conda environment
<pre><code>$ conda activate jet-rul </code></pre>

4. Install requirements to conda environment
<pre><code>$ pip install -r requirements.txt</code></pre>

5. Navigate to project directory
<pre><code>$ cd "Project Directory"</code></pre>

6. Run flask app to get access to pipelines UI
<pre><code>$ python app.py </code></pre>


**Note:-** After step 5 make sure to create your MongoDB database and dump the base dataset `rul.csv` in it using `data_dump.py` script after updating MongoDb client in it and also don't forget to create `.env` file and mention your MongoDb credential within it which are accessed by the `config.py` in `rul` package to run the pipelines. 


![-----------------------------------------------------](doc/rgb.png)


<!-- Showcase -->
<h2 id="showcase"> :camera: Showcase</h2>

<center>
  <table>
    <tr>
      <td><img width="600" alt="Show 1" src="assets\show (8).png"></td>
      <td><img width="600" alt="show 2" src="assets\show (9).png"></td>
    </tr>
    <tr>
      <td><img width="600" alt="show 3" src="assets\show (10).png"></td>
      <td><img width="600" alt="show 4" src="assets\show (11).png"></td>
    </tr>
    <tr>
      <td><img width="600" alt="show 5" src="assets\show (12).png"></td>
      <td><img width="600" alt="show 6" src="assets\show (13).png"></td>
    </tr>
    <tr>
      <td><img width="600" alt="show 7" src="assets\show (14).png"></td>
      <td><img width="600" alt="show 8" src="assets\show (15).png"></td>
    </tr>
  </table>
</center>


<a href="https://drive.google.com/file/d/14HazGAvVN9XcPZuk_mXXZ9oR06NvWi5I/view?usp=sharing" target="_blank"><b>Demo Video</b></a>


![-----------------------------------------------------](doc/rgb.png)


<!-- Contribution -->
<h2 id="contribution"> :paperclip: Contribution</h2>

The Machine Learning Guide Project is a open source project. I a committed to a fully transparent development process and highly appreciate any contributions. Whether you are helping me fixing bugs, proposing new feature, improving our documentation or spreading the word - we would love to have you as part of this project.

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b main/feature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature`)
5. Open a Pull Request


![-----------------------------------------------------](doc/rgb.png)


<!-- Support -->
<h2 id="support"> :sparkling_heart: Support</h2>

I open-source almost everything I can, and I try to reply to everyone needing help using these projects. Obviously,
this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are few ways you can do it :-

- Giving proper credit when you using this project, linking back to it :D
- Starring and sharing the project :rocket:
  
Thanks! :heart:


![-----------------------------------------------------](doc/rgb.png)


<!-- License -->
<h2 id="license"> :book: License</h2>


```text
Apache License 
Copyright (c) 2022 Arnab Kundu
 
  "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License........
```
[Apache License](https://github.com/Arnab-Hell/Text-Summarisation-with-HuggingFace/blob/main/LICENSE)

![-----------------------------------------------------](doc/rgb.png)


<!-- Credits -->
<h2 id="credits"> :scroll: Credits</h2>

Arnab Kundu

- [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Arnab-Hell)

- [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/akundu91/)



![-----------------------------------------------------](assets/rgb.png)

