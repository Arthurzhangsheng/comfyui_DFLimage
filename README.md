# comfyui_DFLimage
在comfyui中处理deepfacelab的素材图片处理工具包，保留DFL内嵌的图片meta信息

在原有WAS_Node_Suite的基础上修改了单张图片读取、批量读取图片和保存图片的节点，额外支持读取与保存图片中deepfacelab相关信息

使用时注意保存图片的尺寸需要和原始图片一致，并且格式为jpg，才能正确导入dfl原信息

![使用示意](https://github.com/Arthurzhangsheng/comfyui_DFLimage/blob/main/assets/example.png)
