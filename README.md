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

