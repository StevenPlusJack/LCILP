# Clust-LP: Exploiting Local Clustering for Inductive Link Prediction in Knowledge Graphs

To start training the model, run the following command:
- python train.py -d WN18RR_v1 -e grail_wn_v1

To test the model, run the following commands:
- python test_auc.py -d WN18RR_v1_ind -e exp_wn_v1
- python test_ranking.py -d WN18RR_v1_ind -e exp_wn_v1
