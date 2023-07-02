# nnhw_final

模型参数保存 百度云网盘链接: https://pan.baidu.com/s/1InVsFOPj4gaKNG8m6PBlfw?pwd=tkxt 提取码: tkxt

# final 1
```
run train.ipynb
run test.ipynb
```
# final 2
```
run ViT.ipynb
```

# final 3
NeRF代码的运行

先按要求配置环境

```
pip install -r requirements.txt
```

下载样例数据集：lego和fern

```
bash download_example_data.sh
```

训练一个低残差的NeRF：

```
python run_nerf.py --config configs/lego.txt
