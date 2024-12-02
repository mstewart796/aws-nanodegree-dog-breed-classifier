
# Image Classification for a City Dog Show

This is an image classifier created as part of my AWS AI Nanodegree program to classify dogs and non-dogs, and within that dog breeds. It is a command line program made up of various .py files which can be found in the *data* folder.


## Funcionalities

- Classification between dog and non-dog
- Classification between breeds
- Results gathered and analysis saved to file
- Three models tested: alexnet, resnet and vgg

## How to use

Place the images you would like to categorize in the *data\uploaded_images* folder (you may delete my personal images that I used) then run one of the following three command lines (make sure you are in the *data* folder in your terminal!):

- `python check_images.py --dir data/uploaded_images/ --arch resnet  --dogfile dognames.txt > resnet_uploaded-images.txt`
- `python check_images.py --dir data/uploaded_images/ --arch alexnet --dogfile dognames.txt > alexnet_uploaded-images.txt`
- `python check_images.py --dir data/uploaded_images/ --arch vgg  --dogfile dognames.txt > vgg_uploaded-images.txt`

  The results will then be found in one of the corresponding files:
  
- `data\alexnet_pet-images.txt`
- `data\resnet_pet-images.txt`
- `data\vgg_pet-images.txt`

*NOTE*

You may wish to delete the content of these files before running the command lines as they currently include my results!


## References

 - [Udacity](https://www.udacity.com/)
 - [AWS AI Programming with Python](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089?promo=year_end&coupon=JULY4&utm_source=gsem_generic&utm_medium=ads_r&utm_campaign=20960322867_c_individuals&utm_term=161066723234&utm_keyword=ai%20programming%20with%20python_p&utm_source=gsem_generic&utm_medium=ads_n&utm_campaign=20960322867_c_individuals&utm_term=161066723234&utm_keyword=ai%20programming%20with%20python_p&gad_source=1&gclid=Cj0KCQjws560BhCuARIsAHMqE0HmBa3LOKQFIsLuPBAjJbFwJJwitNIZPeFQAIL43xoceke-JQbZ7L4aAlrBEALw_wcB)

