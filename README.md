# Facebook-C-Dataset
## 1. data-Facebook

### 1.1 afterdataset-all-Facebook.csv

uuid: unique identifier

label: 0 for no_rumor and 1 for rumor

type: topic type

### 1.2 embed_bert.pickle

1924*768

features of source tweet

### 1.3 embed_knowledge.csv

777*768

external knowledge

### 1.4 node_gcn_tensor.csv

1924*256

features of structural feature

### 1.5 order_tensor.py

Align the order of structural and textual features

## 2. graph_model.py

GCN for external knowledge extraction

## 3. knoeledge_model.py

Adjacency matrix generation

## 4. model.py

final model for rumor detection

## 5. train.py

final train model for rumor detection

## 6. util.py

util for rumor detection 
