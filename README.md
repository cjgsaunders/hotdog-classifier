# hotdog-classifier

Inspired by the Silcone Valley episode where they create "The Shazzam for food".

My goal was to learn python Fast.ai and pytorch by training and deploying an image classifier.
This is a simple transfer learning project. 
This model takes the Pretrained ResNet model and re-trains it on 200 pictures scraped from google images. 
It is a binary classifier for hotdog or not a hotdog.
It has seen 100 hotdogs and then 10 pictures X 10 random objects.

It performs supprisingly well for the small amount of data used in training.
This poject was just for fun.
For a more rigerous model more training and validation metrics are needed.
