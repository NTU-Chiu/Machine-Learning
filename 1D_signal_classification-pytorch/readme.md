# 使用CNN模型分類損壞&健康的軸承
* Using machine learning to classify different bearing damage situation. <br />
## Process
  <img src = "https://github.com/NTU-Chiu/ML_Projects/assets/91785016/cc796268-6194-4aae-b341-00f6b5a72d49">

## Results
* 100 % accuracy (in 600 testing samples)

## Technique
* Preprocessing:
  Using Fast Fourier Transform to transform the time domain signals to frequency domain signals. <br />
  <img src = "https://github.com/NTU-Chiu/ML_Projects/assets/91785016/6a7cf491-3c19-4dde-be22-6489a265dca6.png" width = "250" height = "250">
* Model:
  Using 1D CNN to extract fearures of signals.  <br />
  ![image](https://github.com/NTU-Chiu/ML_Projects/assets/91785016/a4da5184-2b65-489c-a277-58e3632a534b)

# Reference:
* This project is the final project of diginal signal processing class at NTU.
* The dataset is private.
* This code is referenced from the TA, Bo Han Kung.
