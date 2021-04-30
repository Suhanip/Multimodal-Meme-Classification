# Multimodal-Meme-Classification
Identifying offensive content in image and text


This repository contains the code for identifying offensive content in image and text. Stacked LSTM + VGG16 is one of the way to identifying whether the given meme is offensive or not as mentioned in [[1]](#1).

Technique used: Early Stopping to combine the image and the text modality and compare it with text- and an image-only baseline.

Prerequisite : Download the file "http://nlp.stanford.edu/data/glove.6B.zip" for before the execution of Glove Embedding of 50d.

Multi-OFF Dataset was leveraged by the authors to the 2016 U.S.Presidential election.
Dataset can be downloaded using the link https://drive.google.com/drive/folders/1hKLOtpVmF45IoBmJPwojgq6XraLtHmV6?usp=sharing

## References
<a id="1">[1]</a> 
Suryawanshi, Shardul and Chakravarthi, Bharathi Raja and Arcan, Mihael and Buitelaar, Paul (2020). 
[Multimodal Meme Dataset (MultiOFF) for Identifying Offensive Content in Image and Text.](https://www.aclweb.org/anthology/2020.trac-1.6.pdf)
Association for Computational Linguistics.
