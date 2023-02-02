## Code structure

- `cartoonX.py` source code of CartoonX implementation
- `create_lambda_data.py` script to create lambda data for Figure 7c. Should probably be moved to a `cartoonx/run_scripts` folder.
- `hparams.py` hyperparameters used by `main.py`
- `imagenet_labels.txt` labels for imagenet
- `main.py` main script to produce explanations with CartoonX and Pixel RDE
- `pixelRDE.py` source code of Pixel RDE implementation

## How to run
From the main directory, run the following command(s) to produce the data that is needed for the experiments:
```
python cartoonx/create_lambda_data.py # To produce the data for Figure 7c
```
Edit: don't run the above comment unless you know what you are doing! Otherwise you would overwrite some data
