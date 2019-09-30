# NOTE: FALL 2019
If you intend to enroll for Fall 2019, please fill out this questionnare: [https://forms.gle/iHiggRiVbPUsWMm46](https://forms.gle/iHiggRiVbPUsWMm46), and enroll for the class through the [EASy system](https://academicaffairs.ucsd.edu/Modules/Students/PreAuth/). 

# ECE 188: Machine Learning for the Arts - Fall 2019

[Resources](#resources) | [Policies](#policies) | [Schedule](#schedule) | [Projects](#projects) | [Accomodations](#accomodations) | [Diversity and Inclusion](#diversity-and-inclusion)

![Image](ml_art2019.png)


## Course Description

This course explores the vital new domain of Machine Learning (ML) for the arts. Though born out of computer science research, contemporary ML techniques are reimagined through creative application to diverse tasks such as style transfer, generative portraiture, music synthesis, and textual chatbots and agents. Through direct, hands-on experience with state of the art ML tools, students will develop their skills in this nascent area and form critical perspectives on the strengths and limitations of current approaches. 

As ML permeates multiple aspects of culture, industry, and scholarship, it is essential both to train the next generation of ML-literate artists and engineers, and to equip them with critical  tools to evaluate these new techniques. How do computational tools augment, complicate, or supercede human creative endeavor? What new approaches to artistic production are possible with the advent of affordable graphics hardware and ML software?

This project-based course will be conducted primarily in python using free, open-source machine learning and scientific computing toolkits, running on cloud-based educational computing resources. In addition to hands-on experience with ML techniques, students will become familiar with cloud-based workflows, jupyter notebooks, and kubernetes containers. Architectures and topics covered include Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs), LSTMs, Wavenets, Generative Adversarial Networks (GANs) and others. Students will be responsible both for technical implementation and creative value of course projects.  

**Prequisites:** ECE16, ECE143, or equivalent course on Python.

## Details

- **Instructor:** Dr. Robert Twomey
- **Lecture:** MW 9:30-11:00pm
- **Lab:** MW 11:00-12:30pm
- **Location:** EBU1 2315

# Resources
* **Discussion:** we will use slack for discussion [https://join.slack.com/t/ucsd-ml-art/signup](https://join.slack.com/t/ucsd-ml-art/signup) (join with your @ucsd.edu or @eng.ucsd.edu account)

* **Compute Resources:** We will use [datahub.ucsd.edu](http://datahub.ucsd.edu) for our in class computing environment. If you did not attend the bootcamp you need to contact me to be approved for datahub access. I will base it off of our final enrollment.

* **Code:** code examples are here: [https://github.com/roberttwomey/ml-art-code](https://github.com/roberttwomey/ml-art-code)

* **Canvas:** this is where I will post your grades: [https://canvas.ucsd.edu/courses/5343](https://canvas.ucsd.edu/courses/5343)

* **Github Classroom:** this is where you will submit your code: [https://classroom.github.com/classrooms/49459697-ece188-fa2019](https://classroom.github.com/classrooms/49459697-ece188-fa2019)

# Policies

## Grading
* Projects - You will do three projects at 20% each. 
  * Code, Documentation, and Results must be submitted for credit.
* Final Project - 30%
  * Code, Documentation
  * Poster (poster talk)
  * Exhibition 
* Participation - 10%
  * Finding and sharing resources on our course discussion. 
  * Small assignments/tasks as they arise, graded on completion.
  * Readings.
  * Any written proposals, work-in-progress updates, check-ins, etc., I request for individual projects.

Work will be evaluated on the quality of concept, the degree of experimentation (both aesthetic and technical), and final realization (again, aesthetic and technical). I will share a rubric with the first project assignment.

## Group Work

This course will be a mix of group work and individual work depending on each assignment. I want you each to develop your own personal research interests, but also to pool your resources and talents to produce the best projects possible. **Group work is encouraged, but not required.**

## Project Critiques and Group Discussions

We will have critique/group discussion for each of the projects this quarter.

# Schedule

## Introduction to Art and ML (Week 1)
**Day 1: Course and Syllabus** 9/29
- Lecture: ([pdf](https://drive.google.com/open?id=1_RhMhnznkVwYLGB0ZzACeH5U0yR4hOgg))
  - Syllabus, policies, schedule
  - Projects
  - My approach
- Lab:
  - Enrollment questions?
  - Sign up for slack [https://join.slack.com/t/ucsd-ml-art/signup](https://join.slack.com/t/ucsd-ml-art/signup)
  - Log onto datahub
  - File->Clone repository `git clone `

**Homework:** Post something you are interested in (a project, paper, github link) to [#shiny](https://ucsd-ml-art.slack.com/messages/CHJDGRV0X).

**Day 2: Introduction to ML and the Arts** 10/2
- Lecture ([pdf]())
  - Generative Systems in Art Overview
  - Survey of notable work in Art and ML

**Lab 1: Get set up in our environment** 
- Hands-on with datahub.ucsd.edu, jupyter
- Confirm everyone's logon works
- Work through RNN text example.
- Help? 

## Text Generation (Week 2)

**Day 3: Generative Text** 10/7
- Lecture ([pdf]())
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

**Day 4: Text part 2** 10/9
- Lecture ([pdf]())
  - Case Study: GPT, GPT-2
  - Chatbots (the eliza effect)
    - seq2seq models
  - Issues
    - Sense and non-sense with ML
    - Wilful suspension of disbelief

**Lab 2: Project 1 Work Time**
- Q&A about projects.

## Time Series in ML (Week 3)

**Day 5: Autoencoders, Embeddings, Sketch-RNN** 10/14
- Lecture ([pdf]())
  - VAEs (MNIST VAE)
  - Latent representation, Embeddings
  - Modeling Drawings (Sketch-RNN)

**Day 6: Hands-On with VAE, Sketch-RNN** 10/16
- Talk about how to submit project 1.
- In-class activities with VAE and Sketch-RNN code.
- Clone the code repository into your datahub: ```git clone https://github.com/roberttwomey/ml-art-class```
- Work through:
  - 01_mnist_vae.ipynb
  - 02_sketch_rnn.ipynb
  - Start training a sketch-rnn model on google colab

**Assign Project 2:** Generative Audio. See [#projects](#projects)
- Due 11/10, 11:59pm. Submit online to github classroom.


## Drawing cont., Generative Audio (Week 4)

**Project 1 Due** 10/20 11:59pm

- Submit assignment to github classroom here: [https://classroom.github.com/a/F_S6X9eN](https://classroom.github.com/a/F_S6X9eN)

**Day 7: Project 1 discussion** 10/21
- Bring printed copy of your project and abstract. 
- Discuss in small groups (20 minutes)
- Present selected projects to class (50 minutes)

**Day 8: Handwriting** 10/23
- Lecture ([pdf]())
- Mixture Density Networks (MDNs)
- Alex Graves sequence paper, generative handwriting models

## Audio Continued (Week 5)

**Day 9: Generative Audio** 10/28
- Lecture: History of generative music ([pdf]()]
- Hands-on with contemporary music generators
  - NSynth: [blog](https://magenta.tensorflow.org/nsynth), [interactive example](https://experiments.withgoogle.com/ai/sound-maker/view/)
  - MusicVAE: [blog](https://magenta.tensorflow.org/music-vae), [interactive example](https://magenta.tensorflow.org/multitrack)
  - PerformanceRNN: [blog](https://magenta.tensorflow.org/performance-rnn), [interactive example](https://magenta.tensorflow.org/performance-rnn-browser)
  - GANSynth: [blog](https://magenta.tensorflow.org/gansynth), [interactive colab example](https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb)
  - Music Transformer: [blog](https://magenta.tensorflow.org/music-transformer)

- Lab: Project 2 Work

**Day 10: Generative Networks for Music** 10/30
- Check in on any last minute questions for Project 2
- Hands on with ML Music:
  - In small groups, work through these examples from the code repository (divide, conquer, and share!): [https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb](https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb)
  - Covering:
    - sequence generation
    - seeding sequences
    - sequence interpolation
    - direct sound synthesis
    - sound latent-space interpolation.
  
## Audio, then Visual Processing (Week 6)

**Day 11: Speech Generation** 11/4
- Lecture ([pdf]())
  - Text to Speech 
  - Vocoders, Unit Selection
  - Art with Speech Synthesis
  - ML(Tacotron, WaveGlow)

**Day 12: Visual Processing** 11/6

- Lecture: CNNs and Neural Style ([pdf]())
  - CNNs vs other NNs. 
    - LeNet
    - VGG16, VGG19
  - A Neural Algorithm of Style.
  - Neural Style Transfer
- Lab: [https://github.com/roberttwomey/ml-art-code/tree/master/week6_cnn
](https://github.com/roberttwomey/ml-art-code/tree/master/week6_cnn
)

**Assign Project 4: Generative Visual**

## Visual Continued (Week 7)

**Day 13: **VETERANS DAY NO CLASS** 11/11

**Project 2 Due:** 11/12, 11:59pm, through github classroom.

**Day 14: Critique: Project 2** 11/13


## Visual Continued (Week 8)

**Day 15: Style Transfer, Continued** 11/18
- Lecture: [pdf]()
  - Fast Style Transfer
  - Arbitrary Style Transfer
  - Deep Photo Stylization
  - Popular applications
- Lab: 
  - [https://github.com/roberttwomey/ml-art-code/tree/master/week7_style](https://github.com/roberttwomey/ml-art-code/tree/master/week7_style)
  - Fast Style, Arbitrary Style, Deep Photo Style

**Day 16: Deep Dream and Gradient Ascent** 11/20
- Lecture: ([pdf]())
- Neural Doodle [https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/Neural_Doodle_keras](https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/Neural_Doodle_keras)
- Deep Dream [https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/deepdream](https://datahub.ucsd.edu/user/rtwomey/tree/ml-art-code/week8/deepdream)
  - Gradient Ascent, maximal activation/excitation

** GANs and Perceptive ML (Week 9)

**Day 17: GANs** 11/25
- Lecture: ([pdf]())
- StyleGAN, BigGAN, CycleGAN, DCGAN, Pix2Pix on code repository: [https://github.com/roberttwomey/ml-art-code/tree/master/week8](https://github.com/roberttwomey/ml-art-code/tree/master/week8)
  - Ian Goodfellow tutorial on GANs, NeurIPS 2016 [https://www.youtube.com/watch?v=RvgYvHyT15E](https://www.youtube.com/watch?v=RvgYvHyT15E)
- Art using GANs
## Visual (Week 9)

**Day 18: Recognition** 11/27
- Lecture: ([pdf]())
- Image Captioning with Visual Attention (MS-COCO)
  - https://colab.research.google.com/drive/1sGC26H7zIZEWrMdI-LN7cIWsF0Ak9tx9
- Semantic Segmentation
- Art using Segmentation and Captioning
- Project 3 Work Time 

## Final Project Development (Week 10)

**Project 3 due:** 12/1, 11:59pm.

**Day 19: Project 3 Critique** 12/2

**Day 20: Platforms** 12/4
- Lecture ([pdf]())
  - What is Datahub?
  - Embedded systems (NVIDIA jetson nano, Google Coral, TPUs, others)
  - Tools (DNNWeaver)  
- Final Projects
  - Project repository as usual through github classroom: [https://classroom.github.com/g/pEWp059E](https://classroom.github.com/g/pEWp059E)
  - An extended project report (4 pages): [google docs](https://docs.google.com/document/d/133H59WZBmH6MlAgFSskFLMQITeIC5d9b2iuzsOfa4E8/edit?usp=sharing)
  - By wednesday: accept the classroom assignment, fill in your abstract/proposal. Check in with me on Wednesday during class.
- Inspiration for final projects (from your peers at CMU)
  - CMU ArtML Spring 19 Finals: http://kangeunsu.com/artml19s/gallery.html  
- Individual meetings regarding final project.

## Final Presentations / Exhibition (Finals Week)

**FINAL TIME:** Wednesday December 11, 8-11am. Location TBD.
- PROJECT DUE: 8am, Wednesday December 11. 
- REPORT DUE: 11:59pm, Friday December 13 (add to your github repository as pdf)

# Projects

## Project 1: Generative Text

[Generative Text Assignment](https://docs.google.com/document/d/17FX0Vt3ur9QVmhnq4n4JJ0dmqBJuKIKGrslLoAkDpeM/export?format=pdf). Due 10/20/2019, 11:59pm.

Submit online to github classroom: []()

## Project 2: Generative Audio

[Generative Audio Assignment](). Due 11/12/2019, 11:59pm. 

Submit online to github classroom: []()

## Project 3: Generative Visual

[Generative Visual Assignment](). Due 12/1/2019, 11:59pm. Open ended.

Submit online to github classroom: []()

## Final Project: Revisit One Project for Exhibit

Refine, enhance, extend one of your earlier projects for the showcase during Finals Week. 

PROJECT DUE 12/11, 8-11am. Location TBD.

REPORT DUE 12/13, 11:59pm. Add the pdf to your github, please.

For the final project you will need to submit two things: 
- Project repository as usual through github classroom: []()
- An extended project report (4 pages): [google docs]()

# Addenda

## CMU Collaboration

We will have a couple of opportunities to interact with a similar class running this Spring at Carnegie Mellon University, as well as making a joint, online, public-facing exhibition for excellent student work (opt-in). More info coming soon!

## Datahub Info

We do our processing on datahub.ucsd.edu. Here is their instruction manual:
- quick instructions [https://blink.ucsd.edu/faculty/instruction/tech-guide/dsmlp/index.html#Independent-Study,-Student-Rese](https://blink.ucsd.edu/faculty/instruction/tech-guide/dsmlp/index.html#Independent-Study,-Student-Rese)
- detailed instructions [https://docs.google.com/document/u/1/d/e/2PACX-1vR-tC1oL6J9RJxSP42iWr8BukgRO9ohcybFXPn95yjQQLvv4iNP5Tlbzx06rQtPA-fLex2N_MVjzgAR/pub?embedded=true#h.lyhc4mlbki3f](https://docs.google.com/document/u/1/d/e/2PACX-1vR-tC1oL6J9RJxSP42iWr8BukgRO9ohcybFXPn95yjQQLvv4iNP5Tlbzx06rQtPA-fLex2N_MVjzgAR/pub?embedded=true#h.lyhc4mlbki3f)
- making custom Docker containers to run on dsmlp [https://docs.google.com/document/d/1LPfqHvk2Itm_ckafrxRVxXQdr5BSozjsv_TURQDj9x8/edit](https://docs.google.com/document/d/1LPfqHvk2Itm_ckafrxRVxXQdr5BSozjsv_TURQDj9x8/edit)

## Accomodations
The Office for Students with Disabilities (OSD), an Academic Affairs department, is responsible for the review of medical documentation and the determination of reasonable accommodations based on a disability. Authorization for Accommodation (AFA) letters are issued by the OSD and given to undergraduate, graduate, and Professional School students directly. If you have an AFA letter, meet with the CSE Student Affairs representative, and schedule an appointment with your instructor by the end of Week 2 to ensure that reasonable accommodations for the quarter can be arranged.

## Diversity and Inclusion
We are committed to fostering a learning environment for this course that supports a diversity of thoughts, perspectives and experiences, and respects your identities (including race, ethnicity, heritage, gender, sex, class, sexuality, religion, ability, age, educational background, etc.). Our goal is to create a diverse and inclusive learning environment where all students feel comfortable and can thrive.

Our instructional staff will make a concerted effort to be welcoming and inclusive to the wide diversity of students in this course. If there is a way we can make you feel more included please let one of the course staff know, either in person, via email/discussion board, or even in a note under the door. Our learning about diverse perspectives and identities is an ongoing process, and we welcome your perspectives and input.

We also expect that you, as a student in this course, will honor and respect your classmates, abiding by the UCSD Principles of Community [https://ucsd.edu/about/principles.html](https://ucsd.edu/about/principles.html). Please understand that others’ backgrounds, perspectives and experiences may be different than your own, and help us to build an environment where everyone is respected and feels comfortable.If you experience any sort of harassment or discrimination, please contact the instructor as soon as possible. If you prefer to speak with someone outside of the course, please contact the Office of Prevention of Harassment and Discrimination: [https://ophd.ucsd.edu/](https://ophd.ucsd.edu/)
