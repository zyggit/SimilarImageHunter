# SimilarImageHunter
Mac OS X 上的小工具，用来查找相似内容的图片。

![](http://7ni3rk.com1.z0.glb.clouddn.com/QQ20160117-2.png)

## 使用方法

这款工具可以在目标路径中找出与原始路径中图片最为相似的图片。如果目标路径中有多张图片相似度相同且最大，这些图片都会被列出来。树形列表第一列的父节点内容为原始路径中的图片，子节点为目标路径中匹配到的最佳相似内容图片。列表第二列为相似度。双击图片路径即可打开该图片。点击 “HUNT” 按钮开始寻找相似图片，第一次使用时处理图片信息耗时较长，可在中途点击 “CANCEL” 按钮取消当前任务。“CLEAR” 按钮则可清除当前界面信息。

实现原理：http://yulingtianxia.com/blog/2016/01/17/search-for-similar-images/

## LICENSE

The MIT License.
