# Human Activity Detection 



## Dependancies 
. PyTorch
```
pip3 install torch==1.9.1+cu102 torchvision==0.10.1+cu102 torchaudio===0.9.1 -f https://download.pytorch.org/whl/torch_stable.html
```

. PyTorch Lightning
```
pip3 install pytorch-lightning
```
. Pytorch Video
```
pip3 install pytorch-video
```
## Usage

Use the Provided iPyNB file (HumanActivity.ipynb) to run the code.
Change the Directory of the dataset 

dataset should be of order<br>
> root<br>
>|<br>
>|-train<br>
>|-valid<br>

### DataSet used
Kinetics [DeepMind](https://deepmind.com/research/open-source/kinetics)
    
For the dataset use the code provided by [Showmax](https://github.com/Showmax/kinetics-downloader).



For my implementation I downloaded 10 videos for train set and 3 videos for test set for 2 classes ie 'zumba' and 'writing'. 

<hr>

## Contributor
[Atharva Kathale](https://www.github.com/Atharva-K12) 
 