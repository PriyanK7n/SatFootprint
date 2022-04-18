# [SatelliteFootprintDetection](https://priyank7n.me/2021/05/06/SatFoot.html)
> This Project's aim is Footprint Detection of Buildings in High-Resolution Satellite Images by using instance segmentation.

## Dataset Characteristics:
- This open-source dataset includes 24 images (one per month) covering ~100 unique geographies. 
- The dataset will comprise over 40,000 square kilometers of imagery and exhaustive polygon labels of building footprints in the imagery, totaling over 10 million individual annotations. 
- The Data – ~100 locations, spread out across the globe and contains:

## Dataset : 
*  The Dataset is available for download on [**kaggle**](https://www.kaggle.com/amerii/spacenet-7-multitemporal-urban-development)

*  The Dataset is available for download on  AWS as a Public Dataset:
      > **Training Data**
      - aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_train.tar.gz . 
      - aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_train_csvs.tar.gz . 
      > **Testing Data**
      - aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_test_public.tar.gz . 
**Align center:**

<p align="center" width="100%">
    <img width="50%" src="https://github.com/PriyanK7n/SatFootprintDetection/blob/main/images/details.png">
    <img width="50%" src="https://github.com/PriyanK7n/SatFootprintDetection/blob/main/images/s7.gif">
</p>
           
## Models:
The Models trained are stored in [**GoogleDrive**](https://drive.google.com/drive/folders/1qEviop9V3YLVpssFER1LMG-Z3B8y38dJ?usp=sharing)

## BLOG POST:
The Whole Project is documented in this [**Blog Post**](https://priyank7n.me/2021/05/06/SatFoot.html) 

## Results 
https://user-images.githubusercontent.com/44031169/159185584-08eb5679-e7ee-4c3c-b651-2639b851123e.mp4


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ZGvyBiOw4D4/0.jpg)](https://www.youtube.com/watch?v=ZGvyBiOw4D4)


## Installation:
~~~~~~~~~~~~

GIT:

.. code-block:: bash

  git clone https://github.com/PriyanK7n/SatFootprint
  cd SatFootprint
  pip install -r requirements.txt
  pip install -e .


