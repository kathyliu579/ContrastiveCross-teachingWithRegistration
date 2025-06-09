# (CCT-R)ContrastiveCross-teachingWithRegistration
The codes for the work "Learning Semi-Supervised Medical Image Segmentation from Spatial Registration"[https://ieeexplore.ieee.org/abstract/document/10096379], which is accepted by WACV 2025.


## 1. Prepare data
The datasets we used are provided by TransUnet's authors. [Get processed data in this link] (Synapse/BTCV: https://drive.google.com/drive/folders/1ACJEoTp-uqfFJ73qS3eUObQh52nGuzCd and ACDC: https://drive.google.com/drive/folders/1KQcrci7aKsYZi1hQoZ3T3QUtcy7b--n4).

## 2. Environment

- Please prepare an environment with python=3.9, and then use the command "pip install -r requirements.txt" for the dependencies.

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
* [MCSC](https://github.com/kathyliu579/MCSC)

## Citation
@inproceedings{liu2025learning,
  title={Learning Semi-Supervised Medical Image Segmentation from Spatial Registration},
  author={Liu, Qianying and Henderson, Paul and Gu, Xiao and Dai, Hang and Deligianni, Fani},
  booktitle={2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
  pages={6383--6393},
  year={2025},
  organization={IEEE}
}

# CCT-R
