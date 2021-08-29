# Annotations

Table of contents:

1. TOC
{:toc}

In this post I will write everything that I feel is important or that I will need in the future

## Chapter 2

- Random seed -> computers don't really know how to creat random numbers but they simply know how to creat lists of numbers that look random so we provide the same starting point each time - called *seed* so that we get the exact same list each time.
- Images don't go one by one to the model but rather in groups called *mini-batch* which are then grouped into a big array called *tensor* (fastai will make tensor 64 bytes by default).
- It is best to train a simple and fast model, and then deal with image label errors, then to build a complex and time consuming one.
- When exporting a model to use in a online application we need to extract the architecture as well as the trained parametres.
- Consider reading -> [*Building Machine Learning Powered Applications by Emmanuel Ameisen*](https://www.amazon.com/Building-Machine-Learning-Powered-Applications/dp/149204511X).

## Chapter 3

- This chapter was super intriguing and very complicated and because the topic was more about personal thinking, so there isn't much of annotations.
- Authors please change the line about *Technology is power* at page 115 to the Spider-Man uncle Ben Quote.
- Check out -> [*An Ethical Toolkit for Engineering/Design Pratice*](https://oreil.ly/vDGGC).

## Chapter 4

- Stochastic Gradient Descent(SGD)-> Learning by updating weights automatically.
- Have a Baseline: can be a simple solution made by you so you can compare with future improvements or download a similar idea/work that other people formulated so you can have an ideia of what is expected.
- Tensor: Rank= number of axes or dimensions; Shape= size of each axis of a tensor.
- Figure 4-1 -> Just perfection.
- In deep learning "gradient" usually means the value of a functions derivative at a partucular argument value.
- Learning Rate(LR)- is often a number between 0.001 and 0.1. Usually some courses/websites have some difficulty explaining, but in the book it is very well explained.
