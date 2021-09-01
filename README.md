### The source code of "Teacher-Student Learning: Efficient Hierarchical Message Aggregation Hashing for Cross-Modal Retrieval"

#### 1. Basic demo

You can easily train our model on MS COCO dataset with the following code:

    chmod a+x ./train.sh
    ./train.sh

#### 2. Using the model on your dataset

(1) Firstly, you need to divide the dataset into three parts: train, query, retrieval. Each part should contain image features, text features and labels.

(2) Then, place the partitioned dataset in the '/Data' directory.

(3) Finally, change the corresponding parameters and train the model.

#### 3. Download our MS COCO dataset
        
    Google Drive Link:
        https://drive.google.com/drive/folders/1-Ru-NOaIukbJj_wL1rUh7jThOTGwPmKM?usp=sharing