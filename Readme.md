## Introduction
The goal for this notebook is to produce a submission file to participate in Kaggle I’m Something of a Painter Myself. https://www.kaggle.com/competitions/gan-getting-started

## Dataset description:
The dataset consists on two sets of files: one set with 300 Monet paintings and 7038 real photos. 

## Problem description:
The problem is to copy the style of the Monet paitings into the real photos

## Approach:
Import the photos and paintings in two separate datasets. Create a cycle GAN and use the datasets to train two generators and two discriminators. Use the generator for Monet-like images to generate files from the photos dataset, save them in jpeg format and zip them in one file
