# CodeFuse

<p align="center">
  <img src="assets/LOGO.png" width="50%" />
</p>


<div align="center">

[**简体中文**](https://github.com/codefuse-ai/.github/blob/main/profile/README_CN.md)|[**HF Repo**](https://huggingface.co/codefuse-ai)|[**ModelScope Repo**](https://modelscope.cn/organization/codefuse-ai)

</div>

## About This Repository

This repository lists key projects and related demos about CodeFuse. 

## About CodeFuse

CodeFuse aims to develop Code Large Language Models (Code LLMs) to support and enhance full-lifecycle AI native sotware developing, covering crucial stages such as design requirements, coding, testing, building, deployment, operations, and insight analysis. Below is the overall framework of CodeFuse. 
<p align="center">
  <img src="https://github.com/codefuse-ai/.github/assets/82250814/9c8cd9f3-b1ca-43a1-9b0f-8f612b06753e" width="90%" />
</p>
<br/>

## List of CodeFuse Projects

We listed projects according to the lifecycle above. 
| LifeCycle Stage               | Project Repository|  Repo-Description | 
|:------------------------:|:-----------------:|:-------:|
| Project Copilot     |    NA             |     NA  | 
| Code Copilot        |[MFTCoder](https://github.com/codefuse-ai/MFTCoder) | Instruction-Tuning Framework  |
|                     |[FastTransformer4CodeFuse](https://github.com/codefuse-ai/FasterTransformer4CodeFuse) | FT based Inference Engine | 
|                     |[CodeFuse-Eval](https://github.com/codefuse-ai/codefuse-evaluation)|Evaluation kits for CodeFuse |   
| Test&Build Copilot  |[TestAgent](https://github.com/codefuse-ai/Test-Agent) | TestGPT demo frontend  |  
| Ops Copilot         |[DevOps-Eval](https://github.com/codefuse-ai/codefuse-devops-eval)|Benchmark for DevOps|   
|                     |[DevOps-Model](https://github.com/codefuse-ai/CodeFuse-DevOps-Model) |index for DevOps  models|   
| Data Copilot        |    NA              |     NA   | 
| Auxilary Modules    |[ChatBot](https://github.com/codefuse-ai/codefuse-chatbot) |General chatbot frontend for CodeFuse | 
|                     |This Repo |General Introduction & index of CodeFuse Repos| 

## List of CodeFuse Released Models
| ModelName               | Short Description | Huggingface Links|  ModelScope Linls | 
|:------------------------:|:-----------------:|:-----------------:|:-------:|
| CodeFuse-13B     | Training from scratch |     HF |      MS  | 
| CodeFuse-CodeLLaMA-34B    |    Finetuning based on CodeLLaMA-34B  |     HF |      MS  | 
| CodeFuse-CodeLLaMA-34B-4bits |   4bits quantized models            |     HF |      MS  | 
| CodeFuse-StarCoder-15B    | Finetuning based on StarCoder-15B |     HF |      MS  | 
| CodeFuse-Qwen-14B    | Finetuning based on Qwen-14B           |     HF |      MS  | 
| CodeFuse-TestGPT-7B    |    NA             |     HF |      MS  | 


## Demos

 - Video demos: Chinese version at below, English version under preparation. 
   https://user-images.githubusercontent.com/103973989/267514150-21012a5d-652d-4aea-bcea-582e67855ad7.mp4

 - Online Demo: You can try our CodeFuse-CodeLlama-34B model on ModelScope: [CodeFuse-CodeLlama34B-MFT-Demo](https://modelscope.cn/studios/codefuse-ai/CodeFuse-CodeLlama34B-MFT-Demo/summary)

![Online Demo Snapshot](assets/modelscope_demo2.png)

- You can also try to install the [CodeFuse-Chatbot](https://github.com/codefuse-ai/codefuse-chatbot) to test our models locally. 

## How to get

- [**Huggingface Repo**](https://huggingface.co/codefuse-ai).
- [**ModelScope Repo**](https://modelscope.cn/organization/codefuse-ai).
- Train or finetuning on your own models, you can try our [**MFTCoder**](https://github.com/codefuse-ai/MFTCoder), which enables efficient fine-tuning for multi-task, multi-model, and multi-training-framework scenarios.

## Articles or References

For more details about our techniques, please refere to our tech-reports/papers below. 
- MFTCoder:

If you use our codes or models, or feel our project useful for your research works, please cite our paper as below.
```
@article{codefuse2023,
  title={},
  author={},
  journal={arXiv preprint arXiv},
  year={2023}
}

