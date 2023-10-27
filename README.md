# Keywords Best Represent the Account (KBRA)

<b>KBRA</b> generates best keywords of Instagram posts. It crawls photos and classify labels to determine which keyword best represents each account. 
We adopt CLIP model for zero-shot image classification. KBRA can be used for Instagram hashtag recommendation system.


## OUR CUSTOMIZATION

To give the model for appropriate Instagram hastags, we extend the labels description using the template "The instagram hashtag of this photo is" instead of "This is a photo of a".

For labels, we select top 523 hashtags from https://blog.hubspot.com/marketing/instagram-hashtags (removing duplicate tags).

The result recommends user 5 best hashtags for a photo. 

* CLIP model from Intel Open Model Zoo
https://github.com/openvinotoolkit/open_model_zoo/tree/master

* Notebook file from 228-clip-zero-shot-image-classification
* Pretrained model from openai/clip-vit-base-patch16
* Zero-shot learning
* Open AI
