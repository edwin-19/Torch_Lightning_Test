# Torch Lighthing Test
The following repo was to test out a few concepts of pytorch lighthing, and run a few algorithms to gain a general understanding of pytorch as well as the lighthning components

# Takeaways
- Pretty similar to keras in terms of coding style
- pl.lighthing_module inherits a nn.module class, so things like moving model to gpu and so on applies here as well
- Trainer class does a majority of the boiler plate code for you

# ToDO
- [x] Image Classifier
- [x] Transfer Learning
- [x] Simple Text Classification
- [x] Bert With Torch Lighthing
- [ ] Use datasets api from huggingface to process datasets
- [ ] Use trainer class from huggingface to train model - Distilbert