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

# Competition rules

The competition consists of two tasks, and contestants are free to target only one or both tasks. 
The first task is training a network on CIFAR10, and the second one is training on CIFAR100.  Note that to be considered in the competition, submissions  are required to achieve at least 93% top-1 accuracy for CIFAR10 and 78% top-1 accuracy for CIFAR100. The authors can either provide a description of the method and the obtained results, or submit a 4 pages paper if they want to present their work at the workshop session as well. Note that submitting the code is mandatory for the competition, and to do so, we invite authors to submit their code as supplementary material. The three less complex methods will be awarded.

Complexity is defined by the number of parameters plus the number of operations required to compute the training process. Note that in this context, we assume that all operations are equivalent. For instance, if a given input is multiplied by a weight, then added with a bias and passed through a RELU, we consider that 3 operations have been performed.


# Awards and Prizes

Thanks to our sponsors, in addition to best paper awards we will also award a prize for the most energy-efficient hardware architecture and a prize for the fastest training method on compute clusters (details coming soon).
