# Sorting the first layer 
Created: Feb 20, 2021
> In this directory, I experiment with sorting the data before feeding it into the neural network. In other words, the first layer of neurons are sorted. Specifically, I use the MNIST dataset and sort by row array--not the entire image.
> 



## Variable that is being tested:

What happens if we sort the first input layer of a neural network? Would accuracy improve? What happens if we sort from greatest to least vs. least to greatest? 

**Research question**: Can statistically-learned inference for image classification transfer across a uniform redistribution of pixels?  

---

## Data Analysis

Take this data point of a 5 in the MNIST dataset: 

![five](https://user-images.githubusercontent.com/57341225/114344718-53b36a00-9b2e-11eb-9cde-b9a3a3343201.png)

Now see what happens when we apply a uniform redistribution of pixels by sorting the pixel values in the image row-wise: 

![Sorting%20first%20layer%20of%20neural%20network%2014bba065b3bb4dcc85c98d1ebdfccf1a/Untitled%201.png](Sorting%20first%20layer%20of%20neural%20network%2014bba065b3bb4dcc85c98d1ebdfccf1a/Untitled%201.png)
