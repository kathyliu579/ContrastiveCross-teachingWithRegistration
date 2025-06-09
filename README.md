# ContrastiveCross-teachingWithRegistration
The codes for the work "Learning Semi-Supervised Medical Image Segmentation\\from Spatial Registration"[https://ieeexplore.ieee.org/abstract/document/10096379], which is accepted by WACV 2025.


## 1. Prepare data

- The datasets we used are provided by TransUnet's authors. Please go to ["./datasets/README.md"](datasets/README.md) for details, or please send an Email to jienengchen01 AT gmail.com to request the preprocessed data. If you would like to use the preprocessed data, please use it for research purposes and do not redistribute it (following the TransUnet's License).

## 2. Environment

- Please prepare an environment with python=3.7, and then use the command "pip install -r requirements.txt" for the dependencies.

## 3. Train/Test

- Run the train script on synapse dataset. The batch size we used is 24.

- Train

```bash
sh my_train.sh 
```

- Test 

```bash
sh my_test.sh 
```

## References
* [TransUnet](https://github.com/Beckschen/TransUNet)
* [SwinTransformer](https://github.com/microsoft/Swin-Transformer)
* [SwinUnet](https://github.com/HuCaoFighting/Swin-Unet)

## Citation
@inproceedings{liu2025learning,
  title={Learning Semi-Supervised Medical Image Segmentation from Spatial Registration},
  author={Liu, Qianying and Henderson, Paul and Gu, Xiao and Dai, Hang and Deligianni, Fani},
  booktitle={2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
  pages={6383--6393},
  year={2025},
  organization={IEEE}
}

# CS-Unet
