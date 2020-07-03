# Dog-Image-Classifier-Udacity
I worked on pieces of code on this image classifier as part of my first project on Udacity's 'AI Programming with Python Nanodegree Program'

Please note that this project has features that may differ from other project submissions. To start with, the intended way to run the code, is to first run 'run_models_batch.sh' or 'run_models_batch_uploaded.sh' and then 'final_result_printer.py'. 'final_result_printer' will ask you if you want to print the results from your own images or from the ones on the predetermined library. After runing both of these files, 'vgg_pet-images.txt', 'alexnet_pet-images.txt' and 'resnet_pet-images.txt' (alternatively 'vgg_pet-images.txt', 'alexnet_pet-images.txt' and 'resnet_pet-images.txt') will have been created and a table of the results of each model will be printed.

Results with predetermined image library: It can be seen, that VGG outperformed every other model; with VGG and and AlexNet being able to differentiate a dog from a not-dog 100% of the time and VGG being able to correctly determine the breed of the dog 93.3% of the time (highest percentage).

The code can also be used for one model at a time. In this case 'check_images.py' should be run using command line arguments. Furthermore, the command-line argument --ask has been added. It is of boolean type and takes False as the default value. If ask is True, the code will stop to ask the user if it wants information about misclassified images to be printed or not (only works for 'check_images.py').
