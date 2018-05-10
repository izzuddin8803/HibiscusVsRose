

I try to apply what I learned from fastai course on flower dataset. I decide to try with 300 images of Roses and 300 images of Hibiscus since they are quite similiar in colour but different in shape. This notebook is written to test how accurate resnet34 is on these Roses and Hibiscus Dataset. I ran this model using google cloud platform as my personal pc has low GPU capabilties.

The accuracy of the model is very impressive at 93% after 2 epoch and become 96% after implementing image augmentation

Each type of flower is divided into train(200 image) and valid(100 image)

if there is an issue to view the ipnyb notebook, just view the pdf version. the pdf version by the way look messy  though
