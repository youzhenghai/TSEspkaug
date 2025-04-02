# TSEspkaug
a speaker augmentation method used for target speaker extraction

##Environment settings
Please ensure that the required lib are installed, which can be installed using the following command:
```bash
pip install -r requirements.txt
```

##Training model
To train the model, run the following command:
```bash
cd egs/LibriMix/DPRNN_TSE/

chmod +x run.sh

bash run.sh
```
This will execute the training part in the 'run. sh' script.

##Test Model
To test the model, please uncomment the testing section in the 'run. sh' script and run the following command:
```bash
chmod +x eval.sh
bash eval.sh
```
This will execute the testing section in the 'run. sh' script.
