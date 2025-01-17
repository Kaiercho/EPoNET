EPoNET: An Efficient Point Network for LiDAR Point Cloud Perception in Large-scale Scene
### Installation
```shell script
# create new conda environment
conda create -n env python=3.7 -y
conda activate env

# install pytorch
conda install pytorch==1.5.0 torchvision cudatoolkit=10.1 -c pytorch -y
#my log: url: https://download.pytorch.org/whl/torch_stable.html whl的pytorch-1.10.0&torchvision-0.11.2
#cu111/torch-1.10.0%2Bcu111-cp37-cp37m-linux_x86_64.whl + cu111/torchvision-0.11.2%2Bcu111-cp37-cp37m-linux_x86_64.whl
#url： https://pytorch-geometric.com/whl/  --torch-1.10.0+cu111  --https://pytorch-geometric.com/whl/torch-1.10.0%2Bcu111.html
#whl：
#torch_scatter-2.0.9-cp37-cp37m-linux_x86_64.whl
#torch_sparse-0.6.12-cp37-cp37m-linux_x86_64.whl
#torch_cluster-1.6.0-cp37-cp37m-linux_x86_64.whl
#torch_spline_conv-1.2.1-cp37-cp37m-linux_x86_64.whl
pip install torch-geometric
pip install pyyaml
# install pytorch-geometric  url:https://pytorch-geometric.com/whl/torch-1.10.0%2Bcu111.html
#export CUDA=cu101
#pip install torch-scatter==latest+${CUDA} -f https://pytorch-geometric.com/whl/torch-1.5.0.html
#pip install torch-sparse==latest+${CUDA} -f https://pytorch-geometric.com/whl/torch-1.5.0.html
#pip install torch-cluster==latest+${CUDA} -f https://pytorch-geometric.com/whl/torch-1.5.0.html
#pip install torch-spline-conv==latest+${CUDA} -f https://pytorch-geometric.com/whl/torch-1.5.0.html
#pip install torch-geometric

# install other dependencies
pip install pyyaml
```
