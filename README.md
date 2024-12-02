# conda-operation
有关conda的指令
* 创建虚拟环境,python版本根据需要自己定
```
conda create -n <环境名> python=3.6
```
* 在虚拟环境中切换python版本
```
conda install python=3.8
```
如果在安装过程中遇到问题
可以先使用
```
conda uninstall python
```
然后再安装
* 激活环境
```
conda activate <环境名>
```
* 退出环境
```
conda deactivate
```
