## 超级马利奥闯关A3C
使用A3C算法训练AI通关马里奥小游戏。

### 使用流程如下

conda新建虚拟环境，安装库 `pip install -r requirements.txt`

版本要和 requirements.txt 中一致（pytorch 1.11.0，gym 0.21.0）

```python
python train.py  # 训练模型
python test.py  # 测试模型 
```

output文件夹保存了测试视频

训练成功示例
```
Process 0. Episode 0
Process 0. Episode 1
Process 0. Episode 2
Process 0. Episode 3
Process 0. Episode 4
Process 0. Episode 5
Process 0. Episode 6
Process 0. Episode 7
Process 0. Episode 8
```

测试成功会出现马里奥闯关的视频