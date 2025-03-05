# TSEspkaug
a speaker augmentation method used for target speaker extraction

## 环境设置
请确保已安装所需的Python库，可以使用以下命令安装：
```bash
pip install -r requirements.txt
```

## 训练模型
要训练模型，请运行以下命令：
```bash
bash run.sh
```
这将执行`run.sh`脚本中的训练部分。

## 测试模型
要测试模型，请取消注释`run.sh`脚本中的测试部分，并运行以下命令：
```bash
bash eval.sh
```
这将执行`run.sh`脚本中的测试部分。
