# 3D_modeling


### TensorFlow: Blas GEMM launch failed

```python 
configuration = tf.compat.v1.ConfigProto()
configuration.gpu_options.allow_growth = True
session = tf.compat.v1.Session(config=configuration)
```
```python
gpu_options = tf.GPUOptions(per_process_gpu_memory_fraction=0.9)

tf.Session(config=tf.ConfigProto(gpu_options=gpu_options,allow_soft_placement=True)
```
Install pytorch
```
conda create --name nerf python=3.7

pip install torch==1.13.1+cu117 torchvision==0.14.1+cu117 torchaudio==0.13.1 --extra-index-url https://download.pytorch.org/whl/cu117

pip
临时使用
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package

pip install opencv-python
```
