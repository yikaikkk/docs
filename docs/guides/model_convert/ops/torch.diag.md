## torch.diag
### [torch.diag](https://pytorch.org/docs/stable/generated/torch.diag.html?highlight=diag#torch.diag)

```python
torch.diag(input,
           diagonal=0,
           *,
           out=None)
```

### [paddle.diag](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/diag_cn.html)

```python
paddle.diag(x,
            offset=0,
            padding_value=0,
            name=None)
```

其中 Paddle 相比 Pytorch 支持更多其他参数，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input         | x            | 表示输出的 Tensor。               |
| diagonal      | offset       | 对角线偏移量。正值表示上对角线，0 表示主对角线，负值表示下对角线。                |
| -             | padding_value| 表示填充指定对角线以外的区域，PyTorch 无此参数，其用 0 填充。               |
