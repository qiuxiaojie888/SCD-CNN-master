## SCD-CNN: Hyperspectral image denoising via Self-modulated cross-attention deformable convolutional neural network


### Installation
* Install dependencies:
```bash
pip install -r requirements.txt
```
### Train and Test
* Put your data into the 'datasets' directory 
* Creat train and val patches:
```bash
python get_patch_wdc.py
```
* Creat test data:
```bash
python get_patch_wdc_test.py
```
* Open the model directory in terminal
* Set python environment
* Train example:
```bash
python .\train.py --config-file .\gauss_25_config.yaml
```
* Test example: 
```bash
python .\predict.py --config-file .\gauss_blind_config.yaml
```
