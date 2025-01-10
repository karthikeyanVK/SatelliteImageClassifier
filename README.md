# Workshop for Nvid & Satellite Image Classification

Prerequisites for the workshop

- Clone this repo to google colab, we will working in google colab in this workshop

- Open and  start working on the copyFiles2YourDrive.ipynb to copy satellite Images to your google drive for exercise

# Notebook - Nvid

- Add the code from the given reference and run the cell.

- If the code already exists, please run the code and move to the next cell.

## Install rasterio which is used for NVID Calculation

![alt text](media/nvid/image.png)

## Run cell 2, 3, 4

![alt text](media/nvid/image-7.png)


## Open the files for band fetch

![alt text](media/nvid/image1.png)

# Check band4 height and width

![alt text](media/nvid/image-1.png)


#Visualize the band4 region using plot

![alt text](media/nvid/image-2.png)

# Visualize the multiple band 

![alt text](media/nvid/image-3.png)

Plot the same in the crs band.

![alt text](media/nvid/image-4.png)

# Satelite Data Image Classification - Deep Learning

- Open and  start working on the satelliteImageClassification.ipynb to identify Cloud, Desert, Water, GreenArea

## Run the import and drive import cell

![alt text](media/satimageclassify/image-1.png)


## Load dataset and split into training and validation sets

![alt text](media/satimageclassify/image.png)

# Display the first few images in training Dataset

![alt text](media/satimageclassify/image-2.png)

# Display the first few images in validation Dataset

![alt text](media/satimageclassify/image-3.png)

## Print the number of land areas available for classification

![alt text](media/satimageclassify/image-5.png)

# Name those classes

![alt text](media/satimageclassify/image-6.png)

# Define the CNN with layers needed for Classification training

![alt text](media/satimageclassify/image-7.png)

## Compile the Model
![alt text](media/satimageclassify/image-9.png)

## Fit the model
![alt text](media/satimageclassify/image-8.png)

## Display Summary

![alt text](media/satimageclassify/image-10.png)

## Run the below cells to find the prediction accuracy

![alt text](media/satimageclassify/image-11.png)

## Predict one Image from the validation Dataset

![alt text](media/satimageclassify/image-12.png)



