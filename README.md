# Deep Learning: Technology and Applications(Spring 2021)
Deep Learning is regarded as a panacea in the era of big data.
In this course, you will learn the foundations of deep learning, understand how to interprete others' neural networks, and learn how to build your own neural networks.
You will also learn about popular neural network structures including Convolutional neural networks, RNNs, LSTM, and transformers.

## Course Information
- This course meets for in-class lecture Fri 9:10AM - 12:00AM (Seminar room No.2 at KISTI KIUM).
- For all inquiries related to this course, please contact bart7449 AT gmail DOT com
### Instructor
- Kyong-Ha Lee 
### Time and Location
- Fri. 9:10 AM ~ 12:00PM
## Materials
- Book: <a href="https://link.springer.com/book/10.1007/978-3-319-94463-0">Neural networks and deep learning: a textbook</a> by Charu C. Aggarwal(but not mandatory)
- All slides for this class will be available here. 
- Some papers in a reading list will be reviewed and presented by students  
## Logistics
- All course announcements take place though this page. Please check this page frequently.
### Class components and grading
- This course has the following components:
  - In-class lecture (1.5~2H) (attendance 10%)
  - Paper/code reivew(0~1.5H)(40%)
  - A final exam(50%)

## Syllabus
|Event|Date|In-class lecture|Materials and Assignments|
|---------|----|-------------|------------|
|Lecture 1|03/05|Course Introduction<br><ul><li><a href="https://github.com/bart7449/lecture2021a/blob/slides/landscape.pdf">Landscape</a><li><a href="https://arxiv.org/pdf/2001.08361.pdf">Power Law in Neural Language Model</a>|<ul><li>No assignments<li><a href="https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf">How to Read a Paper</a><li><a href="https://bart7449.tistory.com/9">명제와 정의 용어 정리</a>|
|Lecture 2|03/12|Topics:<ul><li>An Introduction to Neural Networks(<a href="http://www.charuaggarwal.net/Chap1slides.pdf">slides</a>) |<ul><li>No assignments <li><a href="https://www.deeplearningbook.org/contents/notation.html">Notations for understanding papers</a>|
|Lecture 3|03/19|Topics: Machine Learning with Shallow Neural Networks I(<a href="http://www.charuaggarwal.net/Chap2slides.pdf">slides)</a>|Paper review:<ul><li><a href="https://github.com/bart7449/lecture2021a/blob/slides/Mikolov2013b_review_ydh.pdf">[Mikolov13a]</a>(<a href="https://github.com/bart7449/lecture2021a/blob/main/skip-gram%20code%20review.ipynb">code</a>)양동헌 |
|Lecture 4|03/26|Topics: Machine Learning with Shallow Neural Networks II(<a href="http://www.charuaggarwal.net/Chap2slides.pdf">slides)</a>|Paper review:<ul><li><a href="https://github.com/bart7449/lecture2021a/blob/slides/Doc2Vec_review_juyeon.pdf">[Le14a]</a>유주연<li><a href="https://github.com/bart7449/lecture2021a/blob/slides/Bojanowski17a_review_ljy.pdf">[Bojanowski17a]</a>이준영|
|Lecture 5|04/02|Topics: Training Deep Neural Networks I(<a href="http://www.charuaggarwal.net/Chap3slides.pdf">slides</a>)|Paper review:<ul><li><a href="https://github.com/bart7449/lecture2021a/blob/slides/batch%20Normalization.pdf">[Ioffe15a]</a>이건호 |
|Lecture 6|04/09|Topics: Training Deep Neural Networks II(<a href="http://www.charuaggarwal.net/Chap3slides.pdf">slides</a>)|Paper Review:<ul><li><a href="https://github.com/bart7449/lecture2021a/blob/slides/node2vec_Byungyun.pdf">[Grover16a]</a>공병윤   <li><a href="https://github.com/bart7449/lecture2021a/blob/slides/Paper%20review_%EA%B9%80%EC%A0%95%EB%AF%BC_(Distilling%20the%20Knowledge%20in%20a%20Neural%20Network).pdf">[Hinton15a]</a>김정민 |
|Lecture 7|04/16|Topics: Training Deep Neural Networks II(<a href="http://www.charuaggarwal.net/Chap3slides.pdf">slides</a>)<br>Topics: Teaching Deep Learners to Generalize (<a href="http://www.charuaggarwal.net/Chap4slides.pdf">slides</a>)|Paper review:<ul><li>[Ba2016a] |
|Lecture 8|04/23|Topics: Convolutional Neural Networks I(<a href="http://www.charuaggarwal.net/Chap8slides.pdf">slides</a>)|<ul><li>[Glorot10a],[He2015a]양동헌 |
|Lecture 9|04/30|Topics: Convolutional Neural Networks II(<a href="http://www.charuaggarwal.net/Chap8slides.pdf">slides</a>)|Paper Reviews:<ul><li>[Alex12a]송지현<li>[He16a]이건호 |
|Lecture 10|05/07|Topics: Recurrent Neural Networks I(<a href="http://www.charuaggarwal.net/Chap7slides.pdf">slides</a>)|Paper Reviews:<ul><li>[He16b]김정민<li>[Huang17a]이준영<li>[Hu2018]김형민 |
|Lecture 11|05/14|Topics:Recurrent Neural Networks II(<a href="http://www.charuaggarwal.net/Chap7slides.pdf">slides</a>)|No assignments | 
|Lecture 12|05/21|Topics: Attention and Language Model I(slides)|Paper Reviews:<ul><li>[Badahnau16]유주연<li>[Vaswani17a]전호범|
|Lecture 13|05/28|Topics: Attention and Language Model II|Paper Reviews:<ul><li>[Devlin19a]송지현 |
|Lecture 14|06/04|Topis: Lightweight Model<ul><li>Quantized Neural Networks|Paper reviews:<ul><li>[Rastegary16a]공병윤<li>[Stock20a]김형민|
|Lecture 15|06/11|Topics: Lightweight Model<ul><li>Compact Network Design|Paper reviews:<ul><li>[Howard17a],[Sandler18a]전호범 |
|Lecture 16|06/18|Final Exam|No Assignments | 
  
