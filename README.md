# Lite3D
This is a project to detect anomaly behaviors of underwater creatures.

## Environment
<ul>
<li>python >= 3.6.9</li>
<li>CUDA >= 10.2</li>
<li>cuDNN >= 7.5.6</li>
</ul>

## Requirements
see requirements.txt

## RawDataSet
The raw dataset generated and/or analyzed during the present study are now [available](http://140.121.135.204/aicenter/publications.html), under the repository name of Anomaly Behavior Recognition of underwater creatures Using Lite 3D Full-Convolution Network.

## Npz File
The <b>npz file</b> can be [downloaded](https://drive.google.com/drive/folders/1CrsJNDQt15mAr9f8085Guj9KktJhkx7Z?usp=share_link) or generated by train.py, placed in the following path.
<pre>
─ .idea/
─ asset/
─ utils/
─ LoadData.py
─ imgto3d.py
─ requirements.txt
─ <b>mix_fishaction_screen_v04_7_10_True.npz</b>
─ train.py
─ ...
</pre>

## Train
You can train your model with train.py\
`python train.py  --output mix_fars_v04_result/`

If yuo want to change loss function\
`python train.py  --output mix_fars_v04_result/ --loss focal`

## Acknowledgements
This work was supported in part by the Center of Excellence for the Oceans (CEO), National Taiwan Ocean University, in part by the Center of Excellence for Ocean Engineering (CEOE), National Taiwan Ocean University, in part by the AI Research Center, National Taiwan Ocean University, National Chengchi University, and in part by the National Science and Technology Council of Taiwan (NSTC) under Grants: NSTC 111-2634-F-019 -001, NSTC 110-2221-E-019 -062, and NSTC 111-2221-E-019 -072.
