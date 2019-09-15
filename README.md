# MIT 6.S191: Introduction to Deep Learning

This repository contains all of the code and software labs for [MIT 6.S191: Introduction to Deep Learning](http://introtodeeplearning.com)! All lecture slides and videos are available on the course website. 


## Opening the labs in Google Colaboratory:
The 2019 6.S191 labs will be run in Google's Colaboratory, a Jupyter notebook environment that runs entirely in the cloud, you don't need to download anything. To run these labs, you must have a Google account. You have two options to open these labs in Colab. 

***Option 1:***
On this Github repo, navigate to the lab you want to run and open the appropriate python notebook (\*.ipynb). Click the "Run in Colab" link on the top of the lab. That's it! 

***Option 2:***
Go to [Colab](https://colab.research.google.com/), and then select the "GitHub" tab in the pop-up window. Enter the GitHub link to the [6.S191 Repository](https://github.com/aamini/introtodeeplearning_labs/), and open the relevant lab.

## Running the labs
Now, to run the labs, open the Jupyter notebook on Colab. Navigate to the "Runtime" tab --> "Change runtime type". In the pop-up window, under "Runtime type" select "Python 2", and under "Hardware accelerator" select "GPU". Go through the notebooks and fill in the `#TODO` cells to get the code to compile for yourself!


Lab 1：介绍TensorFlow及音乐生成

第1讲侧重于神经网络基础。因此lab 1中的第一个模块简单介绍了TensorFlow，为即将发布的TensorFlow 2.0做准备。

TensorFlow练习的介绍中，特别强调了几个关键概念：如何使用数学运算符执行计算；如何定义神经网络模型；以及如何使用自动微分来训练具有反向传播的网络。

lab 1的第二个模块直接进入构建和RNN进行音乐生成，旨在配合第2讲深度序列建模。 

通过第二模块，你将能够构建一个人工智能算法，生成全新的、从未听过的爱尔兰民歌。为什么爱尔兰民间音乐不是二人转啥的呢？因为课程设计者特别喜欢下面这个萌萌哒☘谷歌Doodle。动图中的几个☘们正在表演传统的爱尔兰民歌。

通过填写代码块以定义RNN模型，使用爱尔兰民歌的数据集（在ABC表示法中）训练模型，使用学习的模型生成新歌曲，然后播放生成的内容来检验你的模型的成果如何。



Lab 2：计算机视觉：消除偏见的面部检测系统

Lab 2伴随着深度计算机视觉和深度生成模型的讲座。

第1部分通过卷积神经网络（CNN）的示例提供了对基本神经网络架构的实现的持续实践，用于对著名的MNIST数据集中的手写数字进行分类。

第2部分更进一步，探讨了应用深度学习的两个突出例子：面部检测和算法偏见。

尽管神经网络在识别图像中的面部识别的消除偏见方面表现非常出色，但最近有很多人关注这些人工智能会遭受隐藏的算法偏见。事实证明，深度学习本身可以帮助对抗这种偏见。

MIT基于变分自动编码器（VAE）训练了一个模型，该模型学习特定任务，如面部检测、以及训练数据的基础结构。



反过来，该算法使用这种学习的潜在结构，来揭示隐藏的偏见，并将其影响降低至最小化。

当应用于面部检测任务时，与最先进的模型相比，MIT的算法降低了分类偏见并保持了非常高的整体准确性。

这个软件lab将教会你如何构建这个去除模型，并评估其在消除面部检测任务方面的功效。

除了考虑算法偏见及如何对抗之外，你还将获得VAE的实操经验，这种架构通常不会在深度学习实施教程中突出显示。

更重要的是，这种方法可以应用于面部检测以外的任何环境！



Lab 3：无模型强化学习

这个lab开始，你讲接触到深层强化学习的基础技巧。

与之前专注于监督和无监督学习的lab相比，强化学习旨在教会代理人如何在世界上行动以最大化自己的奖励。 

Tensorflow的强制执行为RL提供了一种简化的方法，你可以在lab 3中，从头开始完整的编写一段程序。

我们专注于学习两个任务：控制（例如Cart-Pole）和游戏（例如Pong）。MIT会分配学生一个任务：建立一个模块化的RL框架，只使用一个“RL大脑”来学习这两个截然不同的环境。

处理这些基线环境为学生提供了迅速掌握快速创建新算法原型的方法。学生们最终能够具体了解如何实施RL培训程序，并将这些想法用作最终项目中的模板。


资源下载


课程视频：
https://youtu.be/5v1JnYv_yWs?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI

lab代码：
https://github.com/aamini/introtodeeplearning_labs/

TensorFlow官网：
https://www.tensorflow.org/
