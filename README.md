# -Mixamo-Unity
将Mixamo的模型导入Unity
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/1.png)
在Mixamo上选择一个模型后点击animation找一个动画
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/2.png)
然后点击download，选择FBX for unity 和with skin
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/3.png)
将下载完的文件拖入unity，就会得到一个无贴图的人物模型
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/4.png)
点击该模型，在animation中会发现该模型有一个动画 这里叫做mixamo.com，勾选loop time并apply这样方便观察
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/5.png)
点击material的extract texture
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/6.png)
新建一个文件夹这里叫Zombie，并选择
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/7.png)
弹出窗口，点击fixnow
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/8.png)
得到有贴图的模型，但是点击play会发现模型不会动，这是因为该模型没有动画控制器
<br>
![pg1](https://github.com/Nevermore1984/-Mixamo-Unity/blob/master/9.png)
将动画再次拖到场景中的人物身上，会发现自动生成了一个控制器，这样人物就会动了
