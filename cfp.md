# Important Dates

- Paper submission deadline: 26 February 2021.
- Acceptance notification: 26 March 2021.
- Workshop: 8 May 2021.

# Author Instructions

The authors have to follow the instructions listed below when submitting thier contributions:

- Use the ICLR LaTeX [template](https://github.com/ICLR/Master-Template/raw/master/archive/iclr2021.zip) to prepare the manuscript.
- Papers should not be longer than 4 pages, including figures and tables, and excluding references.
- Do not report author names since the review is double blind.
- Papers that have been accepted in the main ICLR conference cannot be submitted to the workshop.  
- Manuscripts should be submitted using the [CMT](https://cmt3.research.microsoft.com/HAET2021) system. 

# Scope and Topics

The workshop welcomes contributions that seek to reduce the cost of the training process based on high-level complexity metrics (number of operations, memory usage) or by taking into account the details of the computing hardware (CPU, GPU, IPU, NPU, or any other custom accelerator implemented as an ASIC or on FPGA). Topics of interest include (but are not limited to):

- compression methods to reduce memory usage and/or complexity of deep learning during training,
- hardware architectures and implementations for deep learning training,
- energy reduction techniques for deep learning training,
- open-source designs, implementations and code related to efficient deep-learning implementations,
- energy models or energy-efficiency benchmarks for deep learning training implementations,
- applications of low-energy deep learning training,
- equilibrium-propagation-based techniques and/or their hardware implementations,
- few-shot/few-labels and semi-supervised learning methods for training on chip. 

# Competition Rules

The competition consists of two steps. An open step where contestants can train and test their methods on a public dataset such as CIFAR10/CIFAR100, and an evaluation step where we will test proposed methods on a nonpublic dataset. Contestants should propose a lite training solution that accelerates the training process while reaching a good accuracy. The evaluation will be performed on a 10 classes nonpublic dataset composed of 32 by 32 RGB 500 training images and 100 testing images per class (it is not CIFAR10 or CIFAR100). Contestants are invited to use CIFAR10/CIFAR100 to test their methods. We provide a [code](https://github.com/eghouti/HAET-2021-competition-baseline-code) that contains a dataloader, training and test program and a script that stops training after 10 minutes and performs the test.

To evaluate different submissions, we run each code on an Nvidia V100 using a nonpublic dataset during 10 minutes, and then use the training model to classify test dataset. Methods will be classed according to the accuracy they achieve after 10 minutes training. To explain their methods, the authors can either provide a description of the method and the obtained results, or submit a 4 pages paper if they want to present their work at the workshop session as well. Note that submitting the code is mandatory for the competition, and to do so, we invite authors to submit their code as supplementary material. The three best methods will be awarded. Note that the deadline for the competition is the same as paper submission on 26 February 2021. 
 


# Awards and Prizes

Thanks to our sponsors, in addition to best paper awards we will also award a prize for the most energy-efficient hardware architecture and a prize for the fastest training method on compute clusters (details coming soon).
