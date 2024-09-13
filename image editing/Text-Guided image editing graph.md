# Text-Guided image editing

## P2P

算法无需训练即可实现编辑，但存在无法直接编辑真实图像，且编辑过程仅能通过对给定文本描述的增加删除以及替换做编辑。

### Null-text Inversion for Editing Real Images using Guided Diffusion Models

解决了P2P无法直接在真实图像上使用的问题，并为DDIM反演提升了效果。

### InstructPix2Pix Learning to Follow Image Editing Instructions

使用两个大模型生成训练数据，运用p2p生成编辑后的对应图像，训练模型。

## Localizing Object-level Shape Variations with Text-to-Image Diffusion Models

根据不同时间段的提示改变以改变object的shape。不同时间段的扩散过程对图片整体的布局或个体的生成起到不同的控制作用。

Focus on Your Instruction Fine-grained and Multi-instruction Image Editing by Attention Modulation
