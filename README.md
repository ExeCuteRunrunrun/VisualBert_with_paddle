# VisualBert_with_paddle
Paddle implementation of VisualBert paper [VisualBERT: A Simple and Performant Baseline for Vision and Language](https://arxiv.org/pdf/1908.03557.pdf), with help of its original implementation [code](https://github.com/huggingface/transformers/tree/master/src/transformers/models/visual_bert) in Pytorch.

# Dataset:
VQA, VCR, NLVR2, and Flickr30K

# Goal：
1. Reimplement VisualBert
2. Convert 9 models from pytorch to paddle:
    - uclanlp/visualbert-vqa
    - uclanlp/visualbert-vqa-pre
    - uclanlp/visualbert-vqa-coco-pre
    - uclanlp/visualbert-vcr
    - uclanlp/visualbert-vcr-pre 
    - uclanlp/visualbert-vcr-coco-pre
    - uclanlp/visualbert-nlvr2
    - uclanlp/visualbert-nlvr2-pre
    - uclanlp/visualbert-nlvr2-coco-pre

3. 在VQA测试集上Test-Dev=70.80, Test-Std=71.00，NLVR验证集accuracy=67.4（见论文Table1，Table3）
4. 提交PR至PaddleNLP
