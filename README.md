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
- **Office Hours:** Friday 10am-noon, Atkinson 1611

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
  - Clone repository: **New->Terminal**:
    - `git clone https://github.com/roberttwomey/ml-art-code/`

**Homework:** Post something you are interested in (a project, paper, github link) to [#shiny](https://ucsd-ml-art.slack.com/messages/CHJDGRV0X).

**Day 2: Introduction to ML and the Arts** 10/2
- Lecture ([pdf](https://drive.google.com/open?id=17jwUvIypWtmXWn7B6dOS9Yq5GcHVbrtc))
  - Generative Systems in Art Overview
  - Survey of notable work in Art and ML
  - NN Basics

**Lab 1: Make sure you can log in** 
- Hands-on with datahub.ucsd.edu, jupyter
- Confirm everyone's logon works for datahub.ucsd.edu.
- Help? 

**Homework:** Read Andrej Karpathy's _The Unreasonable Effectiveness of RNNs_ (2015) [http://karpathy.github.io/2015/05/21/rnn-effectiveness/](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

## Text Generation (Week 2)

**Day 3: Generative Text** 10/7
- Lecture ([pdf](https://drive.google.com/open?id=1LIfsYbEd8JDvDXDirf_SU6Kk2tQPiLnM))
  - Approaches to generative text
    - RNNs (karpathy) (character level)
    - LSTM/GRU
  - Practical Issues
    - Where to get a textual corpus. 
    - Working with textual corpora (cleaning, parsing, etc.)
  - Outputs
    - Generative text (recipes, poetry, fiction, screenplays, etc…)
    - How to compose / harness RNN creativity?
- **Assign Project 1: Generative Text** 
  - [Generative Text Assignment](https://docs.google.com/document/d/17FX0Vt3ur9QVmhnq4n4JJ0dmqBJuKIKGrslLoAkDpeM/export?format=pdf). Due 10/20/2019, 11:59pm.
  - Examples of student projects from last quarter.
  - Questions?

**Day 4: Text part 2** 10/9
- Lecture ([pdf](https://drive.google.com/open?id=1yzy1bKY7Nf_wHvL6sxyMu9Vi0fX1fCZu))
  - Transformers and Attention 
  - Fine-tuning
  - Case Study: GPT, GPT-2

**Lab 2: GPT-2 Examples**

**Homework: Project proposal**
- Please clone the project1 repository from github classroom, and edit the abstract to be a description of your proposed project.

## Time Series in ML (Week 3)

**Day 5: Chatbots** 10/14
- Lecture ([pdf](https://drive.google.com/open?id=1qjeE2ZlX-0XVfThCwBPoCgpFb1rsdm2v))
  - Chatbots (the eliza effect)
  - Issues
   - Sense and non-sense with ML.
   - Wilful suspension of disbelief
   - Projective psychology
   - Learning?
   
**Lab: Chatbots**
- Hands on with chatbots:
  - ELIZA: [https://www.masswerk.at/elizabot/](https://www.masswerk.at/elizabot/)
  - Alicebot Alysse: [http://demo.vhost.pandorabots.com/pandora/talk?botid=829713883e34f760](http://demo.vhost.pandorabots.com/pandora/talk?botid=829713883e34f760)
  - Cleverbot: [https://www.cleverbot.com/](https://www.cleverbot.com/)
  - Hugging Face chatbot demo: [https://convai.huggingface.co/](https://www.cleverbot.com/)
- Check in regarding project1 idea

**Day 6: Autoencoders, Embeddings, Sketch-RNN** 10/16
Autoencoders, Embeddings, Sketch-RNN
- Lecture ([pdf](https://drive.google.com/open?id=1TaidNOomzcQ3zK8asDr6U6i_didF8kp9))
  - VAEs (MNIST VAE)
  - Latent representation, Embeddings
  - Modeling Drawings (Sketch-RNN)
- Talk about how to submit project 1.

**Lab: Autoencoders and online Sketch-RNN demos**
- Work through:
  - week3/Autoencoders.ipynb
  - Sketch-RNN interactive demos.
  
**Homework: Project 1**
- Reminder Project 1 is due Sunday night at midnight (10/20), we will spend Monday's class critiquing (in class discussion)
- __Bring a printed copy of your project!__

## Generative Audio (Week 4)

**Project 1 Due** 10/20 11:59pm

- Submit assignment to github classroom. Use the github classroom below: [Project 1](#project-1-generative-text)

**Day 7: Project 1 discussion** 10/21
- Bring printed copy of your project and abstract. 
- Discuss in small groups (20 minutes)
- Present selected projects to class (50 minutes)

**Day 8: Intro to Generative Audio** 10/23
- Lecture: History of generative music ([pdf](https://drive.google.com/open?id=1SfyC-SuYydrUaLC6b_8rosExbc3beamP)]
- Lab: Hands-on with contemporary music generators
  - NSynth: [blog](https://magenta.tensorflow.org/nsynth), [interactive example](https://experiments.withgoogle.com/ai/sound-maker/view/)
  - MusicVAE: [blog](https://magenta.tensorflow.org/music-vae), [interactive example](https://magenta.tensorflow.org/multitrack)
  - PerformanceRNN: [blog](https://magenta.tensorflow.org/performance-rnn), [interactive example](https://magenta.tensorflow.org/performance-rnn-browser)
  - GANSynth: [blog](https://magenta.tensorflow.org/gansynth), [interactive colab example](https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb)
  - Music Transformer: [blog](https://magenta.tensorflow.org/music-transformer)

## Audio Continued (Week 5)

**Day 9: Generative Networks for Music** 10/28
- Lecture: Contemporary Musicians using AI ([pdf](https://drive.google.com/open?id=1QdkvtpchKBNwihGf-ZhHf6heQSD5fuG-))
- Examples of Project 2 from last quarter. 
- Hands on with ML Music:
  - In small groups, work through these examples from the code repository (divide, conquer, and share!): [https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb](https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb)
  - Covering:
    - sequence generation
    - seeding sequences
    - sequence interpolation
    - direct sound synthesis
    - sound latent-space interpolation.
  
**Day 10: Speech Generation** 10/30
- Lecture ([pdf](https://drive.google.com/open?id=11SIAljfUtgI6ZK3rMQMxbD-7ADl0ahea))
  - Text to Speech 
  - Vocoders, Unit Selection
  - Art with Speech Synthesis
  - ML(Tacotron, WaveGlow, DeepVoice, DeepSpeech)
  
 **Lab: Hands-On with ML Speech**

_Synthesis_:

DeepVoice
  - [DeepVoice3: Single-speaker text-to-speech demo](https://colab.research.google.com/github/r9y9/Colaboratory/blob/master/DeepVoice3_single_speaker_TTS_en_demo.ipynb)
  - [DeepVoice3: Multi-speaker text-to-speech demo](https://colab.research.google.com/github/r9y9/Colaboratory/blob/master/DeepVoice3_multi_speaker_TTS_en_demo.ipynb)
- [Tacotron2/WaveGlow](https://colab.research.google.com/github/pytorch/pytorch.github.io/blob/master/assets/hub/nvidia_deeplearningexamples_waveglow.ipynb)

_Recognition:_

- [DeepSpeech](https://github.com/roberttwomey/ml-art-code/blob/master/week5/mozilla_deepspeech.ipynb) on datahub

**Homework: Project proposal**
- Please clone the project2 repository from github classroom, and edit the abstract to be a description of your proposed project.
  - I will discuss these individually with you during lab on Monday

## Visual Processing (Week 6)

**Day 11: Visual Processing** 11/4
- Lecture: CNNs ([pdf](https://drive.google.com/open?id=1wKY75xocKcn8Bb5HY3mpFpO1q6NLzVd5))
  - CNNs vs other NNs. 
    - LeNet
    - VGG16, VGG19

**Lab:** 
- Week 6 LeNet CNN, VGG19 Classification, Neural Style: [https://github.com/roberttwomey/ml-art-code/tree/master/week6
](https://github.com/roberttwomey/ml-art-code/tree/master/week6)
- Individual meetings about Project 2 ideas.

**Day 12: Style Transfer** 11/6
- Lecture: Style Transfer ([pdf](https://drive.google.com/open?id=1qFNlYUB8ze5KEf3-iyIN_VJQMF0vkDB6))
  - Neural Style Transfer
  - Fast Style Transfer
  - Arbitrary Style Transfer
  - Deep Photo Stylization
  - Popular applications

**Lab:**
- [https://github.com/roberttwomey/ml-art-code/tree/master/week6](https://github.com/roberttwomey/ml-art-code/tree/master/week6)
  - Fast Style, Arbitrary Style, Deep Photo Style
  
## Visual Continued (Week 7)

**Day 13: VETERANS DAY NO CLASS** 11/11

**Project 2 Due:** 11/12, 11:59pm, through github classroom.

**Day 14: Critique: Project 2** 11/13

## Visual Continued (Week 8)

**Day 15: Deep Dream and Gradient Ascent** 11/18
- Lecture: ([pdf](https://drive.google.com/open?id=1lrQGY3Nu1WuqiGfXfMNdhUztvn_IguR9))
  - Neural Doodle [https://github.com/roberttwomey/ml-art-code/tree/master/week8/Neural_Doodle_keras](https://github.com/roberttwomey/ml-art-code/tree/master/week8/Neural_Doodle_keras)
  - Deep Dream [https://github.com/roberttwomey/ml-art-code/tree/master/week8/deepdream](https://github.com/roberttwomey/ml-art-code/tree/master/week8/deepdream)
  - Gradient Ascent, maximal activation/excitation
  - GauGAN using [SPADE](https://github.com/NVlabs/SPADE)

**Lab:**
- Hands on with Deep Dream.

**Assign Project 3: Generative Visual**

**Day 16: GANs** 11/20
- Lecture: ([pdf](https://drive.google.com/open?id=1ikd8HH6VQITmJX2_vVdwVRwmAVXC--QH))
  - StyleGAN, BigGAN, CycleGAN, DCGAN, Pix2Pix on code repository: [https://github.com/roberttwomey/ml-art-code/tree/master/week8](https://github.com/roberttwomey/ml-art-code/tree/master/week8)
  - Ian Goodfellow tutorial on GANs, NeurIPS 2016 [https://www.youtube.com/watch?v=RvgYvHyT15E](https://www.youtube.com/watch?v=RvgYvHyT15E)
  - Art using GANs

**Lab:**
- BigGAN Latent Exploration
- StyleGAN Exploration
- Latent Math

**Homework: Project 3 proposal**
- For MONDAY: Please clone the project3 repository from github classroom, and edit the abstract to be a description of your proposed project.


## Visual (Week 9)

**Day 17: Image Captioning and Segmentation** 11/25
- Lecture: ([pdf](https://drive.google.com/open?id=1fyqdat0MlkbuNjgWtncWjkVBwnchEl__))
- Image Captioning with Visual Attention (MS-COCO)
  - https://colab.research.google.com/drive/1sGC26H7zIZEWrMdI-LN7cIWsF0Ak9tx9
- Semantic Segmentation
- Art using Segmentation and Captioning

**Lab**
- Review Project 3 proposals individually.

**Day 18: Platforms** 11/27
- Lecture: ([pdf](https://drive.google.com/open?id=1e1cq7NQSY5-bzwocT8V9ZxDjwP3tIEzK))
  - What is Datahub?
  - Embedded systems (NVIDIA jetson nano, Google Coral, TPUs, others)
  - Tools (DNNWeaver)  

## Final Project Development (Week 10)

**Project 3 due:** 12/1, 11:59pm.

**Day 19: Project 3 Critique** 12/2

**Homework**
- Final Projects
  - Project repository as usual through github classroom: []()
  - An extended project report (4 pages): [google docs](https://docs.google.com/document/d/133H59WZBmH6MlAgFSskFLMQITeIC5d9b2iuzsOfa4E8/edit?usp=sharing)
  - By wednesday: accept the classroom assignment, fill in your abstract/proposal. Check in with me on Wednesday during class.
- Inspiration for final projects (from your peers at CMU)
  - CMU ArtML Spring 19 Finals: http://kangeunsu.com/artml19s/gallery.html  
- Individual meetings regarding final project.


**Day 20: Creativity Metric Activity, Final Project Check-in** 12/4
- No Lecture
- Discuss Final Project Ideas
- In class Assessing Computational Creativity activity
  - In small groups (2 ppl), work with [this spreadsheet](https://docs.google.com/spreadsheets/d/1RVQS78aAa5CBBkG7tXRpURzETUh3lZbDeLWsOrUSkwg/edit?usp=sharing): 

## Final Presentations / Exhibition (Finals Week)

**FINAL TIME:** Wednesday December 11, 8-11am. Location TBD.
- PROJECT DUE: 8am, Wednesday December 11. 
- REPORT DUE: 11:59pm, Friday December 13 (add to your github repository as pdf)

# Projects

## Project 1: Generative Text

[Generative Text Assignment](https://docs.google.com/document/d/17FX0Vt3ur9QVmhnq4n4JJ0dmqBJuKIKGrslLoAkDpeM/export?format=pdf). Due 10/20/2019, 11:59pm.

Submit online to github classroom: [https://classroom.github.com/g/sJIzmAcR](https://classroom.github.com/g/sJIzmAcR)

## Project 2: Generative Audio

[Generative Audio Assignment](https://docs.google.com/document/d/1E82WjOp3p1bXCeR43iGgG39zHPr8u-6_kYFB9RXyhFY/export?format=pdf). Due 11/12/2019, 11:59pm. 

Submit online to github classroom: [https://classroom.github.com/g/ujfzX5Wp](https://classroom.github.com/g/ujfzX5Wp)

## Project 3: Generative Visual

[Generative Visual Assignment](https://docs.google.com/document/d/1RMeJF1oppSgedvhJGjB8CgGXlytR6KaXK8gMJTGJji0/export?format=pdf). Due 12/1/2019, 11:59pm.

Submit online to github classroom: [https://classroom.github.com/g/AMOrRaOj](https://classroom.github.com/g/AMOrRaOj)

## Final Project: Revisit One Project for Showcase

Refine, enhance, extend one of your earlier projects for the showcase during Finals Week. 

PROJECT DUE 12/11, 8-11am. Location TBD.

REPORT DUE 12/13, 11:59pm. Add the pdf to your github, please.

For the final project you will need to submit two things: 
- Project repository as usual through github classroom: [
https://classroom.github.com/g/lGEIfW-a
](
https://classroom.github.com/g/lGEIfW-a
)
- An extended project report (4 pages): see google doc link in repository

# Addenda

## Enrollment Fall 2019
If you intend to enroll for Fall 2019, please fill out this questionnare: [https://forms.gle/iHiggRiVbPUsWMm46](https://forms.gle/iHiggRiVbPUsWMm46), and enroll for the class through the [EASy system](https://academicaffairs.ucsd.edu/Modules/Students/PreAuth/). 

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
