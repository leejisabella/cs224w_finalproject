# cs224w_finalproject
Graph á la Carte

Code is written in Jupyter Notebooks for easy integration with Google Colab. This repo contains 5 models for a restaurant recommender system built off of Google Restaurant data:
1) Base Model: LightGCN 
2) Extended Model 1: LightGCL 
3) Extended Model 2: LightGCL + Distance Awareness 
4) PinSage 
5) LightGCN + HGT Layer 

Data processing and cleaning is available in new_model.ipynb, while no_embeddings_final.ipynb contains the most updated versions of our model implementations without semantic embeddings. Models and results which use textual semantic embeddings are available in embeddings.ipynb.

Please see the following link for the data sources: https://drive.google.com/file/d/1CObpfsYBeAisbhS6fwXGEb5_wNPNnyUw/view?usp=sharing. This link contains both the full dataset as well as the subset. Note that we will use the subset for testing due to computational constraints. Processed datasets can be found at the following link: https://drive.google.com/drive/folders/1mI9jEhjXwF2EiZcc70CAbmgj3fc06M0Y?usp=sharing.
