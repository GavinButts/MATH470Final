# MATH470 Final  
#### By Gavin Butts and Ava Hoeger  

In this repository, we seek to determine whether full finetuning or LoRA results in higher performances. We see that, despite LoRA's computational efficiency, full finetuning performs best. The evaluation results are provided below.  

#### Baseline
*accuracy*: 0.3382  
*precision*: 0.1144  
*recall*: 0.3382  
*f1*: 0.1710  

#### Full Fine Tuning  
*accuracy*: 0.9065  
*precision*: 0.9066   
*recall*: 0.9065  
*f1*: 0.9065  

#### LoRA
*accuracy*: 0.8815  
*precision*: 0.8814  
*recall*: 0.8815  
*f1: 0.8814 


## Running the code  
To run the training blocks, no prior installations are required. Simply run the code from start to finish. To run the evaluation or inference, you must move the model parameters and config files to a repository in your Google Drive. Once you have done this, simply change the file directories to match your own.  

The model parameters and config files can be found here: <https://drive.google.com/drive/folders/1r2k3OW8JLhuOAF7_OZ_jnkGtdpubsNJ3?usp=share_link>

The dataset and documentation can be found here: <https://nlp.stanford.edu/projects/snli/>

The Google Slides version of the presentation can be found here: <https://docs.google.com/presentation/d/1691tKb8vVmjO9lOeFGLFI6Mi3vwkcSS9BsCCDhB7ZZc/edit?usp=sharing>

