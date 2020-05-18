# Active-Learning-Release
AL_synthetic_data.py:   
-unique, set the uniqueness of the synthetic data. eg. to set a uniqueness of 50%, run AL_synthetic_data.py -unique 0.5  
-responsive, set the responsiveness of the synthetic data. eg. to set a responsiveness of 50%, run AL_synthetic_data.py -responsive 0.5
-adjustment, default is on. If specified, the model will be without the confidence adjustment. eg. AL_synthetic_data.py -adjustment  
-random, default is off. If specified, the simulation will run using both active learner and random learner  
-strategy, to set the query strategy of the active learner. There are 3 choices: "hybrid", "entropy" and "score". eg. run AL_synthetic_data.py -strategy "hybrid"  

AL_real_data.py:  
-adjustment, default is on. If specified, the model will be without the confidence adjustment. eg. AL_real_data.py -adjustment  
-random, default is off. If specified, the simulation will run using both active learner and random learner  
-strategy, to set the query strategy of the active learner. There are 3 choices: "hybrid", "entropy" and "score". eg. run AL_real_data.py -strategy "hybrid"  
