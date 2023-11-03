# DL_2023 - Final Assignment: Mini Research Project 
<center> Pei-Hsun Chen, Jinjia Huang, Lida Khachatryan, Mohsen Mohammadi, Jesica Olivares 

### A Review of:

## AN IMAGE IS WORTH 16X16 WORDS: TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE 

Alexey Dosovitskiy∗,†, Lucas Beyer∗, Alexander Kolesnikov∗, Dirk Weissenborn∗, Xiaohua Zhai∗, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, Sylvain Gelly, Jakob Uszkoreit, Neil Houlsby∗,† ∗equal technical contribution, †equal advising 
Google Research, Brain Team 


For this deep learning research project, we choose a paper in the field of image classification: ‘An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale’. This is a paper from Google research in 2021, the official code was included in the paper. We chose this paper because it provides a novel approach in the field of computer vision, a critical area in Deep Learning (DL).  

Transformer architecture, which is part of the self-attention-based architectures, is widely used and became the state of art method in natural language processing (NLP) field. Still, in computer vision, convolutional neural networks (CNN) approach remains dominant. This paper aims to expand the application of Transformer to computer vision. There are empirical results showing that transformers applied directly to image patches and pre-trained on large datasets perform well in image classification, and the reliance on CNNs is not necessary. 

The paper takes the approach of splitting the images into patches and proving the sequence of linear embeddings of these patches as an input to a Transformer, somewhat like the tokens used in NLP. 
If the training datasets are large (14M-300M images), the paper illustrates that the Vision transformer (ViT) would perform with excellent results compared with the discouraging outcome when trained on mid-sized datasets. Transformers are then superior to CNN’s inherited inductive bias because of the large-scale pre-training.  

In this report, we examined and analyzed the paper and developed a comprehensive understanding of its contributions to computer vision and identifying certain limitations. Additionally, we have made diligent efforts to implement the provided code to reproduce the paper's results and have proposed potential enhancements to further advance the research in this area. Our findings and insights are detailed in the subsequent sections of this report.  

 
