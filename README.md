# Emotic_with_attention

### Data preprocessing

- Download emotic.zip and annotations.zip and arrange the following folder structure.
```
├── ...
│   ├── emotic
│   |    ├── ade20k
│   |    ├── emodb_small
│   |    ├── framesdb
│   |    ├── mscoco 
│   ├── Annotations
│   |    ├── Annotations.mat
```
- To convert annotations from mat object to csv files and preprocess the data:

```
> python mat2py.py --data_dir proj/data/emotic19 --generate_npy
```
- Use the generated preprocessed data or the preprocessed data from the drive link
- Define data_src like: data_src = './drive/MyDrive/emotic/dataset/' in the notebook cell to use the data

## Reference
- https://github.com/Tandon-A/emotic
- https://github.com/ndkhanh360/CAER/blob/93d25828ce2ea050fb379d85258ba3fdbf59d2a6/CAER/model/model.py
