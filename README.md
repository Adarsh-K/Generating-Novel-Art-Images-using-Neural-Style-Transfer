# I've made a CNN which generates novel artistic images using an algorithm called Neural Style transfer. The code is in Python and uses TensorFlow.(To see an example image open output folder)
Note: All the files are well documented and commented wherever I felt necessary

## To see the Generated image open generated_image.jpg in output folder
## To see the code open ArtGenerationwithNeuralStyleTransfer.ipynb

Run the file named ArtGenerationwithNeuralStyleTransfer.ipynb which does the following:
1. Loads the VGG-19 model pre-trained on a large dataset of ImageNet(I can't upload the pre-trained model as it's very big in size, but one can easily find it by a simlple Google search;)
2. Computes the Content cost
3. Computes the Gram matrix which is later used to find the Style cost
4. Computes the Style cost from several layers
5. Initialises the generated image as a Noisy Image
6. Creates the TF Graph
7. Outputs the generated image in folder-output
