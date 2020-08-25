# Automatic image caption generator

This deep learning model is trained on the [flickr_8k dataset](http://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip). It uses n-gram model for text prediction and InceptionV3 for generating image embeddings. I have also used [ glove 6B 200d word embeddings](http://nlp.stanford.edu/data/glove.6B.zip) .

### performance on images from flickr-8k data-set
![N|Solid](https://i.ibb.co/HPx2nfV/Annotation-2020-08-25-210116.jpg)

![N|Solid](https://i.ibb.co/f1V892P/Annotation-2020-08-25-210046.jpg)



### performance on real world images
![N|Solid](https://i.ibb.co/MZHSR7g/Annotation-2020-08-25-205839.jpg)

![N|Solid](https://i.ibb.co/bW6NSDN/Annotation-2020-08-25-205907.jpg)

The trained model and tokenizers can be found inside the assets folder.

License
----

MIT


**Free Software, Hell Yeah!**
