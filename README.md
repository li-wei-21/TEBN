# TEBN
2022NIPs-《Temporal Effective Batch Normalization in Spiking Neural Networks》  
openview上zip里面的代码  
如有侵权立删
# Requirements
spikingjelly==0.0.0.0.12  
torchvision>=0.12.0+cu113  
torch>=1.11.0+cu113  
numpy==1.21.5  
# Usage
To run a pre-trained model 'TEBN_VGG9.pth' on CIFAR-10, please run the following script:  
python main.py -resume ./TEBN_VGG9.pth
