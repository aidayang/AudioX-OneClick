# AudioX-OneClick

AudioX音乐音效生成软件免安装部署一键启动整合包，下载解压即用。

![](https://raw.githubusercontent.com/aidayang/AudioX-OneClick/refs/heads/main/audiox.jpg)

## AudioX官方介绍
音频和音乐生成已成为众多应用中的关键任务，然而现有方法面临诸多限制：它们各自为政，缺乏跨模态的统一能力，缺乏高质量的多模态训练数据，并且难以有效地整合不同的输入。在本研究中，我们提出了 AudioX，一个用于“任何内容到音频”和“音乐”生成的统一的扩散变换器 (Diffusion Transformer) 模型。与以往的特定领域模型不同，AudioX 可以生成高质量的通用音频和音乐，同时提供灵活的自然语言控制，并无缝处理包括文本、视频、图像、音乐和音频在内的各种模态。其关键创新在于一种多模态掩蔽训练策略，该策略可以掩蔽跨模态的输入，并迫使模型从掩蔽的输入中学习，从而产生稳健且统一的跨模态表征。为了解决数据稀缺问题，我们整理了两个全面的数据集：基于 VGGSound 数据集的包含 19 万条音频字幕的 vggsound-caps，以及源自 V2M 数据集的包含 600 万条音乐字幕的 V2M-caps。大量实验表明，AudioX 不仅能与最先进的专业模型匹敌或超越它们，而且在统一架构内处理各种输入模式和生成任务方面也具有出色的多功能性。

## AudioX整合包使用说明
首先将网盘内的软件压缩包下载到本地电脑上并解压，然后双击启动软件.exe打开软件启动webui

稍等片刻启动成功后会自动打开webui页面。

webui界面提供了文本合成音效和音乐，视频生成音效和音乐功能。

首先在顶部prompt输入框中输入想要生成音频内容的英文描述词。然后点击下面的Generate按钮即可生成音频或是音乐。你可以在下方Sampler Params中设置sample size值来设置音频时长，原来软件音频只能生成10秒，这里给稍微做了下代码修改。音频时长=sample size÷sample rate。

如果想给视频增加音效的话，可以在Video Path中输入视频路径或是点击下方Upload Video File上传视频文件。

可以输入文本描述词为视频添加指定音效，也可以让软件自动识别视频内容自动添加音效。

视频教程及效果演示：https://www.youtube.com/watch?v=bWCYMDQAZYI

## 注意事项
软件整合包只支持英伟达30或40系列显卡电脑

只支持windows10或11

软件运行路径中不要有非英文字符和空格，待处理文件同样要注意

## 音乐音效生成软件AudioX整合包下载链接
https://pan.quark.cn/s/1eb91866528d

https://pan.baidu.com/s/1_dccvq1RkKlrlaXGX0adlQ?pwd=cmea

## 项目链接
https://github.com/ZeyueT/AudioX

## License

Please follow [CC-BY-NC](./LICENSE).
