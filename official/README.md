# TensorFlow Official Models

The TensorFlow official models are a collection of example models that use TensorFlow's high-level APIs. They are intended to be well-maintained, tested, and kept up to date with the latest TensorFlow API. They should also be reasonably optimized for fast performance while still being easy to read.

The master branch of the models are **in development**, and they target the [nightly binaries](https://github.com/tensorflow/tensorflow#installation) built from the [master branch of TensorFlow](https://github.com/tensorflow/tensorflow/tree/master). We aim to keep them backwards compatible with the latest release when possible (currently TensorFlow 1.5), but we cannot always guarantee compatibility.

**Stable versions** of the official models targeting releases of TensorFlow are available as tagged branches or [downloadable releases](https://github.com/tensorflow/models/releases). Model repository version numbers match the target TensorFlow release, such that [branch r1.4.0](https://github.com/tensorflow/models/tree/r1.4.0) and [release v1.4.0](https://github.com/tensorflow/models/releases/tag/v1.4.0) are compatible with [TensorFlow v1.4.0](https://github.com/tensorflow/tensorflow/releases/tag/v1.4.0).

If you are on a version of TensorFlow earlier than 1.4, please [update your installation](https://www.tensorflow.org/install/).

---

Below is a list of the models available.

[mnist](mnist): A basic model to classify digits from the MNIST dataset.

[resnet](resnet): A deep residual network that can be used to classify both CIFAR-10 and ImageNet's dataset of 1000 classes.

[wide_deep](wide_deep): A model that combines a wide model and deep network to classify census income data.

More models to come!

If you would like to make any fixes or improvements to the models, please [submit a pull request](https://github.com/tensorflow/models/compare).

---
## Running the models
The *Official Models* are made available as a Python module. To run the models and associated scripts, add the top-level ***/models*** folder to the Python path with the command: `export PYTHONPATH="$PYTHONPATH:/path/to/models"`

To install dependencies pass `-r official/requirements.txt` to pip. (i.e. `pip3 install --user -r official/requirements.txt`)

To make Official Models easier to use, we are planning to create a pip installable Official Models package. This is being tracked in [#917](https://github.com/tensorflow/models/issues/917).
***
# TensorFlow官方模型
TensorFlow官方模型是使用TensorFlow高级APIs的模型例子的收藏．他们打算被很好地维护,测试和保持更新至最新的TensorFlow API中．他们也应该为快速的性能而被合理的优化，同时应仍然易于阅读．

Models的master分支*中，并且他们以每夜从TensorFlow的master分支更新编码为目标．我们意欲让他们向后兼容随着最新版本的发布，但是我们不能总是保证兼容性．

面向TensofFlow发布的官方模型的**稳定版本**作为打上标签的分支或者[可下载的发布]是可以获取的．Model仓库版本号匹配目标的TensorFlow发布，比如branch r1.4.0和release v1.4.0和TensorFlow v1.4.0是兼容的．

如果你在一个早于1.4的版本上，请[更新你的安装](https://www.tensorflow.org/install/).
***
以下是可用的模型的列表：  
[mnist](mnist):一个用于分类来自MNIST数据集的数字的基本模型．  

[resnet](resnet):一个用于分类CITAR-10和具有1000个累的ImageNet数据集的深度residual网络  

[wide_deep](wide_deep)一个结合了wide模型和深度网络的用于分类census输入数据的模型．  

更多的模型就要来了！

如果你想对这些模型做任何修正和改进，请[提交一个请求](https://github.com/tensorflow/models/compare)

## 运行这些模型
*Official Models*可以作为Python的一个模块使用．为了运行模型和预支联系的脚本，用一下命令添加顶层的***/models***文件夹到Python路径中：`export PYTHONPATH="$PYTHONPATH:/path/to/models"`
传递`-r official/requirements.txt`到pip中来安装依赖关系.(也就是`pip3 install -user -r official/requirements.txt`)

为了使Official Modles更易于使用，我们正计划创造一个pip可安装的Official Models包．这正在被[917](https://github.com/tensorflow/models/issues/917)跟踪．