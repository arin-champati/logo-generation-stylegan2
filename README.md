# StyleGan2 Logo Generation Tool
A project by Arin Champati: champati@princeton.edu and Brendan Houle: bhoule@princeton.edu

Welcome to our Spring 2021 Junior Paper for Princeton University!

There are many difficulties associated with logo design, including client to designer communication, creative roadblocks, and plagarism / copyright laws. To solve some of these problems, we created a tool that allows users to generate and control features of logos that do not exist.

We used StyleGAN2 to train on two different datasets - one of logos with text and one of logos without text. We then interpreted the latent space of each model through supervised and unsupervised methods and implemented other helpful features, such as projection of existing logos (using with a novel loss function).

I, Arin Champati, specifically focused on creating the model and features for logos without text, which included learning the latent space directions for red, green, blue, brightness, complexity, symmetry, rigidity, background fill, and size. I additionally implemented a new loss function to use for projection, which outperformed previous methods by both improving similarity and representation in the latent space. In this repository, you can find my paper and a notebook with some of the code that was written for this project. 

Click on the Colab link below to give our tool a try!

https://colab.research.google.com/github/bnhoule/stylegan2-logo-tool/blob/main/FinalTool.ipynb

Positive      Negative
![Alt text](example_images/fill_positive.png?raw=true)
![Alt text](example_images/fill_negative.png?raw=true)
