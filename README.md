# Facebook-friend-recommedation
Machine learning model to recommend Facebook friend's

## Problem statement:
Given a directed social graph, we have to predict missing links to recommend friends/connnections/followers (Link Prediction in graph).

## Data Overview
Dataset from facebook's recruting challenge on kaggle: https://www.kaggle.com/c/FacebookRecruiting
Data contains two columns: source and destination edge pairs in the directed graph.

## Data columns (total 2 columns):
source_node int64
destination_node int64

## Business objectives and constraints:
<li>No low-latency requirements.</li>
<li>Predciting the probability of a link is useful so as to recommend the highest probability links to a user.</li>
<li>We got to suggest connnections which are most likley to be correct and we should try and not miss out any connnections.</li><br>

## Performance metric for supervised learning:
<li>Both precision and recall are important, hence F1 score is good choice </li>
<li>Confusion matrix </li>
<li>Accuracy can also be checked </li>
