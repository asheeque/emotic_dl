# emotic_dl

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
