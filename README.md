# ECE 188: Machine Learning for the Arts - Spring 2019

## FALL 2019

__NOTE:__ If you intend to enroll for Fall 2019, please fill out this quesionnare: [https://forms.gle/iHiggRiVbPUsWMm46](https://forms.gle/iHiggRiVbPUsWMm46), and enroll for the class through the EASy system. 


[Details](#details) | [Resources](#resources) | [Policies](#policies) | [Code](#code) | [Schedule](#schedule) | [Projects](#projects) | [CMU Collaboration](#cmu-collaboration) | [Accomodations](#accomodations) | [Diversity and Inclusion](#diversity-and-inclusion)

![Image](ml_art2019.png)


## Course Description

This course explores the vital new domain of Machine Learning (ML) for the arts. Though born out of computer science research, contemporary ML techniques are reimagined through creative application to diverse tasks such as style transfer, generative portraiture, music synthesis, and textual chatbots and agents. Through direct, hands-on experience with state of the art ML tools, students will develop their skills in this nascent area and form critical perspectives on the strengths and limitations of current approaches. 

As ML permeates multiple aspects of culture, industry, and scholarship, it is essential both to train the next generation of ML-literate artists and engineers, and to equip them with critical  tools to evaluate these new techniques. How do computational tools augment, complicate, or supercede human creative endeavor? What new approaches to artistic production are possible with the advent of affordable graphics hardware and ML software?

This project-based course will be conducted primarily in python using free, open-source machine learning and scientific computing toolkits, running on cloud-based educational computing resources. In addition to hands-on experience with ML techniques, students will become familiar with cloud-based workflows, jupyter notebooks, and kubernetes containers. Architectures and topics covered include Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs), LSTMs, Wavenets, Generative Adversarial Networks (GANs) and others. Students will be responsible both for technical implementation and creative value of course projects.  

**Prequisites:** ECE16, ECE143, or equivalent course on Python. **_Students need to attend the bootcamp 3/21 to enroll in the course._** 

## Details

- **Instructor:** Dr. Robert Twomey
- **Lecture:** MW 12:30-1:50pm
- **Lab:** Friday 12:30-1:50pm
- **Location:** EBU1 2315

**Bootcamp**
- Thursday 3/21/2019, 10am - 3pm, Qualcomm Conference Center, Jacobs School of Engineering
- Registration: [https://goo.gl/forms/qWWFqUFNK8nvVvSE2](https://goo.gl/forms/qWWFqUFNK8nvVvSE2)
- Bootcamp Materials: [http://github.com/roberttwomey/ml-art-bootcamp](http://github.com/roberttwomey/ml-art-bootcamp)

## Resources
* **Discussion:** we will use slack for discussion [https://ucsd-ml-art.slack.com/signup](https://ucsd-ml-art.slack.com/signup) (join with your @ucsd account)

* **Compute Resources:** We will use [datahub.ucsd.edu](http://datahub.ucsd.edu) for our in class computing environment. If you did not attend the bootcamp you need to contact me to be approved for datahub access. I will base it off of our final enrollment. 

## Policies

### Grading
* Projects - You will do four projects at 15% each. 
  * Code, Documentation, and Results must be submitted for credit.
* Final Project - 30%
  * Code, Documentation
  * Poster (poster talk)
  * Exhibition 
* Participation - 10%
  * Small assignments/tasks as they arise, graded on completion.
  * Readings.
  * Finding and sharing resources on our course discussion. 
  * Any written proposals, work-in-progress updates, check-ins, etc., I request for individual projects.

Work will be evaluated on the quality of concept, the degree of experimentation (both aesthetic and technical), and final realization (again, aesthetic and technical). I will share a rubric with the first project assignment.

### Group Work

This course will be a mix of group work and individual work depending on each assignment. I want you each to develop your own personal research interests, but also to pool your resources and talents to produce the best projects possible. 

### Project Critiques and Group Discussions

We will have critique/group discussion for each of the projects this quarter.

## Code

Code examples are here: [https://github.com/roberttwomey/ml-art-code](https://github.com/roberttwomey/ml-art-code)

### Datahub

We do our processing on datahub.ucsd.edu. Here is their instruction manual:
- quick instructions https://blink.ucsd.edu/faculty/instruction/tech-guide/dsmlp/index.html#Independent-Study,-Student-Rese
- detailed instructions https://docs.google.com/document/u/1/d/e/2PACX-1vR-tC1oL6J9RJxSP42iWr8BukgRO9ohcybFXPn95yjQQLvv4iNP5Tlbzx06rQtPA-fLex2N_MVjzgAR/pub?embedded=true#h.lyhc4mlbki3f
- making custom Docker containers to run on dsmlp https://docs.google.com/document/d/1LPfqHvk2Itm_ckafrxRVxXQdr5BSozjsv_TURQDj9x8/edit

## Schedule

### Introduction to Art and ML (Week 1)
**Day 1: Course and Syllabus** 4/1/2019
- Lecture ([pdf](https://drive.google.com/file/d/1EGI-bioemxFXJb5VfpVB5snLGBxX3fxr/view?usp=sharing))
  - Syllabus, policies, schedule
  - Projects
  - My approach
- Logistical questions?

**Homework:** Sign up for slack and post something you are interested in (a project, paper, github link) to [#shiny](https://ece188-ml-art.slack.com/messages/CHJDGRV0X).

**Day 2: Introduction to ML and the Arts** 4/3/2019
- Lecture ([pdf](https://drive.google.com/file/d/1b2xBi-2vZhW_hVo3UQJKU0MFyyoXpN9Z/view?usp=sharing))
  - Generative Systems in Art Overview
  - Survey of notable work in Art and ML

**Lab 1: Get set up in our environment** 4/5/2019
- Hands-on with datahub.ucsd.edu, jupyter
- Confirm everyone's logon works
- Work through RNN text example.
- Help? 

### Text Generation (Week 2)

**Day 3: Generative Text** 4/8/2019
- Lecture ([pdf](https://drive.google.com/file/d/1gAradJrMxGedBvziD_shmm-FUjbzd5mL/view?usp=sharing]))
  - Approaches to generative text
    - RNNs (karpathy) (character level)
  - Practical Issues
    - Where to get a textual corpus. 
    - Working with textual corpora (cleaning, parsing, etc.)
  - Outputs
    - Generative text (recipes, poetry, fiction, screenplays, etc…)
    - How to compose / harness RNN creativity?
- **Assign Project 1: Generative Text** 
  - [Generative Text Assignment](https://docs.google.com/document/d/13ueceIyuUc4ATD7B-SFZK641MycFZ57eZ9n1lQ3Y1CM/edit?usp=sharing), due 4/18/2019, 11:59pm.

**Day 4: Text part 2** 4/10/2019
- Lecture ([pdf](https://drive.google.com/open?id=18tHG3m5e0SAwmwQcijLX1uP1Kljf2yQp))
  - Case Study: GPT, GPT-2
  - Chatbots (the eliza effect)
    - seq2seq models
  - Issues
    - Sense and non-sense with ML
    - Wilful suspension of disbelief

**Lab 2: Project 1 Work Time**
- Q&A about projects.

### Time Series in ML (Week 3)

**Day 5: Autoencoders, Embeddings, Sketch-RNN** 4/15/2019
- Lecture ([pdf](https://drive.google.com/file/d/1dCcupN7yN-q3j0UqezO4k0jal60tUEXI/view?usp=sharing))
  - VAEs (MNIST VAE)
  - Latent representation, Embeddings
  - Modeling Drawings (Sketch-RNN)

**Day 6: Hands-On with VAE, Sketch-RNN** 4/17/2019
- Talk about how to submit project 1.
- In-class activities with VAE and Sketch-RNN code.
- Clone the code repository into your datahub: ```git clone https://github.com/roberttwomey/ml-art-class```
- Work through:
  - 01_mnist_vae.ipynb
  - 02_sketch_rnn.ipynb
  - Start training a sketch-rnn model on google colab
  
- **Assign Project 2: Sketching with ML**
  - [Sketching with ML Assignment](https://docs.google.com/document/d/1o_Ii4Eo3KDxq7Nw84_dLoFqes-ouDp2C--f6zMmixxk/edit?usp=sharing), due 5/2/2019, 11:59pm.

**Project 1 Due** 4/18/2019, 11:59pm.
- Submit assignment to github classroom here: [https://classroom.github.com/a/F_S6X9eN](https://classroom.github.com/a/F_S6X9eN)

**Lab 3: Project 1 discussion** 4/19/2019
- Bring printed copy of your project and abstract. 
- Discuss in small groups (20 minutes)
- Present selected projects to class (50 minutes)

### Drawing cont., Generative Audio (Week 4)

**Day 7: Handwriting** 4/22/2019
- Lecture ([pdf](https://drive.google.com/open?id=1tP3scRbhAYsCq0IIuQIYKoos1uyUd1Ml))
- Mixture Density Networks (MDNs)
- Alex Graves sequence paper, generative handwriting models

**Day 8: Generative Audio** 4/24/2019
- Lecture: History of generative music ([pdf](https://drive.google.com/file/d/1p2XcGHwQRyP8AjsHKk8JDNXHWJFkVU0y/view?usp=sharing)]
- Hands-on with contemporary music generators
  - NSynth: [blog](https://magenta.tensorflow.org/nsynth), [interactive example](https://experiments.withgoogle.com/ai/sound-maker/view/)
  - MusicVAE: [blog](https://magenta.tensorflow.org/music-vae), [interactive example](https://magenta.tensorflow.org/multitrack)
  - PerformanceRNN: [blog](https://magenta.tensorflow.org/performance-rnn), [interactive example](https://magenta.tensorflow.org/performance-rnn-browser)
  - GANSynth: [blog](https://magenta.tensorflow.org/gansynth), [interactive colab example](https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb)
  - Music Transformer: [blog](https://magenta.tensorflow.org/music-transformer)


**Lab 3: Project 2 Work** 4/26/2019

### Audio Continued (Week 5)

**Day 9: Generative Networks for Music** 4/29/2019
- Check in on any last minute questions for Project 2
- Hands on with ML Music:
  - In small groups, work through these examples from the code repository (divide, conquer, and share!): [https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb](https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb)
  - Covering:
    - sequence generation
    - seeding sequences
    - sequence interpolation
    - direct sound synthesis
    - sound latent-space interpolation.
  
**Day 10: class cancelled** 5/1/2019

sick day


- **Assign Project 3:** Generative Audio. [Project writeup](https://docs.google.com/document/d/17ZUUWZr7jIhGKwxe_Rj8DlAA6yyrd2YRls66fZOuQK0/edit?usp=sharing)


**Project 2 Due:** 5/2/2019, 11:59pm. Submit online to github classroom: [https://classroom.github.com/a/gP_-KCrL](https://classroom.github.com/a/gP_-KCrL)

**Lab 4: Project 2 Discussion** 5/3/2019

### Audio, then Visual Processing (Week 6)

**Day 11: Speech Generation** 5/6/2019
- Lecture ([pdf](https://drive.google.com/file/d/16QJAIrvSbBC20vO0Ej-cYgS4l06qOrG9/view?usp=sharing))
  - Text to Speech 
  - Vocoders, Unit Selection
  - Art with Speech Synthesis
  - ML(Tacotron, WaveGlow)
- **Assign Project 3:** Generative Audio. [Project prompt](https://docs.google.com/document/d/17ZUUWZr7jIhGKwxe_Rj8DlAA6yyrd2YRls66fZOuQK0/edit?usp=sharing). Due Thursday 5/16, 11:59pm.

**Day 12: Visual Processing** 5/8/2019

- Lecture: CNNs and Neural Style ([pdf](https://drive.google.com/open?id=1xkmIjQVpJuwycVysKX71TMZ6iToADQ5B))
  - CNNs vs other NNs. 
    - LeNet
    - VGG16, VGG19
  - A Neural Algorithm of Style.
  - Neural Style Transfer
- Hands on activities: [https://github.com/roberttwomey/ml-art-code/tree/master/week6_cnn
](https://github.com/roberttwomey/ml-art-code/tree/master/week6_cnn
)

### Visual Continued (Week 7)

**Day 13: Work Day** 5/13/2019
- Work day on project 3

**Day 14: Style Transfer, Continued** 5/15/2019
- Lecture: [pdf](https://drive.google.com/open?id=1nbHklxFSKjIdz6EUnS3KU776mUmnAi3x)
  - Fast Style Transfer
  - Arbitrary Style Transfer
  - Deep Photo Stylization
  - Popular applications
- In class activities: [https://github.com/roberttwomey/ml-art-code/tree/master/week7_style](https://github.com/roberttwomey/ml-art-code/tree/master/week7_style)
  - Fast Style, Arbitrary Style, Deep Photo Style

**Project 3 Due:** 5/16/2019 at 11:59pm. 

Submit online to github classroom: [https://classroom.github.com/a/JPtQMEm9](https://classroom.github.com/a/JPtQMEm9)

- Critique on Friday from 12:30-1:30. 


### Visual Continued (Week 8)

**Day 15: Deep Dream and Gradient Ascent** 5/20/2019
- Lecture: ([pdf](https://drive.google.com/open?id=14G2kUW3HR-gIbhGhRwmCCKskwcMg3011))
- Neural Doodle [https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/Neural_Doodle_keras](https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/Neural_Doodle_keras)
- Deep Dream [https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/deepdream](https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/deepdream)
  - Gradient Ascent, maximal activation/excitation

**Assign Project 4: Generative Visual**

**Day 16: GANs** 5/22/2019
- Lecture: ([pdf](https://drive.google.com/open?id=1qfMY1_mwNUEihcAkB_iIAilbwW6Z3hGf))
- StyleGAN, BigGAN, CycleGAN, DCGAN on code repository: [https://github.com/roberttwomey/ml-art-code/tree/master/week8](https://github.com/roberttwomey/ml-art-code/tree/master/week8)
  - Ian Goodfellow tutorial on GANs, NeurIPS 2016 [https://www.youtube.com/watch?v=RvgYvHyT15E](https://www.youtube.com/watch?v=RvgYvHyT15E)
  
### Visual (Week 9)

**Day 17: MEMORIAL DAY** 5/27/2019

No class!

**Day 18: Recognition** 5/29/2019
- Image Recognition
- Semantic Segmentation
- Captioning (MS-COCO)
- Faces: recognition, pose estimation, 3d reconstruction (deepfakes)
- Pixel RNN

**Project 4 due** 5/30/2019

### Final Project Development (Week 10)

**Lecture: Alternate Platforms**
- TPUs
- Embedded systems (NVIDIA jetson nano, Google Coral, others)
- Tools (DNNWeaver)

### Final Presentations / Exhibition (Finals Week)

**Final Work due for Exhibition**

## Projects

### Project 1: Generative Text

[Generative Text Assignment](https://docs.google.com/document/d/13ueceIyuUc4ATD7B-SFZK641MycFZ57eZ9n1lQ3Y1CM/edit?usp=sharing), due 4/18/2019, 11:59pm.

Submit online to github classroom: [https://classroom.github.com/a/F_S6X9eN](https://classroom.github.com/a/F_S6X9eN)

### Project 2: Sketching with ML

[Sketching with ML Assignment](https://docs.google.com/document/d/1o_Ii4Eo3KDxq7Nw84_dLoFqes-ouDp2C--f6zMmixxk/edit?usp=sharing), due 5/2/2019, 11:59pm.

Submit online to github classroom: [https://classroom.github.com/a/gP_-KCrL](https://classroom.github.com/a/gP_-KCrL)

### Project 3: Generative Audio

[Generative Audio Assignment](https://docs.google.com/document/d/17ZUUWZr7jIhGKwxe_Rj8DlAA6yyrd2YRls66fZOuQK0/edit?usp=sharing), due 5/16/2019, 11:59pm. 

Submit online to github classroom: [https://classroom.github.com/a/JPtQMEm9](https://classroom.github.com/a/JPtQMEm9)

### Project 4: Generative Visual

Due 5/30/2019, 11:59pm. Open ended.

Submit online to github classroom: [https://classroom.github.com/g/tngoWMjM](https://classroom.github.com/g/tngoWMjM)

### Final Project: Revisit One Project for Exhibit

Refine and enhance one of your earlier projects for the final exhibit during Finals Week.

## CMU Collaboration

We will have a couple of opportunities to interact with a similar class running this Spring at Carnegie Mellon University, as well as making a joint, online, public-facing exhibition for excellent student work (opt-in). More info coming soon!

## Accomodations
The Office for Students with Disabilities (OSD), an Academic Affairs department, is responsible for the review of medical documentation and the determination of reasonable accommodations based on a disability. Authorization for Accommodation (AFA) letters are issued by the OSD and given to undergraduate, graduate, and Professional School students directly. If you have an AFA letter, meet with the CSE Student Affairs representative, and schedule an appointment with your instructor by the end of Week 2 to ensure that reasonable accommodations for the quarter can be arranged.

## Diversity and Inclusion
We are committed to fostering a learning environment for this course that supports a diversity of thoughts, perspectives and experiences, and respects your identities (including race, ethnicity, heritage, gender, sex, class, sexuality, religion, ability, age, educational background, etc.). Our goal is to create a diverse and inclusive learning environment where all students feel comfortable and can thrive.

Our instructional staff will make a concerted effort to be welcoming and inclusive to the wide diversity of students in this course. If there is a way we can make you feel more included please let one of the course staff know, either in person, via email/discussion board, or even in a note under the door. Our learning about diverse perspectives and identities is an ongoing process, and we welcome your perspectives and input.

We also expect that you, as a student in this course, will honor and respect your classmates, abiding by the UCSD Principles of Community [https://ucsd.edu/about/principles.html](https://ucsd.edu/about/principles.html). Please understand that others’ backgrounds, perspectives and experiences may be different than your own, and help us to build an environment where everyone is respected and feels comfortable.If you experience any sort of harassment or discrimination, please contact the instructor as soon as possible. If you prefer to speak with someone outside of the course, please contact the Office of Prevention of Harassment and Discrimination: [https://ophd.ucsd.edu/](https://ophd.ucsd.edu/)
