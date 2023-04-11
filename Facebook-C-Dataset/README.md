# *Facebook-C-Dataset*

The dataset constructed in the paper BGEK: Incorporating External Knowledge[[d1\]](#_msocom_1) into Graph Convolutional Networks for Cantonese Rumor Detection in Online Social Networks, which contains 1924 events and 64221 posts.

## Facebook_id_label
It contains the information of source tweets, including uuid and label.

The tweet with a label of '1' is annotated as a rumor. Otherwise, a non-rumor.

## Facebook_tree.csv
It contains the graph structure information of retweets/comments, including uuid, parent, child, text.

- uuid: tweet id of source tweet
- parent: index of parent node
- child: index of current node
- text: space separated index-count pairs, where a index-count pair is in format of _index:count_. Index-count pairs are extracted from text contents of tweets

