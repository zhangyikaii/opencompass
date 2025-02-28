<div align="center">
  <img src="docs/zh_cn/_static/image/logo.svg" width="500px"/>
  <br />
  <br />

[![docs](https://readthedocs.org/projects/opencompass/badge)](https://opencompass.readthedocs.io/zh_CN)
[![license](https://img.shields.io/github/license/InternLM/opencompass.svg)](https://github.com/InternLM/opencompass/blob/main/LICENSE)

<!-- [![PyPI](https://badge.fury.io/py/opencompass.svg)](https://pypi.org/project/opencompass/) -->

[🌐Website](https://opencompass.org.cn/) |
[📘Documentation](https://opencompass.readthedocs.io/zh_CN/latest/index.html) |
[🛠️Installation](https://opencompass.readthedocs.io/zh_CN/latest/get_started.html#id1) |
[🤔Reporting Issues](https://github.com/InternLM/opencompass/issues/new/choose)

[English](/README.md) | 简体中文

</div>

<p align="center">
    👋 加入我们的 <a href="https://discord.gg/KKwfEbFj7U" target="_blank">Discord</a> 和 <a href="https://r.vansin.top/?r=opencompass" target="_blank">微信社区</a>
</p>

## 🧭	欢迎

来到**OpenCompass**！

就像指南针在我们的旅程中为我们导航一样，我们希望OpenCompass能够帮助你穿越评估大型语言模型的重重迷雾。OpenCompass提供丰富的算法和功能支持，期待OpenCompass能够帮助社区更便捷地对NLP模型的性能进行公平全面的评估。

> **🔥 注意**<br />
> 我们正式启动 OpenCompass 共建计划，诚邀社区用户为 OpenCompass 提供更具代表性和可信度的客观评测数据集!
> 点击 [Issue](https://github.com/InternLM/opencompass/issues/248) 获取更多数据集.
> 让我们携手共进，打造功能强大易用的大模型评测平台！

## 🚀 最新进展 <a><img width="35" height="20" src="https://user-images.githubusercontent.com/12782558/212848161-5e783dd6-11e8-4fe0-bbba-39ffb77730be.png"></a>

- **\[2023.08.25\]**  欢迎 [**TigerBot**](https://github.com/TigerResearch/TigerBot) 团队采用OpenCompass对模型进行系统评估。我们非常感谢社区在提升LLM评估的透明度和可复现性上所做的努力。
  🔥🔥🔥.
- **\[2023.08.21\]** [**Lagent**](https://github.com/InternLM/lagent) 正式发布，它是一个轻量级、开源的基于大语言模型的智能体（agent）框架。我们正与Lagent团队紧密合作，推进支持基于Lagent的大模型工具能力评测 ! 🔥🔥🔥.
- **\[2023.08.18\]** OpenCompass现已支持**多模态评测**，支持10+多模态评测数据集，包括 **MMBench, SEED-Bench, COCO-Caption, Flickr-30K, OCR-VQA, ScienceQA** 等. 多模态评测榜单即将上线，敬请期待!
- **\[2023.08.18\]** [数据集页面](https://opencompass.org.cn/dataset-detail/MMLU) 现已在OpenCompass官网上线，欢迎更多社区评测数据集加入OpenCompass !
- **\[2023.08.11\]** 官网榜单上新增了[模型对比](https://opencompass.org.cn/model-compare/GPT-4,ChatGPT,LLaMA-2-70B,LLaMA-65B)功能，希望该功能可以协助提供更多发现！
- **\[2023.08.11\]** 新增了 [LEval](https://github.com/OpenLMLab/LEval) 评测支持.

> [更多](docs/zh_cn/notes/news.md)

## ✨ 介绍

OpenCompass 是面向大模型评测的一站式平台。其主要特点如下：

- **开源可复现**：提供公平、公开、可复现的大模型评测方案

- **全面的能力维度**：五大维度设计，提供 50+ 个数据集约 30 万题的的模型评测方案，全面评估模型能力

- **丰富的模型支持**：已支持 20+ HuggingFace 及 API 模型

- **分布式高效评测**：一行命令实现任务分割和分布式评测，数小时即可完成千亿模型全量评测

- **多样化评测范式**：支持零样本、小样本及思维链评测，结合标准型或对话型提示词模板，轻松激发各种模型最大性能

- **灵活化拓展**：想增加新模型或数据集？想要自定义更高级的任务分割策略，甚至接入新的集群管理系统？OpenCompass 的一切均可轻松扩展！

## 📊 性能榜单

我们将陆续提供开源模型和API模型的具体性能榜单，请见 [OpenCompass Leaderbaord](https://opencompass.org.cn/rank) 。如需加入评测，请提供模型仓库地址或标准的 API 接口至邮箱  `opencompass@pjlab.org.cn`.

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 📖 数据集支持

<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>语言</b>
      </td>
      <td>
        <b>知识</b>
      </td>
      <td>
        <b>推理</b>
      </td>
      <td>
        <b>学科</b>
      </td>
      <td>
        <b>理解</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
<details open>
<summary><b>字词释义</b></summary>

- WiC
- SummEdits

</details>

<details open>
<summary><b>成语习语</b></summary>

- CHID

</details>

<details open>
<summary><b>语义相似度</b></summary>

- AFQMC
- BUSTM

</details>

<details open>
<summary><b>指代消解</b></summary>

- CLUEWSC
- WSC
- WinoGrande

</details>

<details open>
<summary><b>翻译</b></summary>

- Flores

</details>
      </td>
      <td>
<details open>
<summary><b>知识问答</b></summary>

- BoolQ
- CommonSenseQA
- NaturalQuestion
- TrivialQA

</details>

<details open>
<summary><b>多语种问答</b></summary>

- TyDi-QA

</details>
      </td>
      <td>
<details open>
<summary><b>文本蕴含</b></summary>

- CMNLI
- OCNLI
- OCNLI_FC
- AX-b
- AX-g
- CB
- RTE

</details>

<details open>
<summary><b>常识推理</b></summary>

- StoryCloze
- StoryCloze-CN（即将上线）
- COPA
- ReCoRD
- HellaSwag
- PIQA
- SIQA

</details>

<details open>
<summary><b>数学推理</b></summary>

- MATH
- GSM8K

</details>

<details open>
<summary><b>定理应用</b></summary>

- TheoremQA

</details>

<details open>
<summary><b>代码</b></summary>

- HumanEval
- MBPP

</details>

<details open>
<summary><b>综合推理</b></summary>

- BBH

</details>
      </td>
      <td>
<details open>
<summary><b>初中/高中/大学/职业考试</b></summary>

- GAOKAO-2023
- CEval
- AGIEval
- MMLU
- GAOKAO-Bench
- CMMLU
- ARC

</details>
      </td>
      <td>
<details open>
<summary><b>阅读理解</b></summary>

- C3
- CMRC
- DRCD
- MultiRC
- RACE

</details>

<details open>
<summary><b>内容总结</b></summary>

- CSL
- LCSTS
- XSum

</details>

<details open>
<summary><b>内容分析</b></summary>

- EPRSTMT
- LAMBADA
- TNEWS

</details>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 📖 模型支持

<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>开源模型</b>
      </td>
      <td>
        <b>API 模型</b>
      </td>
      <!-- <td>
        <b>自定义模型</b>
      </td> -->
    </tr>
    <tr valign="top">
      <td>

- LLaMA
- Vicuna
- Alpaca
- Baichuan
- WizardLM
- ChatGLM-6B
- ChatGLM2-6B
- MPT
- Falcon
- TigerBot
- MOSS
- ……

</td>
<td>

- OpenAI
- Claude (即将推出)
- PaLM (即将推出)
- ……

</td>
<!-- <td>

- GLM
- ……

</td> -->
</tr>
  </tbody>
</table>

## 🛠️ 安装

下面展示了快速安装以及准备数据集的步骤。

```Python
conda create --name opencompass python=3.10 pytorch torchvision pytorch-cuda -c nvidia -c pytorch -y
conda activate opencompass
git clone https://github.com/InternLM/opencompass opencompass
cd opencompass
pip install -e .
# 下载数据集到 data/ 处
wget https://github.com/InternLM/opencompass/releases/download/0.1.1/OpenCompassData.zip
unzip OpenCompassData.zip
```

有部分第三方功能,如 Humaneval 以及 Llama,可能需要额外步骤才能正常运行，详细步骤请参考[安装指南](https://opencompass.readthedocs.io/zh_CN/latest/get_started.html)。

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 🏗️ ️评测

确保按照上述步骤正确安装 OpenCompass 并准备好数据集后，可以通过以下命令评测 LLaMA-7b 模型在 MMLU 和 C-Eval 数据集上的性能：

```bash
python run.py --models hf_llama_7b --datasets mmlu_ppl ceval_ppl
```

OpenCompass 预定义了许多模型和数据集的配置，你可以通过 [工具](./docs/zh_cn/tools.md#ListConfigs) 列出所有可用的模型和数据集配置。

```bash
# 列出所有配置
python tools/list_configs.py
# 列出所有跟 llama 及 mmlu 相关的配置
python tools/list_configs.py llama mmlu
```

你也可以通过命令行去评测其它 HuggingFace 模型。同样以 LLaMA-7b 为例：

```bash
python run.py --datasets ceval_ppl mmlu_ppl \
--hf-path huggyllama/llama-7b \  # HuggingFace 模型地址
--model-kwargs device_map='auto' \  # 构造 model 的参数
--tokenizer-kwargs padding_side='left' truncation='left' use_fast=False \  # 构造 tokenizer 的参数
--max-out-len 100 \  # 最长生成 token 数
--max-seq-len 2048 \  # 模型能接受的最大序列长度
--batch-size 8 \  # 批次大小
--no-batch-padding \  # 不打开 batch padding，通过 for loop 推理，避免精度损失
--num-gpus 1  # 所需 gpu 数
```

通过命令行或配置文件，OpenCompass 还支持评测 API 或自定义模型，以及更多样化的评测策略。请阅读[快速上手](https://opencompass.readthedocs.io/zh_CN/latest/get_started.html#id3)了解如何运行一个评测任务。

更多教程请查看我们的[文档](https://opencompass.readthedocs.io/zh_CN/latest/index.html)。

## 🔜 路线图

- [ ] 主观评测
  - [ ] 发布主观评测榜单
  - [ ] 发布主观评测数据集
- [ ] 长文本
  - [ ] 支持广泛的长文本评测集
  - [ ] 发布长文本评测榜单
- [ ] 代码能力
  - [ ] 发布代码能力评测榜单
  - [ ] 提供非Python语言的评测服务
- [ ] 智能体
  - [ ] 支持丰富的智能体方案
  - [ ] 提供智能体评测榜单
- [ ] 鲁棒性
  - [ ] 支持各类攻击方法

## 👷‍♂️ 贡献

我们感谢所有的贡献者为改进和提升 OpenCompass 所作出的努力。请参考[贡献指南](https://opencompass.readthedocs.io/zh_CN/latest/notes/contribution_guide.html)来了解参与项目贡献的相关指引。

## 🤝 致谢

该项目部分的代码引用并修改自 [OpenICL](https://github.com/Shark-NLP/OpenICL)。

该项目部分的数据集和提示词实现修改自 [chain-of-thought-hub](https://github.com/FranxYao/chain-of-thought-hub), [instruct-eval](https://github.com/declare-lab/instruct-eval)

## 🖊️ 引用

```bibtex
@misc{2023opencompass,
    title={OpenCompass: A Universal Evaluation Platform for Foundation Models},
    author={OpenCompass Contributors},
    howpublished = {\url{https://github.com/InternLM/OpenCompass}},
    year={2023}
}
```

<p align="right"><a href="#top">🔝返回顶部</a></p>
