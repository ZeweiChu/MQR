# MQR

## Train Data

- The training data can be downloaded from: https://drive.google.com/drive/folders/1VZ7BusNjbulG9xYlcbGmip5Pl-Gzo8HD?usp=sharing

## Dev/Test Data and Model Predictions

- The dev and test datasets are under directory ```data```
- The rewritten dev/test splits can be found under each subdirectory of ```data```

## Annotation

- All annotations on the DEV/TEST splits described in the paper can be found at https://docs.google.com/spreadsheets/d/1uPDhGzxia2T0t9WXjMDuopAtgk6CceZ1U3mrDFNI4cY/edit?usp=sharing

## License

The MQR dataset is under cc-by-sa 4.0 license, intended to be shared and remixed. 
- https://creativecommons.org/licenses/by-sa/4.0/

The MQR dataset is partially constructed from the Stack Exchange data dumps 
- https://archive.org/details/stackexchange

We used Quora Question Pairs dataset as part of the training data
- https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs
- https://www.quora.com/about/tos

We also used the Paralex dataset for training
- http://knowitall.cs.washington.edu/paralex/




## Reference

```
@inproceedings{chu-mqr-20,
  author    = {Zewei Chu and Mingda Chen and Jing Chen and Miaosen Wang and Kevin Gimpel and Manaal Faruqui and Xiance Si},
  title     = {How to Ask Better Questions? A Large-Scale Multi-Domain Dataset for Rewriting Ill-Formed Questions},
  booktitle = {Proc. of {AAAI}},
  year      = {2020}
}
```
