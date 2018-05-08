

# Article 1

## How to create an account on GitHub and upload a sample project

### Creating a [GitHub](https://en.wikipedia.org/wiki/GitHub) Account
1.  Go to <https://github.com/> and *sign up* to create an account.
2.  Select a free plan and complete the process of sign up for GitHub.

### Creating a repository
A repository contains all the files and data related to the projects uploaded to it and the owner can modify access to the repository so that others can contribute to the project.

1. To create a repository, click on “**+**” sign on the top right of the homepage after you log in and select “**New repository**” from the drop-down menu.
2. Enter a name and description of your choice, select Public and **check the box** for initializing the repository with a README and then create the repository.

### Uploading a project
To upload your project, select Upload Files on the repository page, choose the files from your system and commit changes directly to the master branch.





___________________

# Article 2

## 1 x 1 CONVOLUTION

There are multiple dimensions of Kernel we can use in convolution for image processing. As we keep reducing the dimensions we tend to lose more information but they are faster than with the higher dimensions.

*Although 3 x 3 convolution is best for kernel convolution, there is still a need for 1 x 1 convolution as described below.*

1. 1 x 1 convolution is used for **feature merger, not a feature extractor** as it maps one to one pixel from input to output. 
2. They are just matrix multipliers and very cheap to make a model deeper.
3. Convolution like 3 x 3 is a linear classifier but if we add a 1 x 1 convolution in the middle of output, it will give a mini neural network and reduces dimensions over the image instead of the linear classifier.

*Eg:* If there is an image of 200 x 200 pixels, and if we do convolution of 1 x 1 by applying 32 filters, each filter of dimension 1 x 1 and 1 channel, will give output of dimension 200 x 200 with 32 channels.

![1x1 convolution](https://image.ibb.co/cAc7m7/1x1.png)



_____________________



-*Tripti Rathi*
***
-*Batch no. 7*