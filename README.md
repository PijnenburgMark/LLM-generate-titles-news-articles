In this project we take the 250000 short news articles from the Kaggle Dataset 'dutch-news-articles'. We set up a simple pipeline to fine-tune the flan-T5 transformer model to learn to generate titles for these news-articles based on the titles that are provided. In the end we check the quality of the generated titles manually.

My main intention is the provide a working pipeline, not to get the best possible results. For this reason I used the flan-T5 small model and use only 3 training epochs. Better results are to be expected with the large versions that are also available via the transformer package of python (and which are on Hugging Face).

I run the code on a server  having one GPU (RTX-2080) and the training lasted 2 hours, after which the model was able to generate some reasonable and some bad titles. 
