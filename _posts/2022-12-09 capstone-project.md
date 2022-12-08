---
layout: post
title: Capstone project 
author: [Richard Kuo]
category: [Lecture]
tags: [jekyll, ai]
---

Final project: unknown

---
## 題目
### 系統簡介 & 功能說明
1. **系統簡介**
2. **功能說明**
### 系統方塊圖

---
### AI 模型說明
<iframe width="835" height="470" src="https://www.youtube.com/embed/DtzN5vtEgOk" title="RL-Robocar" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 

![](https://github.com/rkuo2000/AI-course/blob/gh-pages/images/stock_dqn.png?raw=true) 

1. Download pre-trained InterNet from [here](https://drive.google.com/drive/folders/1BET1f5p2-1OBOz6aNLuPBAVs_9NLz5Jo?usp=sharing)
2. Put the model at `demo` folder
3. Go to `demo` folder and edit `bbox` in [here](https://github.com/facebookresearch/InterHand2.6M/blob/5de679e614151ccfd140f0f20cc08a5f94d4b147/demo/demo.py#L74)
4. run `python demo.py --gpu 0 --test_epoch 20`
5. You can see `result_2D.jpg` and 3D viewer.

**Camera positios visualization demo**
1. `cd tool/camera_visualize`
2. Run `python camera_visualize.py`


<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

