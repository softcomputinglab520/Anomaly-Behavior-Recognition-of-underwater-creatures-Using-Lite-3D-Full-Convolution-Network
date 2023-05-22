# Lite3D
This is a project to detect anomaly behaviors of underwater creatures.

##Environment
<ul>
<li>python >= 3.6.9</li>
<li>CUDA >= 10.2</li>
<li>cuDNN >= 7.5.6</li>
</ul>

##Requirements
see requirements.txt

##DataSet
The raw dataset generated and/or analyzed during the present study are now available and can be accessed through the link: http://140.121.135.204/aicenter/publications.html, under the repository name of Anomaly Behavior Recognition of underwater creatures Using Lite 3D Full-Convolution Network.

##Train
You can train your model with train.py\
`python train.py  --output mix_fars_v04_result/`

If yuo want to change loss function\
`python train.py  --output mix_fars_v04_result/ --loss focal`

##Acknowledgements
This work was supported in part by the Center of Excellence for the Oceans (CEO), National Taiwan Ocean University, in part by the Center of Excellence for Ocean Engineering (CEOE), National Taiwan Ocean University, in part by the AI Research Center, National Taiwan Ocean University, National Chengchi University, and in part by the National Science and Technology Council of Taiwan (NSTC) under Grants: NSTC 111-2634-F-019 -001, NSTC 110-2221-E-019 -062, and NSTC 111-2221-E-019 -072.
