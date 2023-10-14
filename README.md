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
