# Text-Guided image editing

## P2P

算法无需训练即可实现编辑，但存在无法直接编辑真实图像，且编辑过程仅能通过对给定文本描述的增加删除以及替换做编辑。

### Null-text Inversion for Editing Real Images using Guided Diffusion Models

解决了P2P无法直接在真实图像上使用的问题，并为DDIM反演提升了效果。