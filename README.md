# SageMaker

SageMaker Studio Lab project     
https://studiolab.sagemaker.aws/         

## CPU环境  

 - Ubuntu 20.04.3 LTS  
 - 内核 4.14
 - Python 3.9.7   
 - Intel(R) Xeon(R) Platinum 8259CL CPU @ 2.50GHz 4个
 - 双核心CPU
 - 16G内存
 - apt list: apt、gcc、g++、git、wget、unzip、tar、make、dpkg，无root权限安装
 - pip正常
 - conda 4.10.3
 - tensorflow gpu 2.7.0
 - pytorch 1.10
 - 目录 /home/studio-lab-user/sagemaker-studiolab-notebooks/SageMaker
 - 空间剩12G /dev/nvme1n1     25G  7.0G   19G  28% /home/studio-lab-user
 
## GPU环境

 - Cuda compilation tools, release 11.2, V11.2.152
 - Build cuda_11.2.r11.2/compiler.29618528_0
 - NVIDIA-SMI 470.57.02    Driver Version: 470.57.02    CUDA Version: 11.4
 - 15109MiB  16G显存

## conda

 - conda -V
 - conda list
 - conda deactivate 退出studiolab环境
 - conda env list (studiolab装了 tensorflow gpu 和 torch)
 - conda create xxx
 - conda activate xxx
 - conda install 
 - 等同于 pip 加 virtualenv 
 
## 另外的空间

 - /dev/nvme0n1p1   50G   14G   37G  28% /opt/.sagemakerinternal
 - /opt/.sagemakerinternal/default/wwk
 - ngrok-stable-linux-amd64.tgz
 - 无法使用，重启丢失
 - 测试token