# 书生·浦语大模型训练营第二节课作业
教程链接：https://github.com/InternLM/Tutorial/blob/camp2/helloworld/hello_world.md

作业要求：https://github.com/InternLM/Tutorial/blob/camp2/helloworld/homework.md
## 基础作业
### HW1-使用 InternLM2-Chat-1.8B 模型生成 300 字的小故事
部署成功截图；
![alt text](hw-base1.png)
## 进阶作业
### HW2-Lagent 工具调用 数据分析 Demo 部署
部署成功截图：
![alt text](hw-adavance1.png)
### HW3-使用huggingface进行模型下载
使用教程中的查看文件可以确定下载成功
![alt text](show.png)
```python
#show.py
import os 
from huggingface_hub import hf_hub_download  # Load model directly 
hf_hub_download(repo_id="internlm/internlm2-7b", filename="config.json")
```
### HW4-部署浦语·灵笔2模型
图文创作部署成功截图：
![alt text](image-4.png)
视觉问答部署成功截图：
![alt text](image-6.png)