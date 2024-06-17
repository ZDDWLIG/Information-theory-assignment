# Neural Style Transfer


## 文章及算法
https://arxiv.org/pdf/1508.06576

## pytorch实现
https://github.com/gordicaleksa/pytorch-neural-style-transfer/tree/master

## 关于VGG
https://medium.com/@siddheshb008/vgg-net-architecture-explained-71179310050f

## 作业内容
1. 复现（跑通）neural style transfer 的pytorch版本，如果没有GPU，可以生成很小的image height,但是小的height分辨率会低。
2. 使用自己的style和content(非自带的图片)生成一幅style transfer的图片
hint：如果效果不理想，可根据github上面的描述，调整content_weight、style_weight、tv_weight
3. 通过对代码进行调整，尝试实现 两个style 和 1个content 的style transfer，即生成的图像需要兼顾2种风格和1种内容。也就是说，额外增加一个style输入。
hint: 可以考虑对两个style得到的target_style_representation进行操作。
