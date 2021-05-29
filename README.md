# studyPytorch
linux安装

which python 查看当前命令行键入 python 后运行的python路径
（whereis python 可以查看所有python的路径）


清华大学开源软件镜像站 下载
https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/

安装
chmod +x Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh


配置环境
vim ~/.bashrc


export  PATH="/home/xyz/miniconda3/bin:"$PATH
alias condapython="/home/xyz/miniconda3/bin/python3.7"


export PATH="/usr/bin:"$PATH #保持原有python最先被检索到，从而不先运行conda中的python
alias python="/usr/bin/python2.7"



/home/xyz/miniconda3/bin/python3.7



source ~/.bashrc 

conda init
conda activate base 进入conda 创建的python环境
conda deactivate 退出conda环境

conda list 

conda install pytorch torchvision cudatoolkit=10.0
