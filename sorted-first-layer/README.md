# Sorting the first layer 
Created: Feb 20, 2021
> In this directory, I experiment with sorting the data before feeding it into the neural network. In other words, the first layer of neurons are sorted. Specifically, I use the MNIST dataset and sort by row array--not the entire image.
> 



## Variable that is being tested:

What happens if we sort the first input layer of a neural network? Would accuracy improve? What happens if we sort from greatest to least vs. least to greatest? 

**Research question**: Can statistically-learned inference for image classification transfer across a uniform redistribution of pixels? 

**Motivation**: If the research question is true, then in settings where the data that the models are being trained on needs to be private (e.g. healthcare), the original data doesn't need to be used, but rather the edited, sorted data. 

**Future**: Experimenting with other redistribution methods. 

---

## Data Analysis

Take this data point of a 5 in the MNIST dataset: 

![five](https://user-images.githubusercontent.com/57341225/114344718-53b36a00-9b2e-11eb-9cde-b9a3a3343201.png)

Now see what happens when we apply a uniform redistribution of pixels by sorting the pixel values in the image row-wise: 

![reshuffled-five](https://user-images.githubusercontent.com/57341225/114344805-7e052780-9b2e-11eb-909b-5c084ebe77a4.png)

---
Note: This experiment is a work-in-progress and is not done yet. More to come soon. 
