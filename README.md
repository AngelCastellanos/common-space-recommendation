# A Concept-driven Common Representation Space for Recommendation
=================================================================================

Results and specific detail used for the paper "A Concept-driven Common Representation Space for Recommendation" by [Ángel Castellanos](http://nlp.uned.es/~acastellanos/), [Ana García-Serrano](http://nlp.uned.es/web-nlp/index.php?option=com_content&view=article&id=11) and [Juan Cigarrán](http://nlp.uned.es/~juanci/)

## Dataset

For experimentation we made use of the "2nd Linked Open Data-enabled Recommender Systems Challenge" dataset. For more detail on the dataset, please refer to:

[http://sisinflab.poliba.it/events/lod-recsys-challenge-2015/dataset/](http://sisinflab.poliba.it/events/lod-recsys-challenge-2015/dataset/)

## Code

The baselines as well as the state-of-the-art approaches to which our FCA-based approach has been compared have been implemented with the help of LibRec: A Java Library for Recommender Systems:

[http://www.librec.net](http://www.librec.net)

The specific configuration files used in the experimentation in the paper is included at: [code/librec](https://github.com/AngelCastellanos/common-space-recommendation/tree/master/code/librec)

The code related to our proposal is included at [code/fca](https://github.com/AngelCastellanos/common-space-recommendation/tree/master/code/fca)

## Results

[results/task1](https://github.com/AngelCastellanos/common-space-recommendation/tree/master/results/task1) includes the results for the Task 1: Top-N recommendations from unary user feedback. This task deals with the top-N recommendation problem, in which a system is requested to find and recommend a limited set of N items that best match a user profile, instead of correctly predict the ratings for all available items.

[results/task2](https://github.com/AngelCastellanos/common-space-recommendation/tree/master/results/task2) includes the results for the Task 2: Diversity within recommended item sets. In this task, the evaluation will be made by considering a combination of both accuracy of the recommendation list, and the diversity of items belonging to it

For more details on the specific aspects of each task, please refer to [http://sisinflab.poliba.it/events/lod-recsys-challenge-2015/tasks/](http://sisinflab.poliba.it/events/lod-recsys-challenge-2015/tasks/)




