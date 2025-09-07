# DeepSHAP Summary

This GitHub is about "Effective Adversarial Example Detection with DeepSHAP Summary" (under review), and includes advanced approaches from  "DeepSHAP Summary for Adversarial Example Detection".

```python
@INPROCEEDINGS{10190801,
  author={Lin, Yi-Ching and Yu, Fang},
  booktitle={2023 IEEE/ACM International Workshop on Deep Learning for Testing and Testing for Deep Learning (DeepTest)}, 
  title={DeepSHAP Summary for Adversarial Example Detection}, 
  year={2023},
  volume={},
  number={},
  pages={17-24},
  doi={10.1109/DeepTest59248.2023.00010}}
```


## Phase
![image](https://github.com/YiChingLLin/DeepSHAP_summary/blob/main/img/Phase.png)

- Decision Logic Approach Process: Phase1_Data_Collection -> Phase2_3_SHAP_Path_Exaction (generate_attack_layer(approach = 'path')) -> Phase2_3_Detection
- Best-Layer SHAP Signature Approach Process: Phase1_Data_Collection -> Phase4_Path_Astraction -> Phase2_3_SHAP_Path_Exaction (generate_attack_single) -> Phase2_3_Detection
- Activation Status Approach Process: Phase1_Data_Collection -> Phase4_Path_Astraction -> Phase5_Data_Activation -> Phase2_3_Detection

## Environment
- matplotlib 3.6.2
- numpy 1.23.5
- pandas 1.5.1
- python 3.9.13
- scikit-learn 1.1.3
- [shap](https://github.com/slundberg/shap) 0.41.0
- torch 1.13.0+cu117
- torchvision 0.14.0+cu117
- [torchattacks](https://github.com/Harry24k/adversarial-attacks-pytorch) 3.3.0