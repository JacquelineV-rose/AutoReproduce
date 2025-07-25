## Data Preparation

All the datasets are included in the [reproducebench.tar.gz](https://huggingface.co/datasets/ai9stars/ReproduceBench/blob/main/reproducebench.tar.gz). 
You need firstly download and decompress the data.
The overall file structure after decompressing is as follows:
```
PreproduceBench
|-- PreproduceBench
    |-- itransformer
        |-- source/ # contain the dataset
        |-- dataloader.py
        |-- run_itransformer.py
    |-- lsm
        |-- source/ # contain the dataset
        |-- dataloader.py
        |-- run_itransformer.py
    ...
```