## Reading list for further discussion
### General Techniques
- [Ioffe15a] <a href="http://proceedings.mlr.press/v37/ioffe15.pdf"> Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift</a>, In Proceedings of ICLR 2015.
- (optional)[Ba2016a] <a href="https://arxiv.org/pdf/1607.06450.pdf?utm_source=sciontist.com">Layer Normalization</a>, arXiv:1607.06450v1, 2016.
- (optional)[Glorot10a]<a href="http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf">Understanding the difficulty of training deep feedforward neural networks</a>, In proceedings of AISTATS 2010.
- (optional)[He2015a] <a href="https://openaccess.thecvf.com/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf">Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification</a>, In Proceedings of ICCV 2015.
- [Hinton15a] <a href="https://arxiv.org/pdf/1503.02531.pdf">Distilling the Knowledge in a Neural Network</a>, arXiv:1503.02531v1, 2015.

### Convolutional Neural Network
- [Alex12a] <a href="https://kr.nvidia.com/content/tesla/pdf/machine-learning/imagenet-classification-with-deep-convolutional-nn.pdf">ImageNet Classification with Deep Convolutional Neural Networks </a>,  Advances in Neural Informaiton Processing Systems 25:1098-1105, 2012
- [He16a] <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">Deep Residual Learning for Image Recognition</a>, In Proceedings of CVPR 2016.
- [He16b] <a href="https://arxiv.org/pdf/1603.05027.pdf">Identity mapping in deep residual networks</a>, In Proceedings of ECCV 2016.
- [Huang17a] <a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Densely_Connected_Convolutional_CVPR_2017_paper.pdf">Densely connected convolutional networks</a>, In Proceedings of CVPR 2017.
- [Hu2018]<a href="">Squeeze-and-excitation networks</a>, In Proceedings of CVPR 2018.

### Distributed Representations for words and graphs
- [Mikolov13a] <a href="https://arxiv.org/pdf/1310.4546.pdf">Distributed Representations of Words and Phrases and their Compositionality</a>, Advances in Neural Information Processing Systems 26 (2013): 3111-3119.
- [Rong2016a] <a href="https://arxiv.org/pdf/1411.2738.pdf&xid=25657,15700021,15700124,15700149,15700168,15700186,15700191,15700201,15700208&usg=ALkJrhhNCZKc2CO7hRoTrGd6aH2nBc-ZVQ">word2vec Parameter Learning Explained</a>, arXiv:1411.2738v4
- [Le14a]<a href="http://proceedings.mlr.press/v32/le14.pdf">Distributed Representations of Sentences and Documents</a>, In Proceedings of the ICML 2014.
- [Bojanowski17a] <a href="https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00051?source=post_page---------------------------">Enriching word vectors with subword information</a>, Transactions of the Association for Computational Linguistics 5 (2017): 135-146.
- [Grover16a] <a href="https://dl.acm.org/doi/pdf/10.1145/2939672.2939754">node2vec: Scalable Feature Learning for Networks</a>, In Proceedings of KDD 2016.

### Attention and Transformers
- [Badahnau16a] <a href="https://arxiv.org/pdf/1409.0473.pdf"> NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE</a>, In Proceedings of ICLR 2015
- [Vaswani17a] <a href="https://arxiv.org/pdf/1706.03762.pdf">Attention is All You Need<a>, In Proceedings of NeurIPS 2017  
- [Devlin19a] <a href="https://www.aclweb.org/anthology/N19-1423/">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a>, In Proceedings of ACL 2019

### Lightweight Model
  - [Rastegary16a] <a href="https://arxiv.org/pdf/1603.05279.pdf?source=post_page---------------------------">XNOR-Net: ImageNet classification using binary convolutional Neural Networks</a>, In Proceedings of ECCV 2016
  - [Sandler18a] <a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Sandler_MobileNetV2_Inverted_Residuals_CVPR_2018_paper.pdf">Mobilenetv2: Inverted residuals and linear bottlenecks</a>, In Proceedings of CVPR 2018
    - [Howard17a] <a href="https://arxiv.org/abs/1704.04861">MobileNets: Efficient convolutional Neural Networks for Mobile Vision Applications</a>, arXiv preprint arXiv:1704.04861, 2017
  - [Stock20a] <a href="https://arxiv.org/pdf/1907.05686.pdf?utm_campaign=ExternalTechRecSeptember52019&utm_content=100275348&utm_medium=social&utm_source=twitter&hss_channel=tw-992153930095251456">And the bit goes down: revisiting the quantization of neural networks</a>, In Proceedings of ICLR 2020
