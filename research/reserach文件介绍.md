# TensorFLow 研究模型

该文件夹包含了由研究者在[TensorFlow](https://tensorflow.org)上实施的机器学习模型．模型由他们对应的作者维护．若想提交一个模型，请提交一个pull请求．

目前，这里的模型兼容TensorFlow1.0或者之后的版本，如果你正运行在TensorFlow0.12或者之前的版本，请[更新你的安装](https://www.tensorflow.org/install)

## 模型

-   [adversarial_crypto](adversarial_crypto): 以对抗神经密码学(adversarial neural cryptography)保护沟通．
-   [adversarial_text](adversarial_text):用对抗训练来进行半监督序列学习
-   [attention_ocr](attention_ocr): 一个用于现实世界图片文本(image text)提取的模型.
-   [audioset](audioset): 用于[AudioSet](http://g.co/audioset)的模型(s)和代码支持．
-   [autoencoder](autoencoder): 不同的自编码器
-   [brain_coder](brain_coder): 强化学习的程序综合(Program synthesis).
-   [cognitive_mapping_and_planning](cognitive_mapping_and_planning):基于映射和用于可视导航的计划框架的空间记忆的实施．
-   [compression](compression):用一个预训练的残差ＧＲＵ网络压缩和解压图片．
-   [deeplab](deeplab): deep labelling for semantic image segmentation.
-   [delf](delf): 用于图片匹配和恢复的深度局部特征(features)．
-   [differential_privacy](differential_privacy): 针对训练数据的不同隐私(differential privacy).
-   [domain_adaptation](domain_adaptation): 域分离网络(DSN).
-   [gan](gan): 生成对抗网络．
-   [im2txt](im2txt): 用于生成图片标题的image-to-text 神经网络.
-   [inception](inception): 用于计算机视觉的深度卷积网络．
-   [learning_to_remember_rare_events](learning_to_remember_rare_events): 
    大规模长寿命记忆模块在深度深度学习上的使用．
-   [learning_unsupervised_learning](learning_unsupervised_learning): 一个
    meta-learned无监督学习更新规则．
-   [lexnet_nc](lexnet_nc): 用于名词符合关系分类的分布模型(noun compound relationship
    classification).
-   [lfads](lfads): 用于分析Neuroscience(一个杂志)数据的序列化变分自编码器.
-   [lm_1b](lm_1b): 对于[1 Billion Word Language Model Benchmark](http://www.statmt.org/lm-benchmark/)语言建模．
-   [maskgan](maskgan): 使用GANs的文本生成.
-   [namignizer](namignizer): 识别和生成名字(s).
-   [neural_gpu](neural_gpu): 高度并行的神经计算机(neural computer).
-   [neural_programmer](neural_programmer): 以逻辑和数学运算为参数的神经经网络．
-   [next_frame_prediction](next_frame_prediction):通过交叉卷积网络(实现)的概率未来帧综合:[probabilistic future frame synthesis via cross convolutional networks](http://visualdynamics.csail.mit.edu/visualDynamics16.pdf) .
-   [object_detection](object_detection): 在单张图片中定位和识别多个目标对象．
-   [pcl_rl](pcl_rl): 几种强化学习算法的代码，包括路径一致学习(Path Consistency Learning).
-   [ptn](ptn): 3D对象重建的视角转换网络(perspective transformer nets).
-   [qa_kg](qa_kg): 用于在知识图(knowledge graphs)回答问题的模块网络(module networks).
-   [real_nvp](real_nvp): 使用实值非体积保留(real NVP)转换的密度估计．
-   [rebar](rebar): 对离散潜在变量模型的低方差无偏见unbiased梯度估计.
-   [resnet](resnet): 深度和wide残差网络.
-   [skip_thoughts](skip_thoughts): RNN的句子转向量编码器．
-   [slim](slim): 使用TF-Slim的图片分类模型．
-   [street](street): 使用深度DNN从一张图片中识别一条法国的街道的名字．
-   [swivel](swivel): 用于生成词embeddings的Swivel算法．
-   [syntaxnet](syntaxnet): 自然语言语法的神经网络．
-   [tcn](tcn): 从多视角视频中学习的自监督表现/陈述representation．
-   [textsum](textsum): 用于文本总结的使用attention模型的seq2seq.
-   [transformer](transformer): 空间转换网络，允许在网络内进行数据的空间操作．
-   [video_prediction](video_prediction): 以神经流预测视频的未来帧．