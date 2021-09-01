### The source code of "Teacher-Student Learning: Efficient Hierarchical Message Aggregation Hashing for Cross-Modal Retrieval"

#### 0. Prepare

Our training environment(only as reference):
    
    Python 3.6.2
    Pytorch 1.5.0
    RTX2080Ti + CUDA 10.2

#### 1. Basic demo

You can easily train our model on MS COCO dataset with the following code:

    chmod a+x ./train.sh
    ./train.sh

#### 2. Using the model on your dataset

(1) Firstly, you need to divide the dataset into three parts: train, query, retrieval. Each part should contain image features, text features and labels.

(2) Then, place the partitioned dataset in the '/Data' directory.

(3) Finally, change the corresponding parameters and train the model.

#### 3. Experimental results on MS COCO

You can easily reimplement the experimental results using the above code. The MS COCO dataset link in Section.4.
    
    [16 bits]
        mAP@500 on I2T: 0.691
        mAP@500 on T2I: 0.800
    
    [32bits]
        mAP@500 on I2T: 0.732
        mAP@500 on T2I: 0.869
    
    [64bits]
        mAP@500 on I2T: 0.763
        mAP@500 on T2I: 0.904
    
    [128bits]
        mAP@500 on I2T: 0.790
        mAP@500 on T2I: 0.934
    
    [256bits]
        mAP@500 on I2T: 0.808
        mAP@500 on T2I: 0.947
    
#### 4. Download our MS COCO dataset
        
    Google Drive Link:
        https://drive.google.com/drive/folders/1-Ru-NOaIukbJj_wL1rUh7jThOTGwPmKM?usp=sharing
  

#### 5. Citation      

    To be determined.