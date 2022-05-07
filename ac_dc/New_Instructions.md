### Turkish Modifications

In order to use the new modifications for Turkish and the current dataset, the following should be done. First, the sentencepiece json file, the kenlm model, and the fasttext lid176 (language identification with 176 languages) should all be in the ac_dc folder. 

In the clean_dataset.py file, you can change the dataset in the main function to be whatever the desired dataset is. This can be a dataset on the computer, or a huggingface dataset. 