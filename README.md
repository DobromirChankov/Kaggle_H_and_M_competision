# Kaggle_H_and_M_competision
H&amp;M Personalized Fashion Recommendations

There are two sollotions I've prepared.

# 1. Solution for a *Kaggle's* competition

#### ["H&M Personalized Fashion Recommendations"]('https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations')

Autor: Dobromir Chankov

30.4.2023

_**Abstract**_

Task is to deliver a working notebook, as much complete as possible project on the referenced competition following the guidelines of the data science development standard [CRISP-DM.]('https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining')



I choose an approach of a simple segmentation depending on how customers are buying:

 - trought internet (on-line) or
 - visiting the shop (on-place)

My approach shows a system of algorithms for *partitioned validation* based on one-week retention time (between 4-11 days).

The structure of this project is as following:

1. *EDA*
2. *Modeling*
3. *Final prediction*
4. *Conclusion*
5. *References*

The main idea is that the predictions for "on-line"customers are more precise then for those buying in shops.

And the final results of the projects are clear proof for this:

MAP@12(average precision) of a weekly hold-on validation is around:
 + 0.0187 for on-line and 
 + 0.0306 for on-place customers.

During my work I used and learned from great discussions and some notebooks shared in public.

I'm really very thankful to all the authors.

__*NOTE__: because of security reasons(internet interruption) I've downloaded the files(**_datasets_**) from kaggle.com.

# 2. Solution with Neural Network(RNN)

During the holydays I've tried to give second solution with a recurrent neural network (RNN).

At the moment I'm facing some difficulties and my code is not $100 \%$ ready yet.
