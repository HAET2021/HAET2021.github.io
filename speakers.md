
# Speakers

- [Warren Gross](#warren-gross)
- [Julie Grollier](#julie-grollier)
- [Song Han](#song-han)
- [Ehsan Saboori](#ehsan-saboori)
- [Yunhe Wang](#yunhe-wang)
- [Liangwei Ge](#liangwei-ge)

## Warren Gross

| <img src="/speakers_pictures/warren.jpg" alt="Warren Gross" height="250px" /> |
| **Stochastic Computing for Machine Learning towards an Intelligent Edge** |
| Deep learning offers the promise of intelligent devices that are able to perceive, reason and take intuitive actions. The rising adoption of deep learning techniques has motivated the search for low-cost and high-speed software and hardware solutions for deployment on smart edge devices. In recent years work has focused on reducing the complexity of inference in deep neural networks, however, a method enabling low-complexity on-chip learning is still missing. In this talk we explore the promise of a hardware implementation technique called stochastic computing, which represents values in an algorithm as streams of randomly chosen bits. We show how stochastic computing can be used as a binary or ternary compression technique for both inference and training of deep neural networks. We also show how stochastic computing can implement invertible logic circuits that perform learning without backpropagation. |

| **Affiliation** | [University of Mcgill](https://www.mcgill.ca/ece/warren-gross) |
| **Biography** | Warren J. Gross received the B.A.Sc. degree in Electrical Engineering from the University of Waterloo, Waterloo, ON, Canada, in 1996, and the M.A.Sc. and Ph.D. degrees from the University of Toronto, Toronto, ON, Canada, in 1999 and 2003, respectively. He is currently a Professor, the Louis Ho Faculty Scholar in Technological Innovation,  and the Chair of the Department of Electrical and Computer Engineering, McGill University, Montreal, QC, Canada. His research interests are in the design and implementation of signal processing systems and custom computer architectures. Dr. Gross served as the Chair for the IEEE Signal Processing Society Technical Committee on Design and Implementation of Signal Processing Systems. He served as the General Co-Chair for the IEEE GlobalSIP 2017 and the IEEE SiPS 2017 and the Technical Program Co-Chair for SiPS 2012. He served as an Associate Editor for the IEEE TRANSACTIONS ON SIGNAL PROCESSING and as a Senior Area Editor. He is a Licensed Professional Engineer in the Province of Ontario. | 


## Julie Grollier

| <img src="/speakers_pictures/julie.jpg" alt="Julie Grollier" height="250px" /> |
| **Spiking Equilibrium Propagation for Autonomously Learning Hardware** |
| Current hardware such as CPUs/GPUs is not adapted for efficient training of deep networks: orders of magnitude in speed and energy efficiency are lost due to relentless data transfers between memory and processing. A solution to this issue is to build chips where physical components embodying neurons and synapses are organized in deep networks. Memristor nanodevices are nanoscale resistors whose tunable conductance can mimic and memorize a synaptic weight in-situ. Deep network chips combining transistor-based neurons with memristor-based synapses have been developed but they are only capable of inference. Indeed, backpropagation requires heavy additional circuitry and memories to compute, store and write gradients in memristors. To solve this problem, we have developed a spiking version of equilibrium propagation and designed it to run on circuits with hardware LIF neurons that locally update the memristor conductances through their voltage spikes. Our simulations of the system give a test accuracy on MNIST within 2\% of BPTT. They also show that the system is resilient to imperfections and fast: with GHz oscillators, inference can be achieved in nanoseconds and training in tens of milliseconds. We have thus designed an ultrafast hardware Spiking Neural Network where learning is entirely autonomous and local, with state-of-the-art accuracy. Our work opens the path to novel hardware chips for embedded AI. |

| **Affiliation** | [CNRS, Thales](http://julie.grollier.free.fr) |
| **Biography** | Julie Grollier is researcher director in the CNRS/Thales lab in France, where she is leading the “Nanodevices for Neuromorphic Computing” team. Julie has over 100 publications, and is a frequent invited speaker in international conferences. She is a Fellow of the American Physical Society. In 2010 she was awarded the Jacques Herbrand prize of the French Academy of Science. 2018 she received the Silver Medal of CNRS in Physics for her pioneering work on spintronics and brain-inspired computing. | 

## Song Han

| <img src="/speakers_pictures/song.jpeg" alt="Song Han" height="250px" /> |
| **AutoML for TinyML with Once-for-All Network** |
| Last June, researchers released a startling report estimating that the amount of power required for neural architecture search involves the emissions of roughly 626,000 pounds of carbon dioxide. That’s equivalent to nearly five times the lifetime emissions of the average U.S. car, including its manufacturing. This issue gets even more severe in the model deployment phase, where deep neural networks need to be deployed on diverse hardware platforms, including resource-constrained edge devices. I will present a new NAS system for searching and running neural networks efficiently, the once-for-all network (OFA). By decoupling model training and architecture search, OFA can reduce the pounds of carbon emissions involved in neural architecture search by thousands of times. OFA can produce a surprisingly large number of sub-networks ($> 10^{19}$) that can fit different hardware platforms and latency constraints. By exploiting weight sharing and progressive shrinking, the produced model consistently outperforms state-of-the-art NAS methods including MobileNet-v3 and EfficientNet (up to 4.0\% ImageNet top1 accuracy improvement over MobileNetV3, or same accuracy but 1.5x faster than MobileNetV3, 2.6x faster than EfficientNet). In particular, OFA achieves a new SOTA 80.0\% ImageNet top-1 accuracy under the mobile setting ($<600M MACs$). OFA is the winning solution for the 3rd and 4th Low Power Computer Vision Challenge (LPCVC). |

| **Affiliation** | [MIT EECS](https://songhan.mit.edu) |
| **Biography** | Song Han is an assistant professor at MIT EECS. Dr.~Han received the Ph.D. degree in Electrical Engineering from Stanford advised by Prof.~Bill Dally. Dr.~Han’s research focuses on efficient deep learning computing. He proposed “Deep Compression” that can compress neural networks by an order of magnitude, and the hardware implementation “Efficient Inference Engine” that brings compressed weights and sparsity into deep learning accelerators. His work received the best paper award in ICLR’16 and FPGA’17; He is the recipient of 35 Innovators Under 35 (TR35) and NSF CAREER Award. The pruning, compression and acceleration techniques have been integrated into many AI chip products in industry. His hobbies include biking, snowboarding, drum sets, and design.|



## Ehsan Saboori

| <img src="/speakers_pictures/ehsan.jpg" alt="Ehsan Saboori" height="250px" /> |
| **Deep learning model compression using neural network design space exploration** |
| The emergence of deep neural networks (DNNs) in recent years has enabled ground-breaking   abilities   and   applications   for   modern   intelligent   systems. Concurrently, the increasing complexity and sophistication of DNNs is predicated on significant power consumption, model size and computing resources. These factors have been found to limit deep learning’s performance in real-time applications, in large-scale systems, and on low-power devices. Application developers, software engineers and algorithm architects must now create intelligent solution that deal with strict latency, power and  computation  constraints across an  increasingly diverse set of hardware backends. Deeplite researches and develops novel multi-objective optimization methods aimed towards automated software solutions for neural network design space exploration and network compression that is ideal for various target hardware platforms. Increasingly, the need for end to end, holistic optimization solutions that include training and  inference  considerations, with a particular focus on promising solutions that are user-friendly, intuitive, and enable the practical use of neural networks. We will discuss how recent progress in neural network   design   space   exploration   can   benefit   both   algorithm   developers   and hardware designers alike to reduce the complexity in designing resource-efficient deep learning that consumes less power and fewer barriers to adoption. |

| **Affiliation** | [Deeplite](https://www.deeplite.ai/) |
| **Biography** | Ehsan Saboori is a passionate tech entrepreneur and technologist. He obtained his BSc   in   artificial   intelligence   and   completed   his   PhD   in   computer   science   at Concordia university in 2016. He has been a member of ACM and IEEE associations and published several peer-reviewed conferences and journal papers. With several years of experience working in different companies such as Microsoft, SAP and Morgan Stanley he cofounded Deeplite where he assessed emerging challenges for deep learning and formed the technology vision that became the core of Deeplite. |




## Yunhe Wang

| <img src="/speakers_pictures/yunhe.jpg" alt="Yunhe Wang" height="250px" /> |
| **AdderNet: Do we really need multiplications in deep learning?** |
| Compared with cheap addition operation, multiplication operation is of much higher computation complexity. We present adder networks (AdderNets) to trade these massive multiplications in deep neural networks, especially convolutional neural networks (CNNs), for much cheaper additions to reduce computation costs. In AdderNets, we take the $\ell_1$ norm distance between filters and input feature as the output response. We develop a special back-propagation approach for AdderNets by investigating the full-precision gradient. We then propose an adaptive learning rate strategy to enhance the training procedure of AdderNets according to the magnitude of each neuron's gradient. Moreover, we develop a series of optimization approaches (e.g. knowledge distillation) for enhancing the resulting performance. As a result, the proposed AdderNet can achieve 93.3\% Top-5 accuracy using ResNet-50 on the ImageNet dataset, which is slightly higher than that of the baseline ResNet-50 using multiplications. |

| **Affiliation** | [Huawei Noah’s Ark Lab](https://www.wangyunhe.site/) |
| **Biography** | Dr. Yunhe Wang is currently a senior researcher at Huawei Noah’s Ark Lab. He received the Ph.D. degree from Peking University, China. His research interests lie in deep learning algorithms and related applications in computer vision. He has published over 40 papers in prestigious journals and top tier conferences, including IEEE T-PAMI, IEEE T-NNLS, IEEE T-IP, ICML, NIPS, CVPR, ICCV, IJCAI and AAAI. He regularly severed as the (senior) PC member for many conferences, e.g. NIPS, ICML, CVPR, ICCV, IJCAI and AAAI. |


## Liangwei Ge

| <img src="/speakers_pictures/luke.jpeg" alt="Liangwei Ge" height="250px" /> |
| **Intel AI Technical Solution** |
| The presentation will provide a comprehensive summary of the various technologies, solutions, and best practices that Intel provides to the industry for tacking some of the challenges of training DNN models. It covers the full AI stack, from underlying hardware to libraries, frameworks, and SDKs at three different levels: cluster-level, node-level, and instruction-level. |

| **Affiliation** | [Intel]() |
| **Biography** | Liangwei Ge is an artificial intelligence (AI) Technical Solution Specialist (TSS) within Intel. His particular focus is on AI workload optimizations, like distributed training across a cluster, processing of large, high-resolution, 3D images, and inferencing at the data center and edge devices. He obtained his PhD in Electronics Design Automation (EDA), Waseda Univ., Japan. |
