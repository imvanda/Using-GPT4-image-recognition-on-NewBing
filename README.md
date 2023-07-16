# Using-GPT4-image-recognition-on-NewBing
如题，这是一个教你如何在NewBing上实现类似GPT-4发布会上，在纸上打草稿，然后让ai生成网站代码的“魔法”功能。尽管可能没有100%实现预期效果，但我决定这已经很不错了，充满了可玩性等待开发。
As you can see, this is teaching you how to achieve a "magic" like functionality on the free NewBing similar to what was showcased at the GPT-4 launch event, where you sketch ideas on paper and have the AI generate website code for you. Although it may not be 100% perfect, I still find it amazing and full of potential waiting for you to explore.
首先，让我们简单了解下原理，NewBing基于GPT-4，其实已经包含了图片识别的功能，但是目前还未开放，我们需要做的就是在浏览器的控制台中执行代码，来打开这个隐藏功能。下面我将演示：
## 步骤：
### 1.打开浏览器，进入NewBing页面，使用f12调出控制台。
### 2.在控制台中输入以下代码，此时先不要运行它：
```
_w["_sydConvConfig"].sydOptionSets += ",iycapbing,iyxapbing",
_w["_sydConvConfig"].enableVisualSearch = true;
```
### 3.刷新网页，在网页还未加载完成前按下Enter运行代码，此时NewBIng对话框将出现传图功能，你可以上传网络/本地图像给NewBing，并给她下达命令。
### 4.最后，以下我的演示，基本复刻GPT-4发布会上画的“大饼”😁
